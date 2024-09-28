#  Сайт для публикации фотографий котов и их достижений

![example workflow](https://github.com/Vlad-the-God/kittygram_final/actions/workflows/main.yml/badge.svg)

## Стек

Python, Django, DRF, Docker, CI/CD, GitHub Actions

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Vlad-the-God/kittygram_final.git
```

```
cd kittygram_final
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Для запуска на сервере:

Клонировать в репозиторий файл docker-compose.production.yml

Запустить проект командой:

```
sudo docker compose -f docker-compose.production.yml up -d
```

## Пример заполненного файла .env

POSTGRES_USER=user
POSTGRES_PASSWORD=password
POSTGRES_DB=kittygram
DB_HOST=db
DB_PORT=5432
SECRET_KEY='django-insecure-cg6*%51d6ef8f#4!r3*$vmxm4)ajwbg8mo!4y-q*uq1!4$-98$'
ALLOWED_HOSTS='127.0.0.1, localhost'
DEBUG='True'

## Автор:

Волохов Владислав Алексеевич
https://github.com/Vlad-the-God
