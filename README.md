# Flask Blog Project

## Описание
Этот проект представляет собой базовый блог, разработанный с использованием Flask.  
Он включает регистрацию пользователей, авторизацию, управление пользователями, а также базовые CRUD-операции для постов.

## Особенности
- Регистрация и авторизация пользователей.
- Хэширование паролей с использованием `werkzeug.security`.
- Работа с базой данных через `Flask-SQLAlchemy`.
- Структура проекта с разделением на модули.

## Установка
Установка проекта:
   ```bash
   git clone https://github.com/<username>/flask_blog_project.git
   cd flask_blog_project
   python3 -m venv venv
   source venv/bin/activate  # для Linux/Mac
   venv\Scripts\activate     # для Windows
   pip install -r requirements.txt
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade


