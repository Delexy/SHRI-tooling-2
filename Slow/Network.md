# Вкладка Netrwork
[har файл](./www.gd.ru.har)
## Дублирование ресурсов
Дважды подгружается (скриншоты ниже с подтверждением): 
- CSS: *bootstrap.min.css*
- JS: *bootstrap.bundle.min.js*, *bootstrap.min.js*, *jquery-3.5.1.js*
- Шрифты: *data:font/worff2*
 
[Скриншот 1](./imgs/Duplicates-1.png)
[Скриншот 2](./imgs/Duplicates-2.png)
[Скриншот 3](./imgs/Duplicate-3.png)

## Лишние размеры ресурсов
- Заместо jquery можно было грузить его минифицированную версию (см. скриншоты выше).

## Медленно загружающиеся ресурсы
При замедлении тайминги увеличились и теперь топ по длительности загрузки выглядит следующим образом:
[Скриншот](./imgs/Timing.png)

## Ресурсы, блокирующие загрузку
JS, который прописан без аттрибута *defer*, например в данном случае main.js и context.js, различные виджеты сайта.
[Скриншот](./imgs/Blocking.png)

## Что-то еще
Сайт слишком качает контент сайта: 18,57 s
[Скриншот](./imgs/FB.png)
