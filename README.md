Проект ToDo

Для запуска проекта локально и через Docker введите в терминале следующие команды

docker volume create todo_data  # создание контейнера
docker build -t todo-sqlite:latest .  # создание образа
docker run -d -p 8000:80 -v todo_data:/app/data todo-sqlite:latest  # запуск контейнера

Затем откройте сайт lokalhost:8000/docs - откроется FastAPI

Проект URL-Sortener

Для запуска проекта локально и через Docker введите в терминале следующие команды

docker volume create todo_data  # создание контейнера
docker build -t todo-sqlite:latest .  # создание образа
docker run -d -p 8000:80 -v todo_data:/app/data todo-sqlite:latest  # запуск контейнера

Затем откройте сайт lokalhost:8001/docs - откроется FastAPI