# React с нуля

Пошаговое преобразование кода в полноценное приложение на React.
Примеры кода для вебинара. В ветке `master` последний шаг преобразований кода.
Форкайте репозиторий и творите!

- [Презентация](https://www.figma.com/proto/Wlno4o4ZuAFhsavUdCMsJh/React-%D1%81-%D0%BD%D1%83%D0%BB%D1%8F-%D0%92%D0%B5%D0%B1%D0%B8%D0%BD%D0%B0%D1%80-ylab.io?page-id=0%3A1&node-id=1%3A3&viewport=257%2C246%2C0.2668256163597107&scaling=min-zoom&hotspot-hints=0)

## Шаг 1 (ветка `step1`)

```git checkout step1```

Одностраничное приложение (SPA) на чистом JavaScript. Создаём каждый тег методом `document.createElement`.
Выводим список записей, добавляем, удалением записи. При изменении списка записей приложение
пересоздаёт DOM.

## Шаг 2 (ветка `step2`)

```git checkout step2```

Подключаем React классическим способом через тег `<srcipt>` - быстрый старт с нуля 🙂.
Решаем задачу оптимального обновления DOM. В разметке используется `React.createElement`

## Шаг 3 (ветка `step3`)

```git checkout step3```

Подключаем Babel классическим способом через тег `<srcipt>`. Всем скриптам добавляем транспиляцию
современных возможностей JAvaScript и разметки в `JSX`. Код приложения переписываем на использование
синтаксиса тегов `JSX` вместо `React.createElement`

## Шаг 4 (ветка `step4` или `master`)

```git checkout step4```

Подключаем Webpack для сборки приложения. Теперь у нас модульная архитектура, скрипты изолированные
друг от друга, их не надо подключать вручную в `<srcipt>`. Исходный код перенесён в `/src`.

