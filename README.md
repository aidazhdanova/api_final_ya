API для социальной сети
=====

Описание:
=====

API для социальной сети, в которой пользователи могут публиковать записи и просматривать сообщения других пользователей. Реализованы механизм комментариев к записям, возможность подписки на публикации интересующий авторов, регистрация пользователей. Для аутентификации используется JWT-токен. 

### Технологии

- Django
- Django Rest Framework
- JWT

Запустить проект можно следующим образом:
----------

1. Клонировать репозиторий и перейти в него:
```bash
git clone https://github.com/aidazhdanova/api_final_ya.git
cd api_final_yatube
```
2. Cоздать и активировать виртуальное окружение:
```bash
python -m venv venv
source venv/Scripts/activate
```
3. Установить зависимости ```requirements.txt```:
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
python manage.py migrate
```
5. Запустить проект:
```bash
python manage.py runserver
```
----------
Документация доступна по адресу ```/redoc/```.
