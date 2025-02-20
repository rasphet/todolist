Простое приложение для управления списком задач (ToDo List) на Android. Позволяет добавлять задачи, отмечать их как выполненные (с зачеркиванием текста) и удалять задачи через контекстное меню.
Основные функции
- **Добавление задач**: Пользователь может ввести текст задачи и добавить её в список.
- **Зачеркивание задач**: При нажатии на `CheckBox` задача отмечается как выполненная, и её текст зачеркивается.
- **Удаление задач**: При долгом нажатии на задачу появляется контекстное меню с опцией удаления.
- **Простой интерфейс**: Минималистичный и удобный интерфейс для быстрого управления задачами.

  Технологии
- **Язык программирования**: Kotlin
- **Используемые компоненты**:
  - `ListView` для отображения списка задач.
  - `CheckBox` для отметки выполнения задач.
  - Контекстное меню для удаления задач.

MainActivity.kt: Основная активность, управляющая логикой приложения.
TaskAdapter.kt: Адаптер для отображения задач в ListView.
item_task.xml: Макет для отображения одной задачи (текст и CheckBox).
activity_main.xml: Главный макет приложения.
context_menu.xml: Меню для удаления задач.
