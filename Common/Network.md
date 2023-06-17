# Вкладка Netrwork
[har файл](https://disk.yandex.ru/d/qB5C9byWBm9-og)
## Дублирование ресурсов
Дважды подгружается (скриншоты ниже с подтверждением): 
- Стили: *bootstrap.min.css*
- JS: *bootstrap.bundle.min.js*, *bootstrap.min.js*, *jquery-3.5.1.js*, *popper.min.js*, *code.js*
- Шрифты: *data:font/worff2*, *fontawesome-webfont.woff2*
 
[Скриншот 1](./imgs/Duplicate-1.png)
[Скриншот 2](./imgs/Duplicate-2.png)
[Скриншот 3](./imgs/Duplicate-3.png)
[Скриншот 4](./imgs/Duplicate-4.png)
[Скриншот 5](./imgs/Duplicate-5.png)

## Лишние размеры ресурсов
- Заместо jquery можно было грузить его минифицированную версию. (см. скриншот выше)

## Медленно загружающиеся ресурсы
Виджеты, которые можно было подгрузить уже после загрузки основной страницы сайта.
[Скриншот](./imgs/Time.png)

## Ресурсы, блокирующие загрузку
JS, который прописан без аттрибута *defer*, например Google Analitycs, различные виджеты сайта.
[Скриншот](./imgs/Blocking.png)

## Что-то еще
Сайт слишком долго получает контент с сервера. В моем случае это время равно 5.03 секундам
[Скриншот](./imgs/First-byte.png)
