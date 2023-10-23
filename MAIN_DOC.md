
## План документации для сайта
   * [План документации](##план-документации)
     * [Цель проекта](###цель-проекта)
     * [Цель документации](###цель-документации)
     * [Виды документов](###виды-документов)
     * [Структура и содержание документов](###Структура и содержание документов)
     * [Формат и стиль документов](###Формат и стиль документов)
     * [Инструменты и ресурсы для создания документации](###Инструменты и ресурсы для создания документации)
     * [Процесс создания и обновления документации](###Процесс создания и обновления документации)
     * [Ответственные за создание и обновление документации](###Ответственные за создание и обновление документации)
     * [Виды документов](###Виды документов)
     * [Структура и содержание документов](###Структура и содержание документов)
     * [Формат и стиль документов](###Формат и стиль документов)
     * [Инструменты и ресурсы для создания документации](###Инструменты и ресурсы для создания документации)
   * [План документации для проекта сайта для театра](#План документации для проекта сайта для театра)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
      * [Auto insert and update TOC](#auto-insert-and-update-toc)
      * [GitHub token](#github-token)
      * [TOC generation with Github Actions](#toc-generation-with-github-actions)
   * [Tests](#tests)
   * [Dependency](#dependency)
   * [Docker](#docker)
     * [Local](#local)
     * [Public](#public)


### Цель проекта
Целью проекта является создание сайта для театра, на котором пользователи смогут:

- просматривать информацию о театре, его команде, спектаклях и афише;
- покупать билеты на спектакли онлайн;
- оставлять отзывы и комментарии;
- подписываться на новости и рассылки.

### Цель документации
Целью документации является предоставление полной, точной и актуальной информации о проекте, его функциональности, архитектуре, технологиях и процессах разработки для различных заинтересованных сторон, таких как:

- разработчики;
- тестировщики;
- заказчик;
- пользователи.

### Виды документов
В рамках проекта планируется создать следующие виды документов:

1. Техническое задание - документ, в котором определяются требования к проекту, его цели, функциональность, интерфейс, архитектура и технологии.
2. Документация API - документ, в котором описываются методы, параметры, форматы и примеры запросов и ответов для взаимодействия с бэкендом проекта.
3. Документация кода - документ, в котором комментируются основные классы, функции, переменные и константы в коде проекта.
4. Руководство пользователя - документ, в котором объясняется, как пользоваться сайтом, его функциями и возможностями.
5. Руководство администратора - документ, в котором описывается, как управлять сайтом, его настройками, контентом и безопасностью.

### Структура и содержание документов
Каждый вид документа будет иметь свою структуру и содержание в зависимости от его цели и аудитории. В общем случае каждый документ будет состоять из следующих разделов:

- Введение - раздел, в котором кратко описывается цель и содержание документа, а также указываются обозначения и сокращения.
- Обзор - раздел, в котором даются общие сведения о проекте, его целях, функциональности, архитектуре и технологиях.
- Детали - раздел, в котором подробно описываются все аспекты проекта в соответствии с видом документа. Например, в техническом задании будут перечислены требования к проекту, в документации API будут приведены методы и примеры запросов и ответов, в руководстве пользователя будут показаны скриншоты и инструкции по использованию сайта.
- Приложения - раздел, в котором прилагаются дополнительные материалы, такие как диаграммы, таблицы, ссылки и т.д.

### Формат и стиль документов
Все документы будут создаваться в формате Markdown, который позволяет легко форматировать текст, вставлять изображения, ссылки, таблицы и код. Документы будут иметь единый стиль оформления, который будет соответствовать стандартам и рекомендациям по написанию документации. Например, будут соблюдаться правила орфографии, пунктуации, грамматики, терминологии, заголовков, списков и т.д.

### Инструменты и ресурсы для создания документации
Для создания документации будут использоваться следующие инструменты и ресурсы:

- Visual Studio Code - редактор кода, который поддерживает работу с Markdown и имеет множество расширений для упрощения и улучшения процесса написания документации.
- GitHub - платформа для хранения, управления и совместной работы над кодом и документацией проекта.
- Swagger - инструмент для автоматического создания и тестирования документации API на основе кода.
- Sphinx - инструмент для генерации документации из кода на Python с использованием reStructuredText.
- MkDocs - инструмент для создания статических сайтов из документации в Markdown.
- Read the Docs - сервис для хостинга и публикации документации онлайн.

### Процесс создания и обновления документации
Процесс создания и обновления документации будет состоять из следующих этапов:

- Анализ - этап, на котором определяются цели, аудитория, виды, структура и содержание документов.
- Написание - этап, на котором создаются черновики документов с использованием выбранных инструментов и ресурсов.
- Редактирование - этап, на котором проверяются и исправляются ошибки, неточности и несоответствия в документах.
- Рецензирование - этап, на котором документы проверяются и одобряются заинтересованными сторонами.
- Публикация - этап, на котором документы публикуются в нужном формате и на нужной платформе.
- Обновление - этап, на котором документы поддерживаются в актуальном состоянии в соответствии с изменениями в проекте.

### Ответственные за создание и обновление документации
За создание и обновление документации будут отвечать следующие роли:

- Менеджер проекта - роль, которая координирует процесс создания и обновления документации, определяет требования к ней, назначает ответственных за разные виды документов, контролирует сроки и качество работы.
- Разработчик - роль, которая участвует в создании технического задания, документации API и документации кода, используя свои знания о проекте, его архитектуре и технологиях.
- Тестировщик - роль, которая участвует в проверке правильности и актуальности документации API и кода, используя свои знания о тестировании проекта.
- Копирайтер - роль, которая участвует в создании руководства пользователя и администратора, используя свои навыки написания текстов, которые будут понятны, интересны и полезны для целевой аудитории. Копирайтер также отвечает за стиль, тон и грамматику документов.

# План документации для проекта сайта для театра

## Цель документации
Целью документации является предоставление полной, точной и понятной информации о проекте сайта для театра для всех заинтересованных сторон: заказчика, разработчиков, тестировщиков, администраторов, пользователей.

## Виды документации
Для проекта сайта для театра будут созданы следующие виды документации:

- Техническое задание - документ, в котором описываются требования к функциональности, дизайну, технологиям и срокам проекта. Техническое задание будет составлено на основе цели и видения проекта, бизнес-контекста и материалов, предоставленных заказчиком. Техническое задание будет утверждено заказчиком и является основой для разработки и тестирования проекта.
- Архитектурная документация - документ, в котором описывается структура и взаимодействие компонентов системы, используемые технологии и инструменты, принципы и паттерны проектирования. Архитектурная документация будет составлена на основе технического задания и будет содержать диаграммы, схемы, описания и комментарии к коду. Архитектурная документация будет использоваться для понимания и развития системы разработчиками и тестировщиками.
- API документация - документ, в котором описываются интерфейсы для взаимодействия между backend и frontend частями системы, а также с внешними сервисами. API документация будет составлена на основе архитектурной документации и будет содержать спецификации, примеры запросов и ответов, ошибки и коды состояния. API документация будет использоваться для интеграции и тестирования системы разработчиками и тестировщиками.
- Пользовательская документация - документ, в котором описываются функции и возможности сайта для театра для конечных пользователей. Пользовательская документация будет составлена на основе технического задания и будет содержать инструкции, подсказки, скриншоты и видео. Пользовательская документация будет использоваться для обучения и поддержки пользователей сайта.

## Форматы и инструменты
Для создания документации будут использованы следующие форматы и инструменты:

- Техническое задание - формат PDF, инструмент Microsoft Word или Google Docs.
- Архитектурная документация - формат HTML или Markdown, инструмент Doxygen или MkDocs.
- API документация - формат JSON или YAML, инструмент Swagger или Postman.
- Пользовательская документация - формат HTML или Markdown, инструмент Read the Docs или Docusaurus.

## План работы
Для создания документации будут выполнены следующие шаги:

1. Сбор и анализ информации о проекте от заказчика и разработчиков.
2. Написание технического задания с учетом требований заказчика и возможностей разработки.
3. Согласование технического задания с заказчиком и разработчиками.
4. Написание архитектурной документации с учетом технического задания и выбранных технологий.
5. Написание API документации с учетом архитектурной документации и спецификаций интерфейсов.
6. Написание пользовательской документации с учетом технического задания и функциональности сайта.
7. Редактирование и проверка документации на соответствие стандартам, требованиям и реальности.
8. Публикация и обновление документации в соответствующих форматах и инструментах.
9. Получение обратной связи от заказчика, разработчиков и пользователей по документации и внесение необходимых исправлений.
