# Задание: Разработка сайта с использованием OMDb API

## Описание:

Вам предстоит создать одностраничное веб-приложение, которое взаимодействует с OMDb API для поиска информации о фильмах. Сайт должен содержать три основные страницы:

-   Поиск фильмов – позволяет пользователю искать фильмы по названию, отображать результаты поиска и предоставлять возможность лайкать фильмы.
-   Подробная информация о фильме – отображает полную информацию о выбранном фильме.
-   Список лайкнутых фильмов\* – отображает фильмы, которые пользователь отметил лайком.

## Требования:

### Страница поиска фильмов:

-   Поле ввода для ввода названия фильма.
-   Кнопка для выполнения поиска.
-   Список фильмов, соответствующих запросу, с краткой информацией (постер, название, год выпуска).
-   Кнопка "Лайк" рядом с каждым фильмом, позволяющая добавлять фильм в список лайкнутых.
-   Пагинация\*

### Страница подробной информации о фильме:

-   Загружать полную информацию о фильме, используя его imdbID (например: описание, жанры, режиссер, актеры, рейтинг).
-   Отображать постер.
-   Кнопка для лайка фильма.\*

### Страница списка лайкнутых фильмов:

-   Отображать список всех фильмов, которые пользователь отметил лайком.
-   Возможность удалить фильм из списка лайкнутых.
-   Клик по названию фильма ведет на страницу с подробной информацией.

## Технические требования:

-   Как стартер использовать [Vite](https://vite.dev/) (React + TypeScript)
-   Глобальный стейт менеджер [Zustand](https://zustand-demo.pmnd.rs/)
-   Для запросов использовать [axios](https://axios-http.com)
-   Использовать [OMDb API](http://www.omdbapi.com/) для получения данных о фильмах. Документация OMDb API
-   Обеспечить маршрутизацию между страницами (используя React Router).
-   Реализовать хранение списка лайкнутых фильмов с помощью мидлварки persist в стейт-менеджере zustand
-   Под поле ввода и кнопку создавать отдельные пользовательские компоненты

## Сдача задания

1. Создать репозиторий под названием `up09-lab1-{ваша_фамилия}`
2. Оформить pull request из ветки `main` в ветку `done`

## Материалы

Ключ для OMDB API

> `505480d7`
