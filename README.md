# To-Do List telegram bot

## Описание

Телеграм бот для планирования задач. Имеет четыре команды:
1) /help - выводит список доступных команд
2) /add - добавляет новую задачу в список. Команду необходимо вводить в формате «/add - дата - задача»
3) /show - выводит все добавленные задачи на заданную дату. Команду необходимо вводить в формате «/show - дата»
4) /random - добавляет случайную задачу из заданного списка. Задача добавляется на сегодняшнее число

Дату нужно вводить в формате «день месяц год», можно использовать слова «сегодня» и «завтра». Доступные форматы даты:
1) 2 сентября 2022
2) 02 сентября 2022
3) 02.09.2022
4) 2.09.2022
5) 02/09/2022
6) 2/09/2022
7) 02:09:2022
8) 2:09:2022

## Установка

Зависимости, необходимые для работы, указаны в файле pyproject.toml.

## Использование

Для использования бота необходимы API:
1. telegram
