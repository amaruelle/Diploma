# Выступление

## Актуальность темы

Разрешите представить вам дипломный проект на тему "Разработка мобильного приложения 'Планировщик задач'". 
В настоящее время большинство приложений для проектной работы и ведения личных дел сталкиваются с рядом ограничений, 
таких как централизация системы, что означает полную зависимость пользователей от разработчика, частичная или полная 
закрытость системы, что делает невозможным внедрение новых функций и возможностей самостоятельно (персонализация), 
а также коммерциализация сервисов, что приводит к появлению или увеличению цен, введению платных подписок и услуг, 
и отвлекает пользователей от основной цели использования.

Эти проблемы можно решить, создав систему, которая акцентирует внимание на принципах децентрализованности и открытости, 
а также ставит в приоритет безопасность и неприкосновенность данных пользователей. 
Именно такой системой является проект Uptask. 

Он позволяет вести свои дела, не отвлекаясь на рекламу, не беспокоясь о качестве интернет-связи или о внезапном 
закрытии проекта, и не переживая о безопасности своих данных. 

Uptask полностью локален, все данные хранятся непосредственно на устройстве пользователя, 
а исходный код проекта полностью открыт и позволяет персонализировать систему под свои нужды.

Помимо этого, актуальной является и сама сфера планирования для любого пользователя - 
она пользуется большим спросом в современном мире, где время является самым ценным ресурсом, а информационный шум зашкаливает.

Планирование своей жизни и её структуризация решает проблемы рассеянности, забывчивости, 
помогает распределять приоритеты задач, проводить самоанализ и саморазвитие.

## Постановка задачи

Основной задачей дипломного проекта является разработка мобильного приложения планировщика задач 
с расширенным функционалом категоризации, сортировки, группировки задач.

Основные этапы включают проектирование и разработку архитектуры приложения, создание 
удобного пользовательского интерфейса, обеспечение безопасности данных и 
проведение тестирования для оценки качества работы приложения.

## Функции приложения

Приложение Uptask включает в себя следующие основные функции:

- Создание и управление задачами.
- Установка напоминаний для задач.
- Категоризация и сортировка задач.
- Поиск задач по ключевым словам.
- Возможность изменения данных профиля пользователя (логин и пароль).
- Очистка данных и удаление задач.
- Генерация аналитических отчетов по выполненным и невыполненным задачам.

Основные исходные данные включают в себя следующее.
1. Пользовательские данные:
  - Логин: Имя пользователя, используемое для входа в систему;
  - Пароль: Секретная комбинация символов для доступа к аккаунту.

2. Данные задач:
  - Название задачи: Краткое описание или заголовок задачи;
  - Описание задачи: Детальное описание того, что нужно выполнить;
  - Дата выполнения: Срок, к которому задача должна быть выполнена;
  - Приоритет: Важность задачи по сравнению с другими задачами;
  - Статус выполнения: указывает, выполнена задача или нет;
  - Напоминание (за сколько времени до срока напомнить).

3. Данные списков задач:
  - Название списка: Название, идентифицирующее список задач.
  - Эмодзи или иконка: Графический символ, ассоциирующийся со списком.
  - Задачи: Ссылки на задачи, включенные в список.

4. Данные для аналитики:
  - Дата начала периода: Начало временного промежутка для анализа.
  - Дата окончания периода: Конец временного промежутка для анализа.

Выходные данные это сами задачи, их отображение на экране, аналитическая информация.

## Среды программирования

Для разработки приложения были использованы следующие среды программирования:

- Язык программирования Kotlin.
- Фреймворк Jetpack Compose для создания пользовательского интерфейса.
- База данных H2 для локального хранения данных.
- Android SDK для разработки и тестирования на платформе Android.
- Android Studio как основная интегрированная среда разработки.

## Схема базы данных

Основные сущности созданной базы данных, а также связи между ними представлены на следующем рисунке:

[РИСУНОК]

## Структура приложения

## Интерфейс приложения

## Обеспечение защиты
