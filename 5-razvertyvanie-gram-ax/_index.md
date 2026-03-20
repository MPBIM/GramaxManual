---
order: 5
title: 5. Развертывание Gram.ax
---

Текущая версия gramax представляет из себя open-source решение, которое развернуто на корпоративном сервере с IP10.50.2.22

Разворачивание с применением Docker выполнялось в применение технической документации <https://gram.ax/resources/docs>

Для оформления корпоративного пространства применялись следующие логотипы и стили:

[home_logo_dark.svg](./home_logo_dark.svg)

[home_logo_light.svg](./home_logo_light.svg)

```css
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,400;0,600;0,700;0,900;1,400&display=swap');

:root {
    --article-max-width: 55%;
}

#custom-style {
    --app-font-famaly: 'Source Sans Pro', sans-serif;
}

#custom-style[data-theme="light"] {
    --color-article-heading-text: #222222;
    --color-article-text: #444444;
    --color-nav-menu-bg: #ffffff;
    --color-right-nav-bg: #ffffff;
    --color-nav-item-selected: #2E7AEB;
    --version-control-primary: #2E7AEB;
    --color-link: #2E7AEB; /* ссылки как выделение */
}

/* Заголовки и жирный текст */
#custom-style[data-theme="light"] h1,
#custom-style[data-theme="light"] h2,
#custom-style[data-theme="light"] h3,
#custom-style[data-theme="light"] h4,
#custom-style[data-theme="light"] h5,
#custom-style[data-theme="light"] h6 {
    font-weight: 700 !important;
}

#custom-style[data-theme="light"] strong,
#custom-style[data-theme="light"] b {
    font-weight: 700 !important;
}

#custom-style[data-theme="dark"] {
    --color-article-heading-text: #ffffff;
    --color-article-text: #dddddd;
    --color-nav-menu-bg: #1a1e33;
    --color-right-nav-bg: #1a1e33;
    --color-nav-item-selected: #2E7AEB;
    --version-control-primary: #2E7AEB;
    --color-link: #2E7AEB; /* ссылки как выделение */
}

#custom-style[data-theme="dark"] h1,
#custom-style[data-theme="dark"] h2,
#custom-style[data-theme="dark"] h3,
#custom-style[data-theme="dark"] h4,
#custom-style[data-theme="dark"] h5,
#custom-style[data-theme="dark"] h6 {
    font-weight: 700 !important;
}

#custom-style[data-theme="dark"] strong,
#custom-style[data-theme="dark"] b {
    font-weight: 700 !important;
}
```

:::info 

Стили и логотипы для оформления расположены на сервере Gramax  в папке **workspace/assets**

:::