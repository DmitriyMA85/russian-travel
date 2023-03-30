# Проект: Путешествие по России
Проектная работа ппосле третьего сплита
### Страница сайта где представлено информация про красивые места России, доступные для путешествинников (страница выполнена на русском языке)
На данной странице представлена следующая информация:
1. *Общая информация про путешетвие по России*
2. *Фотографии красивейших мест России*
3. *Описание и фотография Куршской косы*
4. *Описание и фотография Кольского полуострова*
5. *Описание и фотография Алтая*
6. *Описание и фотография зимнего Байкала*
7. *Описание и фотография Карелии*

В данном проекте автором были использованы основные разметки HTML и закреплены использования основных свойств CSS, с выполнением адаптивной верстки на четыре размера экрана 320px,768,1024px,1240px через метод Mobile First, а также использованы следующие техники:

1. Подключение шрифтов:
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
2. Трансформации: 
```css 
.footer__link:hover {
    color:gray;
}
```
3. Создание необходимых ссылок внутри страницы сайта:
```html
 <a href="#" lang="en" class="header__lang-link header__lang-link_ru">Ru</a>
```
4. Добавление псевдоэлемента: 
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
5. Выполнение таблицы c использованием Grig
```css 
.gallery {
    width: 288px;
    min-height: 2724px;
    display: grid;
    gap: 12px;
}
```
6. Оформление структуры файлов по БЭМ

Планы по доработки:
1. Создание новых страниц и взаимодействий между друг другом.
2. Добавление и подключение кода в JavaScript.