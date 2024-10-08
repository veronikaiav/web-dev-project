# Задание: сверстать сайт с шаблона PSD 1 в 1.

Ограничения:
- Использовать только относительные единицы измерения
- Не использовать старые приемы
- По максимуму старайся использовать HTML5 семантические тэги.

Допущения:
- На данный момент сделать всё без JS, а именно: кнопки могут не работать, постинг коментариев тоже
- Делай сайт под свой экран, используй Desktop First подход.
- Иконки/картинки могут быть любые
- Тему сайта можешь поменять, главное, чтобы вся конструкция сохранилась

Правила:
1. Поделить на компоненты, которые будут в твоем сайте. Изначально написать список названий компонентов.
2. Создать папку, назвать  ёе названием сайта, продумать про что сайт будет, в случае, если тема меняется.
3. Инициализировать гит локально, создать репозиторий на гитхаб, связать их.
4. Добавить Readme.md файл (почитать про него) в репозиторий с описанием проекта, заданием и списком компонентов из первого пункта. Также добавить JPG файл из ссылки с картинкой сайта. Сделать первый коммит Initial Commit.
5. Найти весь контент. Иконки, картинки, которые будешь использовать на сайте. Сделать коммит
6. Написать скелет-основу для сайта. Написать нужные метатэги, написать html, подключить css, настроить лайаут на сайт. Сделать коммит с этим.
7. Начать верстать по компоненту сверху вниз. Сделала компонент — закоммитила. На данный момент можешь использовать одну ветку (master).
8. !important Не начинать верстать следующий компонент, пока не сверстала предыдущий. :)

Ход действий:
1. Создать ветку.
2. Переключиться на нее.
3. Сделать задачу в этой ветке.
4. Открыть пул реквест.

[Прототип сайта (картинка)](prototype/web-dev-project.jpg)

Список компонентов:

- хэдер
  - лого
  - меню
    - меню айтем
  - поиск
- мейн блок
  - кнопка

- блок-контейнер (базовый контейнер для блока)

- About Us блок
  - карточка About Us
- Services блок
  - карточка Services
  - кнопка 
- Latest Work блок
  - фильтр
    - кнопка
  - карточка Latest Work
  - кнопка
- Pricing Plan блок
  - карточка Pricing Plan
    - кнопка
- Our Team Member блок
  - карусель
    - карточка Our Team Member
      - фото
      - иконки
- Blog блок
  - статья
    - картинка
    - текст
  - кнопка
- Contact Us блок
  - карточка контакта
  - форма
- футер

## Выводы

Планирование:
- делать декомпозицию более осознанно и глубоко.
- не бояться разделять на мелкие детали (пример, menu и menu-item).
- находить на этапе декомпозиции компоненты, которые можно будет переиспользовать.

Верстка:
- не использовать внешние отступы в переиспользуемых компонентах
- не использовать выравнивание в переиспользуемых компонентах
- латиница в коде - ... на проде
- ПРЕЖДЕВРЕМЕННАЯ ОПТИМИЗАЦИЯ - КОРЕНЬ ВСЕХ ЗОЛ ПРОГРАММИРОВАНИЯ. Дональд Кнут
- при верстке компонента можно сразу делать простой вариант, например используем абсолютные единицы, затем относительные (преждевременная оптимизация)
- продумывать относительные единицы относительно чего лучше использовать)))
- используем сервис Font Awesome для добавления иконок
- оставлять одну пустую строку
- проверять, не едет ли верстка при масштабировании (например, карточек работников, преимуществ компании)
- проверять работает ли focus на необходимых элементах
- все классы, прописанные в html, должны быть используемы
- удалять лишние (неиспользуемые) файлы


 
