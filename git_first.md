# Инструкция по использованию GIT

## Установка

* git
* Visual Studio Code

## Проверка работы

Запустить терминал, выполнить команду:
git --version

В случае ошибок, в большинстве случаев, связи устанавливаются автоматически, после перезагрузки программы.

## Использование команд

1) git init -- Инициализация папки
2) git status -- Проверка состояния отслеживания
3) git add <file> -- Создаем элемент и добавляем его отслеживание
4) git commit -m “New file” -- Добавляем комментарий
5) git log –- Просмотр сохраненных состояний

6) git checkout <hash> - переход в версию
7) git checkout master – возврат к актуальной версии
8) git diff – показывает внесенные изменения

## Ветвление версий


1) git branch - cписок веток
2) git branch <Имя_ветки> - создание новой ветки
3) git merge <Имя_ветки> - cлияние ветки
4) git branch -d <Имя_ветки> - удаление ветки
5) git log --graph - представление с псевдографикой

## Клавиатурные сочетания

1) "q" -- Выход из просмотра
2) "Ctrl"+"S" -- Сохранение текущего файла проекта