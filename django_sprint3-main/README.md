# Описание.

## Проект django_sprint3.

## Технологии:
* Python 3.7
* Django 3.2
* SQlite3
* JSON

## Описание проекта

Доработка проекта django_sprint1.
Небольшая социальная сеть для публикации личных дневников. Данные для БД находятся в файле db.json.
![image](https://github.com/RiSSoL-86/django_sprint3/assets/110422516/99f01781-dc7d-4715-9dc9-ada61b22ff0a)


## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке:

        git clone git@github.com:RiSSoL-86/django_sprint3.git
        cd django_sprint3

* Cоздать и активировать виртуальное окружение:

        python -m venv venv
        source venv/Scripts/activate

* Установить зависимости из файла requirements.txt:

        python -m pip install --upgrade pip
        pip install -r requirements.txt

* Выполнить миграции:

        python manage.py migrate

* Загрузить фикстуры:

        python manage.py loaddata db.json

* Запустить проект:

        python manage.py runserver

* Перейти на локальный сервер:

        http://127.0.0.1:8000/
