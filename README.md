# ContactManagerCLI

## Описание
**ContactManagerCLI** — это консольное приложение на языке Java для управления контактами. Приложение позволяет пользователю создавать, просматривать, обновлять и искать контакты через удобный интерфейс меню.

## Функционал
- **Добавление контактов:** возможность добавить новый контакт с именем и номером телефона.
- **Просмотр всех контактов:** отображение списка всех сохраненных контактов.
- **Обновление контактов:** изменение информации о существующем контакте.
- **Поиск контактов:** поиск контактов по имени.
- **Выход из программы:** завершение работы приложения.

## Технологии
- **Язык программирования:** Java
- **Структура данных:** Map для хранения контактов
- **Принципы:** Объектно-ориентированное программирование (ООП)

## Структура проекта
- `Contact` — класс, описывающий сущность контакта с полями:
    - `name` — имя контакта.
    - `phoneNumber` — номер телефона.
- `Main` — класс, содержащий точку входа `main()` и методы для работы с пользователем:
    - Добавление нового контакта.
    - Просмотр всех контактов.
    - Обновление информации о контакте.
    - Поиск контактов по имени.

Контакты хранятся в коллекции `Map<String, Contact>`, где ключом является имя, а значением — объект контакта.

## Пример работы программы
При запуске программы отображается меню:

```
1. Добавить новый контакт
2. Просмотреть все контакты
3. Обновить контактную информацию
4. Поиск контакта
0. Закрыть приложение
```

Пользователь вводит номер пункта меню, после чего выполняется соответствующая операция.

## Как запустить
1. Склонируйте репозиторий:
   ```
   git clone https://github.com/aligarkh7/ContactManagerCLI
   ```
2. Перейдите в папку проекта:
   ```
   cd ContactManagerCLI
   ```
3. Скомпилируйте и запустите проект:
   ```
   javac Main.java
   java Main
   ```

## Возможности для улучшения
- Добавить сохранение и загрузку контактов из файла.
- Реализовать удаление контактов.
- Добавить обработку ошибок и валидацию данных.
- Разработать графический интерфейс пользователя (GUI).

## Автор
Ваше имя (Mukhametali Jetikov)  
[Ваш профиль GitHub](https://github.com/aligarkh7)