 # 🧑‍💻 Flask-проект: Sindilitik 

Это веб-приложение, разработанное с использованием Flask и множества полезных расширений. Проект поддерживает регистрацию и авторизацию пользователей, работу с базой данных через ORM, локализацию интерфейса, загрузку изображений, отображение временных меток и настроенное логирование.


 ## **🔧 Основные функции:**

* Регистрация и вход пользователей (Flask-Login )
* ORM для работы с данными (SQLAlchemy + Flask-SQLAlchemy )
* Миграции базы данных (Flask-Migrate )
* Формы и валидация (Flask-WTF )
* Локализация интерфейса (Flask-Babel )
* Отображение временных меток (Flask-Moment )
* Загрузка изображений (Flask-Uploads )
* Настроенное логирование (RotatingFileHandler )


 ## 📦 Технологии: 

* python 3.10.x
* больше информации найдёте в файле requirements.txt


---

 ## 🛠️ Установка и запуск

 1. Клонируйте репозиторий:
```bash
git clone https://github.com/Sindereve/Flask_project
cd Flask_project
```

 2. Создайте виртуальное окружение и установите зависимости:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

 3. Запустите приложение

В репозитории уже хранится тестовый вариант миграции. Поэтому можно пропустить пункт связанный с миграцией и перейти к запуску

```bash
flask run
```

 ## Изображения

Авторизация
![image](https://github.com/user-attachments/assets/6fe796aa-3ebf-455a-b436-d4cf13fbbbab)

Регистрация
![image](https://github.com/user-attachments/assets/1d0b3ff9-6971-4f9a-9657-3b7c1a074a90)

Домашняя страница(ваши посты и посты людей, на кого оформлена подписка)
![Home](https://github.com/user-attachments/assets/16ffe70c-0c0b-4dfa-8f2b-073e39b79c57)

Профиль пользователя
![My_profile](https://github.com/user-attachments/assets/398ea03a-7907-4a37-ab71-a61b7fc4f04b)

Посты всех пользователей 
![Explore](https://github.com/user-attachments/assets/b7c84d2e-937d-4b9d-a619-883458c6f7fb)

Пример с другой локализацией 
![Ru_profile](https://github.com/user-attachments/assets/fe33413a-ef74-46ef-9c45-091be032f287)
![De_profile](https://github.com/user-attachments/assets/a040701f-0a64-4ff3-9658-cadce9a38a9e)


