# Проект Киттиграм - это социальная сеть для любителей котиков.
Kittygram - социальная сеть, специально созданная для хозяев и просто любителей милых кошечек. Здесь делятся фотографиями питомцев. Это так же платформа для заведения новых друзей с общими кошачьими интересами.

## Использованные технологии:
- Python 3.9
- Django 3.2
- Django REST framework
- Djoser
- PostgreSQL
- Docker
- gunicorn
- nginx

## Локальный запуск проекта
1. ### Склонируйте репозиторий:
```
git clone https://github.com/romatimon/kittygram_final
```

2. ### Создайте и активируйте виртуальное окружение:
Команда для установки виртуального окружения на Mac или Linux:
```
python3 -m venv env
source env/bin/activate
```

Команда для установки виртуального окружения на Windows:
```
python -m venv venv
source venv/Scripts/activate
```

3. ### В корневой дирректории создайте файл .env по образцу .env.example.

4. ### Установите зависимости:
```
cd backend
pip install -r requirements.txt
```

5. ### Проведите миграции:
```
python manage.py migrate
```

6. ### При необходимости создайте суперпользователя:
```
python manage.py createsuperuser
```

7. ### Запустите локальный сервер:
```
python manage.py runserver
```
