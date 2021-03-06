# Разработанные проекты

## Проекты

### :airplane: **Avia search results (v.0.4)** | [Preview](https://test-task-gridnine-systems.vercel.app/) | [Repository](https://github.com/it-amalker/test-task-gridnine-systems)

**_Стек:_** JS, React, Webpack.

**_Краткое описание:_** Тестовое задание, страничка вывода результатов поиска авиа билетов, с возможностью применения фильтров и сортировки. Данные о перелетах берутся из JSON, затем рендерится результативный список авиа перелетов в виде карточек. К данным карточкам можно применять сортировку (по возрастанию/убыванию цены или продолжительности полета), а также фильтры (без пересадок, max/min порог цены).

**_Описание разработки:_** Приложение написано на фреймворке _React_. Сборкой бандла проекта занимается _Webpack_. Для манипулирования с датами и временем использовал библиотеку _date-fns_. Также реализовал интернационализацию с помощью _i18next_ с возможностью переключения английского и русского языков.

### :round_pushpin: **Routes (v.0.7)** | [Preview](https://routes-app.amalker.vercel.app/) | [Repository](https://github.com/it-amalker/routes-app)

**_Стек:_** TypeScript, React, Webpack, Google Maps API.

**_Краткое описание:_** Приложение для построения маршрутов на Google Maps.

**_Чему научился:_** При разработке использовал _Typescript + React_. Научился работать с несколькими _Google APIs_ (Maps, Places, Directions, Geocoding). Для работы с Google Maps API в React использовал библиотеку _@react-google-maps/api_. Компонент поиска по карте с выпадающим списком реализовал с помощью _Combobox (Reach UI)_. Также получил опыт построения _Drag&Drop_ интерфейса для взаимодействия с точками на карте. Все маркеры на карте являются _интерактивными_ и маршрут динамически перестраивается на любые изменения положения маркеров (также обновляется адрес благодаря взаимодействию с Geocoding API), в том числе посредством использования D&D-интерфейса.

**UPD.** Добавил выбор типа построения маршрута (автомобильныйб велосипедный, пешеходный). Добавил геолокацию, теперь при запуске приложения стартовая локация отображается согласно вашего местоположения.

**_В планах:_** Покрыть приложение тестами.

### :page_facing_up: **Table (v.0.5)** | [Preview](https://test-task-bim-info-ru.amalker.now.sh/) | [Repository](https://github.com/it-amalker/test-task-bim-info-ru)

**_Стек:_** TypeScript, React, Webpack.

**_Краткое описание:_** Тестовое задание, небольшое приложение по работе с табличными данными. Приложение подгружает данные из JSON и выводит в виде таблицы. После чего данные можно сортировать, добавлять новые поля, редактировать и удалять существующие. Редактирование реализовано по клику на табличную строку. Если применена сортировка, то она не сбрасывается и отрабатывает корректно при любых манипуляциях с табличными данными.

**_Описание разработки:_** Приложение написано на _Typescript_, а также с использованием фреймворка _React_. Для работы с формами и их валидацией воспользовался _react-hook-form_. Для сборки проекта использовал _Webpack_.

### :partly_sunny: **Weather (v.0.11)** | [Preview](https://weather-puce.now.sh/) | [Repository](https://github.com/it-amalker/Weather)

**_Стек:_** TypeScript, React, Webpack, GH Actions.

**_Краткое описание:_** Приложение для проверки погоды в любом городе.

**_Чему научился:_** Приложение разработал на фреймворке _React_, для управления формой использовал _react-hook-form_. Научился получать данные по _API_ и организовывать взаимодействие между _несколькими API_, работать с переменными окружения с помощью плагина _dotenv_, а также научился настраивать _Webpack_ отдельно под production, где переменные окружения работаю корректно.

**UPD.** Переписал приложение на _Typescript_. Научился работать и описывать типы, работать с типами в _React_. Также настроил окружение: сборкой бандла занимается _Webpack_, транспиляцию кода настроил через _Babel (TypeScript => Babel => JS)_, перенастроил _Eslint+Prettier_.

**UPD2.** Переписал приложение c использованием _styled-components_. Изменил структуру компонентов, теперь каждый компонент находится в отдельной директории, в которой также находятся модули стилей и юнит тестов. Начал покрывать приложение тестами с помощью Enzyme\Jest.

### :cyclone: **Slack-chat (v.0.10)** | [Preview](https://fast-lake-13387.herokuapp.com/) | [Repository](https://github.com/it-amalker/frontend-project-lvl4)

**_Стек:_** JS (ES6), React/Redux, React Bootstrap, Webpack, Websockets, GH Actions.

**_Краткое описание:_** Упрощенная версия Slack-чата.

**_Чему научился:_** Получил опыт разработки с помощью фреймворка _React_, для управления состоянием приложения использовал _Redux_, а для контроля форм - библиотеку _Formik_. Активно взаимодействовал с _бекендом_. Для построения real-time приложения использовал _вебсокеты_. Деплоил проект на _Heroku_.

### :newspaper: **RSS feed aggregator (v.0.9)** | [Preview](https://frontend-project-lvl3-nu.now.sh/) | [Repository](https://github.com/it-amalker/frontend-project-lvl3)

**_Стек:_** JS (ES6), Bootstrap 4, Webpack, GH Actions.

**_Краткое описание:_** RSS-лента с автоматическим обновлением новостей.

**_Чему научился:_** Научился настраивать и использовать сборщик _Webpack_, получил навыки работы с фреймворком _Bootstrap_, научился отправлять запросы с помощью _AJAX (Axios)_. Контролировать валидацию форм с помощью библиотеки _Yup_. Для интернационализации воспользовался фреймворком _i18next_. Приложение написано с соблюдением архитектурного принципа _MVC_.

### :mag_right: **Difference generator (v. 0.10)** | [Repository](https://github.com/it-amalker/frontend-project-lvl2)

**_Стек:_** JS (ES6), Jest, GH Actions.

**_Краткое описание:_** Утилита для поиска отличий между двумя конфигурационными файлами.

**_Чему научился:_** Консольное приложение разработал при помощи техники _TDD_. Для написания unit-тестов использовал библиотеку _Jest_. Закрепил навыки работы с деревьями и построением _АСД_. При разработке применил архитектурные принципы _Фасад_ и _Адаптер_.

### :ghost: **Brain games (v.0.12)** | [Repository](https://github.com/it-amalker/frontend-project-lvl1)

**_Стек:_** JS (ES6), Jest, Travis CI.

**_Краткое описание:_** Небольшое CLI-приложение с пятью играми-головоломками.

**_Чему научился:_** Научился настраивать окружение, работать с _NPM_, использовать транспилятор _Babel_, следить за стилем кода с помощью _Eslint_ и следовать стандартам кодирования _Airbnb_, а также подключать проект к сервису непрерывной интеграции _CI_. Проект написан в _функциональном стиле_. Для написания unit-тестов использовал библиотеку _Jest_.

## Адаптивная верстка | HTML/CSS, БЭМ, SCSS, GULP, JS

**_Чему научился:_** Научился адаптивной верстке с применением _ретинизации_ и _оптимизации графики_. При верстке придерживался методологии _БЭМ_, использовал препроцессор _SCSS_. Для сборки проекта был выбран _Gulp_.

### :bear: **Mishka** | [Preview](https://it-amalker.github.io/mishka/build) | [Repository](https://github.com/it-amalker/mishka)

**_Краткое описание:_** Интернет-магазин изделий ручной работы.

### :cherries: **Pink** | [Preview](https://it-amalker.github.io/pink/build) | [Repository](https://github.com/it-amalker/pink)

**_Краткое описание:_** Веб-сайт небольшого приложения для смартфонов.

## Верстка | HTML/CSS, JS

**_Чему научился:_** Научился семантической верстке _HTML5_, применять стили _CSS_, верстать _кроссбраузерно_, оживлять модальные окна и слайдеры с помощью _JS_.

### :battery: **Device** | [Preview](https://it-amalker.github.io/device/index.html) | [Repository](https://github.com/it-amalker/device)

**_Краткое описание:_** Интернет-магазин электроники.

### :ice_cream: **Gllacy** | [Preview](https://it-amalker.github.io/gllacy/) | [Repository](https://github.com/it-amalker/gllacy)

**_Краткое описание:_** Интернет-магазин мороженного.

### :hammer: **Technomart** | [Preview](https://it-amalker.github.io/technomart/index.html) | [Repository](https://github.com/it-amalker/technomart)

**_Краткое описание:_** Интернет-магазин строительных материалов и инструментов для ремонта.

### :sunrise_over_mountains: **Sedona** | [Preview](https://it-amalker.github.io/sedona/index.html) | [Repository](https://github.com/it-amalker/sedona)

**_Краткое описание:_** Туристический сайт-визитка американского городка Седона.

### :city_sunrise: **Nerds** | [Preview](https://it-amalker.github.io/nerds) | [Repository](https://github.com/it-amalker/nerds)

**_Краткое описание:_** Веб-сайт небольшой дизайн-студии.
