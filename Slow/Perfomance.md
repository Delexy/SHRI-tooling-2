# Вкладка Perfomance
[Файл Perfomance.json](https://disk.yandex.ru/d/Qslnz6Xl2gynWg)
## Измерить время в миллисекундах от начала навигации до событий:
- First Paint (FP): 10019.8 ms = 10.01 s
- First Contentful Paint (FCP): 10341.1 ms = 10.34 s
- Largest Contentful Paint (LCP): 38879.1 ms = 38.87 s
- DOM Content Loaded (DCL): 40649.9 ms = 40.64 s
- Load: ??? - из 10 раз, которые я проводил исследование, ни разу он не сработал, видимо из-за большого времени загрузки (для подтверждения см. файл Perfomance.json в браузере)
 
## Определить, на каком DOM-элементе происходит LCP
LCP происходит на изображении с селектором: *body > div.branded__center.ASE_brandImage > div > a > div > img*
[Скриншот](./imgs/LCP.png)

## Измерить, сколько времени в миллисекундах тратится на разные этапы обработки документа
- Loading: 673 ms
- Scripting: 9054 ms
- Rendering: 13242 ms
- Painting: 3916 ms
[Скриншот](./imgs/Summary.png)
