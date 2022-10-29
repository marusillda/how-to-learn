# Проект "Научиться учиться"

## [Демонстрация сайта](https://marusillda.github.io/how-to-learn/)

![Превью проекта](https://github.com/marusillda/how-to-learn/blob/main/how%20to%20learn.gif)

## ***Содержание:***
- [Описание проекта](#Description)
- [Используемые технологии](#Technologies)
- [Структура каталога проекта](#ProjectStructure)
- [Оценка качества кода](#Quality)
- [Планы по доработке проекта](#Planes)


# Описание проекта <a name="Description"></a>

**How to learn** — мой первый самостоятельный проект в рамках обучения на курсе "Web-разработчик" в Яндекс Практикум. В рамках обучения для выполнения проектной работы были предоставлены макеты, по которым нужно было сверствать сайт. Проект посвящен тому, как правильно изучать материал. В нем представлены конкретные техники и упражнения, которые помогут изменить подход к обучению и сделать его более эффективным.


# Используемые технологии <a name="Technologies"></a>

1. Проект реализован с помощью языка разметки HTML5.

2. За описание внешнего вида сайта отвечает язык каскадных таблиц стилей CSS.

3. Все элементы страницы и стили реализованы в соответствии с концепцией [БЭМ](https://ru.bem.info/methodology/quick-start/).

4. При размещении элементов на странице использовалась технология для создания сложных гибких макетов [CSS Flexbox](https://doka.guide/css/flexbox-guide/).

5. На старнице есть анимированные элементы, которые были реализованы с помощью [keyframes](https://doka.guide/css/animation/#keyframes).

6. Все ссылки на странице анимированы и при наведении мыши плавно становятся немного прозрачными. Этот эффект реализован с использованием [псевдоклассов](https://doka.guide/css/pseudoclasses/) и свойства [CSS Transition](https://doka.guide/css/transition/).

7. Для отображения видео с YouTube используется контейнер [iframe](https://doka.guide/html/iframe/).

# Структура каталога проекта <a name="ProjectStructure"></a>

```
📦how-to-learn
 ┣ 📂blocks
 ┃ ┣ 📂cards
 ┃ ┃ ┣ 📂__description
 ┃ ┃ ┃ ┗ 📜cards__description.css
 ┃ ┃ ┣ ...
 ┃ ┣ 📂section-subtitle
 ┃ ┃ ┣ 📂_theme
 ┃ ┃ ┃ ┗ 📜section-subtitle_theme_dark.css
 ┃ ┃ ┗ 📜section-subtitle.css
 ┣ 📂images
 ┣ 📂pages
 ┃ ┗ 📜index.css
 ┣ 📂vendor
 ┃ ┗ 📜normalize.css
 ┣ 📜.editorconfig
 ┣ 📜.nojekyll
 ┣ 📜index.html
 ┗ 📜README.md

📜.editorconfig - Файл настроек форматирования кода
📜.nojekyll     - Пустой файл, нужен для корректной публикации в GitHub Pages
📜index.html    - Главная страница сайта
📜README.md     - Файл документации проекта
📂blocks        - Каталог, содержащий CSS стили согласно концепции Nested BEM
📂images        - Каталог, содержащие изображения
📂pages         - Каталог в котором подключаются CSS стили, необходимые конкретной странице
📂vendor        - Каталог с 3rd-party зависимостями
```
# Оценка качества кода <a name="Quality"></a>
Качество кода обусловлено его проверкой по чек-листу Яндекс Практикума, автоматическими проверками и код-ревью специалистом Яндекс Практикума.

Для преварительной прверки использованы валидаторы
- [Markup Validation Service](https://validator.w3.org/#validate_by_uri)
- [Генератор HTML-дерева](https://yoksel.github.io/html-tree/)
- [BEMValidator](https://nglazov.github.io/bem-validator-page/)

# Планы по доработке проекта <a name="Planes"></a>
- Исправить стили, добавив вендорные префиксы, чтобы страница стала кроссбраузерной.
- Исправить стили, реализовав адаптивную верстку, чтобы сайт корректно отображался на экранах шириной меньше 1100px.
