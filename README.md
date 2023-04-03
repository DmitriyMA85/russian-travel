# Проект: Путешествие по России
Проектная работа по результатам обучения 3 сплита
Данная работа выложена на GitHub Pages и её можно посмотреть по ссылке https://dmitriyma85.github.io/russian-travel/
------
### Страница сайта где представлена информация по достиинствам путешествия и интересным местам России (страница выполнена на русском языке)
1. *Обшая информация по пушествию по России*
2. *Галерея красивейших мест России*
3. *Описания и фотография Куршской косы*
4. *Описания и фотография Кольского полуострова*
5. *Описания и фотография Алтая*
6. *Описания и фотография Зимнего Байкала*
7. *Описания и фотография Карелии*

Для оформления данного проекта мною была выполнена адаптивная верстка для четырех размеров экрана 320px, 768px,1024px и 1240px, применив способ верстки Mobile First, и использованы следующие техники:
1. Подключение шрифтов
```css
@font-face {
    font-family: 'Inter';
    font-style:  normal;
    font-weight: 400;
    src: url("../fonts/Inter-Regular.woff2") format("woff2"),
         url("../fonts/Inter-Regular.woff") format("woff"),
         url("../fonts/Inter-Regular.ttf") format("truetype");
         
  }
```
2. Изменения свойства элемента при наведении на него курсора мыши 
```css 
.footer__link:hover {
    color:gray;
}
```
3. Добавление необходимых ссылок
```html
<a href="#" lang="en" class="header__lang-link header__lang-link_en">En</a>
```
4. Добавление псевдоэлементов
```css
.cover::after {
    content: "";
    position: absolute;
    background-image: url(../../images/cover-trains.jpg);
    background-size: contain;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    opacity: .3;
    z-index: -1;
}
```
5. Использования технологии Grid
```css
 .gallery {
    width: 288px;
    min-height: 2724px;
    display: grid;
    gap: 12px;
}
```
5. Оформление структуры файлов по БЭМ
6. Создание и форматирование документов в Git, вкдючая работку с веткамию


Планы по доработки:
1. Создание новых страниц и взаимодействий между друг другом.
2. Добавление кода в JS.