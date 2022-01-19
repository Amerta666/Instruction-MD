![Файл не найден](git.png)
# Инструкция по работе с git

## Начало работы с репозиторием
> git init 
* создаёт локальный репозиторий

Если не было ранее задано имя и email то,
> git config --global user.name "name"

> git config --global user.email "email@mail.com"

## Добавление файлов в репозиторий
> git add file_name

Добавляет файл file_name для отслеживания
>git add .

Добавить все файлы, которые не отслеживаются

> git commit -m "some message"

Фиксирует все файлы, которые были добавлены для отслеживания с комментарием "some message".

> git commit -a -m "some message"

Фиксирует все файлы, которые были добавлены для отслеживания с комментарием "some message" и добавляет все файлы (-a), без использования "git add"

>git commit --amend

Редактировать название последнего коммита

>git commit --amend -m "commit name"

Редактировать название последнего коммита и сразу его переименовать (-m)

## Отслеживание состояния репозитория
> git status

показывает изменённые файлы и файлы готовые для комита

> git log

показывают все комиты

>git log --graph

показывают все комиты с визуализацией веток


>git diff

показывает разницу между текущей версией и зафиксированной

## Переход между коммитами

>git checkout commit_code

Переходит к комиту с кодом commite_code (можно подсмотреть по git log)

## Ветки и работа с ними

> git branch

Показывает все ветки и текущую.

>git branch branch_name

Создаём новую ветку branch_name

>git checkout branch_name

Переход на ветку branch_name
>git merge branch_name

Объединяем текущую ветку с веткой branch_name

>git brancn -d branch_name

удаляет ветку branch_name
("-d" - безопасное удаление, если ничего не повредит, "-D" - удаление в любом случае)

## Ветки в гит

>git branch

Посмотреть все ветки

>git branch branch_name

Создать новую ветку branch_name

>git checkout branch_name

Переместиться к ветке branch_name
