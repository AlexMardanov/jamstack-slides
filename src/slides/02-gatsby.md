![Gatsby](https://snipcart.com/media/204347/gatsby-static-site-generator.jpg)

---

## Плюсы

- Данные извлекаются в Gatsby с помощью GraphQL
- Доступна система плагинов
- Создает очень быстрые статические HTML-страницы
- PWA-готов по умолчанию

## Минусы

- Вам нужно иметь полное представление о JS, React и GraphQL, чтобы начать работать с Gatsby.

---

# О чем будет речь

- Часть 1. Вступление
- Часть 2. Основы Gatsby
- Часть 3. Стили в Gatsby
- Часть 4. Данные в Gatsby
- Часть 5. Источники данных и плагины для трансформации
- Часть 6. Диманическое создание страниц
- Часть 7. Работа с картинками в Gatsby
- Часть 8. PWA
- Часть 9. Build & Deploy

---

# Часть 1

- Убирает boilerplate
- Быстрый старт
- Git + Netlify
- Контент от куда угодно
- Настройки по умолчанию = лучший результат
- Оптимизация assets
- Позволяет расширять конфигурации

---

# Часть 2

## Установка и начало работы:

    npm install -g gatsby-cli

    gatsby new hello-world

    gatsby develop

---

## Структура папок:
    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

---

# Часть 3

- CSS и css modules - из коробки
- Styled Components, Emotion, Sass, Less - простая установка

---

# Часть 4

![](https://hsto.org/webt/c7/oq/a1/c7oqa1w2b00akzatd2womwb_daw.png)

---

## Способы получения данных:

[Page Query](https://github.com/gatsbyjs/gatsby-starter-blog/blob/master/src/pages/index.js)

[Static Query](https://github.com/gatsbyjs/gatsby-starter-blog/blob/master/src/components/bio.js)

---

# Часть 5

## Плагины

Можно найти плагин на любой случай жизни.

- Для получения даных с разных источников
- Для трансформации даных
- ...rest

https://www.gatsbyjs.org/plugins/

---

# Часть 6

## Автогенерация страниц

https://www.gatsbyjs.org/docs/api-files-gatsby-node/

---

# Часть 7

## Картинки

Супер оптимизация с помощью плагина

https://www.gatsbyjs.org/packages/gatsby-image/

---

# Часть 8

## PWA

https://www.gatsbyjs.org/docs/progressive-web-app/

- Должен быть HTTPS.
- Должен содержать Web App Manifest.
- Работа с service worker.

---

# Часть 9

## Build & Deploy

![](https://www.netlify.com/img/global/meta-image.jpg)

---

## Примеры

- [CMS](https://gatbsy-netlify-cms.netlify.com)
- [авторизация и приватные роуты](https://gatsby-auth.netlify.com/)
- [магазин](https://store.gatsbyjs.org/)

---

## THE END

![](https://cdn-images-1.medium.com/max/800/1*xl31p_qdHAe73krTJAka_Q.gif)

##### ...вопросы?
