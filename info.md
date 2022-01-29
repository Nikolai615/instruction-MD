## Инструкция по работе с git

## Начало работы с репозиторием
> git init

* создает локальный репозиторий 

Если не было задано имя пользователя ранее, то:
> git config --global user.name "name"

> git config --global user.email "mail@mail.com"

## Добавление факйлов в репозиторий
> git add file_name 

Добалвяет файл file_name для отслеживания

> git commit -m "some message"

фиксирует все файлы, которые добавлены для отслеживания

## Отслеживание состояния репозитория
> git status

показывает измененные файлы и файлы готовые для отслеживания 
> git log

показывает все комиты
> git diff

показывает разницу между текущей версией и зафиксированной

## Переход между комитами
> git checkout commit_code

Переходит к комиту с кодом commit_code (его можно подсмотреть по git log)

> git checkout master 

Вернуться к актуальному состоянию
! [error] (pic.jpg)

## ветки в git
Чтобы посмотреть все ветки:
> git branch

Для создания ветки branch_name:
> git branch branch_name

Переместиться к ветке branch_name:
> git checkout branch_name

## Удаление веток 
Удалить ветку с именем branch_name можно командой:
> git branch -d branch_name

Для  удаления ветки игнорируя все ошибки:
> git branch -d branch_name