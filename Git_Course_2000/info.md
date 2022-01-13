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
> git commit -m "some message"

Фиксирует все файлы, которые былт добавлены для отслеживания