# DRF Project

Добро пожаловать в проект на Django REST Framework! Этот репозиторий содержит backend-приложение, написанное с использованием Django и DRF для создания REST API.

## 🚀 Быстрый старт

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-username/your-drf-project.git
   cd your-drf-project
   ```

2. Создайте и активируйте виртуальное окружение:
   ```bash
   python -m venv env
   source env/bin/activate  # Для Windows: env\Scripts\activate
   ```

3. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

4. Создайте файл `.env` в корне проекта и добавьте в него переменные окружения, например:
   ```
   DEBUG=True
   SECRET_KEY=your-secret-key
   ALLOWED_HOSTS=127.0.0.1,localhost
   DATABASE_URL=sqlite:///db.sqlite3
   ```

   > ⚠️ Убедитесь, что файл `.env` добавлен в `.gitignore`, чтобы не попасть в публичный репозиторий.

5. Примените миграции:
   ```bash
   python manage.py migrate
   ```

6. Запустите сервер:
   ```bash
   python manage.py runserver
   ```

## 🌿 Основы Git

- `git clone <url>` — клонировать удалённый репозиторий
- `git status` — посмотреть текущее состояние репозитория
- `git add <файл>` — добавить файл в индекс
- `git commit -m "Комментарий"` — зафиксировать изменения
- `git push` — отправить изменения в удалённый репозиторий
- `git pull` — получить последние изменения с удалённого репозитория
- `git checkout <ветка>` — переключиться на другую ветку
- `git branch <имя>` — создать новую ветку

## 📂 Структура проекта

```
your-drf-project/
├── your_app/
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── urls.py
├── manage.py
├── requirements.txt
├── .env.example
├── README.md
```

## 💻 Базовые команды терминала

- `ls` — список файлов и папок в текущей директории
- `cd <путь>` — переход в другую директорию
- `pwd` — путь к текущей директории
- `mkdir <имя>` — создать новую папку
- `rm <файл>` — удалить файл
- `rm -r <папка>` — удалить папку и её содержимое
- `touch <имя_файла>` — создать новый пустой файл
- `clear` — очистить терминал

## ⌨️ Полезные горячие клавиши

- `Ctrl + C` — прервать выполнение текущей команды
- `Ctrl + D` — выйти из текущей сессии (например, Python shell)
- `Ctrl + L` — очистить терминал
- `Tab` — автодополнение имени файла или команды
- `↑ / ↓` — прокрутка по истории команд