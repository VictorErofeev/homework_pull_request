# Инструкция по работе с контролем версий

## Начало работы с депозиторием

* git init - создаёт локальный депозиторий

* git confing --global user.name "name" - задать имя в глобальной версии

* git confing --global user.email "email" - задать эл.почту глобальной версии

## Добавление файлов в репозиторий

* git add file_name -  добавили файл в депозиторий и сохраняет его

* git commit -m "сообщение" - прикрепляет сообщение о проделаной работе

## Отслеживание состояния репозитория

* git status - показывает статус

* git log - показывает журнал всех сохранений

* git diff - показывает разницу между текущей версией и зафиксированной

* для визулиазции веток добавляйте git log --help


## Переход между коммитами

* git checkout commit_code - команда для перехода в версии, необходимо ввести начала нужного коммита "_code". Для выбора коммита команда git log

* git checkout master - вернуться к актуальному состоянию, ветке "мастер"

![error](bet.jpg)

## Создание ветки

* git branch master_info - Создали ветку master_info

* git checkout master_info - переключились на ветку master_info

## Удаление веток

* git branch -d имя_ветки - удаление ветки

* git branch -D имя_ветки - удаление ветки игнорируя все ошибки

## Слияние веток и решение конфликтов
* git merge name_vetki - команда выкачивания и слияния информации в текущую ветку

## Справка

* что бы вызвать справку по какой либо команде, нужно вызвать тег --help

## Работа с удаленным депозиторием

* clone "адрес из github" - клонирует данные из удаленного репозитория на локальный

* pull - вытягивает актуальную версию из удаленного репозитория в локальный

* push - передаёт актуальную версию с локального в удаленный репозиторий

* Pull request — предложение изменения кода в чужом репозитории

* 
