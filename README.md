# Проект Киттиграм - это социальная сеть для любителей котиков.
Kittygram - проект (социальная сеть) для обмена фотографиями питомцев, в котором доступна регистрация. Можно добавить нового котика на сайт или изменить существующего, а также просмотреть записи других пользователей.

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

3. ### В корневой дирректории создайте файл .env и заполните его данными:
```
SECRET_KEY=your_secret_key
DEBUG=True
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=db
DB_PORT=5432
```

5. ### Установите зависимости:
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
