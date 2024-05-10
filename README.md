# «Cypress 2»

## Решения
### Задание 1
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/package.json">package.json</a> со скриптами запуска тестов с различными конфигурациями.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress.config.js">cypress.config.js</a> - настройки прогона автотестов.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/support/commands.js">commands.js</a> - переиспользуемые методы взаимодействия со страницами.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.7/cypress/fixtures">cypress/fixtures</a> - репозиторий с тестовыми данными и селекторами.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.7/cypress/e2e">cypress/e2e</a>. - Репозиторий с автотестами.
* <a href="https://cloud.cypress.io/projects/d418g3/runs?branches=%5B%5D&committers=%5B%5D&flaky=%5B%5D&page=1&status=%5B%5D&tags=%5B%5D&timeRange=%7B%22startDate%22%3A%221970-01-01%22%2C%22endDate%22%3A%222038-01-19%22%7D">Dashboard</a> - дашборд с тестами.

<a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.7">Репозиторий</a> с Cypress проектом.

### Задание 2
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/package.json">package.json</a> - со скриптом запуска тестов cypress.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress.config.js">cypress.config.js</a> с прописанным базовым URL для e2e тестов cypress.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/support/commands.js">commands.js</a> - переиспользуемые методы взаимодействия со страницами..
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/fixtures/api.json">api.json</a> - описание тела запроса.
* <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/e2e/api.cy.js">api.cy.js</a> - автотесты.
* <a href="https://cloud.cypress.io/projects/d418g3/runs?branches=%5B%5D&committers=%5B%5D&flaky=%5B%5D&page=1&status=%5B%5D&tags=%5B%5D&timeRange=%7B%22startDate%22%3A%221970-01-01%22%2C%22endDate%22%3A%222038-01-19%22%7D">Dashboard</a> - дашборд с тестами.

<a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/API%207.7">Репозиторий</a> с Cypress проектом.
## Что было сделано
### Задание 1
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/.gitignore">.gitignore</a>.
* Составлены сприпты запуска тестов в различных конфигурациях в <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/package.json">package.json</a>
(браузеры, тест-комплекты, параллельные запуски).
* Составлен <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress.config.js">cypress.config.js</a>,
 с таймаутами, базовым URL и количеством попыток воспроизведения тестовых сценариев.
* Составлен <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/support/commands.js">commands.js</a> с методами, в которые вынесены повторяющиеся операции на странице.
* Создан репозиторий <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/7.7/cypress/fixtures">cypress/fixtures</a>, содержащий в себе:
  * <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/fixtures/selectors.json">selectors.json</a> - описание селекторов для дальнейшего переиспользования.
  * <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/fixtures/auth.json">auth.json</a> - данные для авторизации.
  * <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/fixtures/booking.json">booking.json</a> - тестовые данные.
* Написаны E2E автотесты бронирования билетов <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/booking.cy.js">booking.cy.js</a>,
 авторизации <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/authorization.cy.js">authorization.cy.js</a>.
* Написаны простые API тесты на код ответа <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/dir_1/apiStatus.cy.js">apiStatus.cy.js</a>
и ContentType <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/dir_1/apiContentType.cy.js">apiContentType.cy.js</a>.
* Написан UI тест <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/dir_2/poster.cy.js">poster.cy.js</a>
и параметризированный тест <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/7.7/cypress/e2e/dir_2/bookingData.cy.js">bookingData.cy.js</a>.
* Поключен <a href="https://cloud.cypress.io/projects/d418g3/runs?branches=%5B%5D&committers=%5B%5D&flaky=%5B%5D&page=1&status=%5B%5D&tags=%5B%5D&timeRange=%7B%22startDate%22%3A%221970-01-01%22%2C%22endDate%22%3A%222038-01-19%22%7D">Dashboard</a>
 к проекту.

### Задание 2
* Создан <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/.gitignore">.gitignore</a>.
* Составлены сприпты запуска тестов cypress в <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/package.json">package.json</a>.
* Составлен <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress.config.js">cypress.config.js</a>,
 с базовым URL.
* Составлен <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/support/commands.js">commands.js</a> с методами, в которые вынесены повторяющиеся операции на странице.
* Составлен <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/fixtures/api.json">api.json</a>, в
  <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/tree/main/API%207.7/cypress/fixtures">cypress/fixtures</a>, описывающий BODY для PUT метода API запроса.
* Составлены API автотесты <a href="https://github.com/Nephedov/jsaqa-code-Nephedov93/blob/main/API%207.7/cypress/e2e/api.cy.js">api.cy.js</a>.
* Подключен <a href="https://cloud.cypress.io/projects/8nkxm7/runs?branches=%5B%5D&committers=%5B%5D&flaky=%5B%5D&page=1&status=%5B%5D&tags=%5B%5D&timeRange=%7B%22startDate%22%3A%221970-01-01%22%2C%22endDate%22%3A%222038-01-19%22%7D">Dashboard</a> к проекту.

---
---


## Описание Задания 1. Cypress. Установка и настройка проекта

1. Изучите [приложение](https://github.com/Evgeniy-Varlamov/FS21-diplom) для работы с бронирование билетов в кино.
2. Вы можете тестировать бронирование билетов, логин в админку.
3. Создайте новый проект для тестов на Cypress.
4. Создайте:
  - spec-тест с тестами для проверки корректности отображения главной страницы;
  - spec-тест для проверки логина в админку. Используйте фикстуру для хранения тестовых данных: минимум 2 набора — happy и sad path;
  - spec-тест с UI-тестом для бронирования фильма в доступный зал, название которого вы получаете из админки.

5. Сделайте рефакторинг кода так, чтобы данные обо всех селекторах хранились в фикстурах.

6. Поключите ваш проект к Dashboard.

## Описание Задания 2. Интеграционные тесты

1. Создайте новый проект с test suite (используйте `describe()`) с API-тестами для [проекта](https://petstore.swagger.io/#/).

В вашем наборе должны быть тесты для проверки:
  - создания пользователя;
  - правки пользователя;
  - удаления пользователя.

Тесты должны быть независимыми друг от друга и выполняться в любом порядке.

2. Поключите ваш проект к Dashboard.
