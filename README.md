# 🎓 Python Learning Path

> Коллекция проектов, выполненных в ходе обучения на курсе «Python-разработчик» Яндекс Практикума.

Здесь собраны учебные работы от базовых скриптов до полноценных REST API и Docker-контейнеров.

---

## 📚 Каталог проектов

### 🔰 Основы Python и ООП

| Проект | Что реализовано | Технологии |
|--------|----------------|------------|
| [`hw_python_oop`](./projects/hw_python_oop) | Домашние задания по ООП | Python, Classes, Inheritance |
| [`character_creation_module`](./projects/character_creation_module) | Модуль создания персонажей | Python, ООП, Атрибуты классов |

### 🤖 Telegram боты

| Проект | Что реализовано | Технологии |
|--------|----------------|------------|
| [`anfisa-bot`](./projects/anfisa-bot) | Бот-помощник для обучения | Python, Telegram Bot API, Requests |
| [`homework-bot`](./projects/homework-bot) | Бот для уведомлений о ДЗ | Python, Telegram API, Schedule |

### 🌐 Django разработка

| Проект | Что реализовано | Технологии |
|--------|----------------|------------|
| [`django-sprint1`](./projects/django-sprint1) | Базовые модели, админка | Django ORM, Admin Panel |
| [`django-sprint3`](./projects/django-sprint3) | Шаблоны, формы, пагинация | Django Templates, Forms |
| [`django-sprint4`](./projects/django-sprint4) | Работа с базами данных | Django, PostgreSQL, Queries |

### 🚀 REST API и Backend

| Проект | Что реализовано | Технологии |
|--------|----------------|------------|
| [`api_final_yatube`](./projects/api_final_yatube) | API для блога с постами и комментариями | Django REST Framework, JWT |
| [`django_testing`](./projects/django_testing) | Тестирование Django-приложений | Pytest, Django Test Client |

### 🛠 Инфраструктура и DevOps

| Проект | Что реализовано | Технологии |
|--------|----------------|------------|
| [`infra_sprint1`](./projects/infra_sprint1) | CI/CD, Docker, деплой | Docker, GitHub Actions, Nginx |
| [`taski-docker`](./projects/taski-docker) | Приложение для задач с Docker | Django, Docker, Docker Compose |

---

## 🚀 Как использовать

### Клонирование со всеми проектами

```bash
# Вариант 1: Клонировать сразу со всеми подмодулями
git clone --recurse-submodules https://github.com/Klikmok/python-learning-path.git

# Вариант 2: Если уже склонировал без подмодулей
git clone https://github.com/Klikmok/python-learning-path.git
cd python-learning-path
git submodule update --init --recursive
```

### Запуск любого проекта

```bash
# Перейди в папку проекта
cd projects/django-sprint1

# Создай виртуальное окружение
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Установи зависимости
pip install -r requirements.txt

# Запусти проект (индивидуально для каждого проекта)
python manage.py runserver
```

---

## 🎯 Ключевые проекты (вынесены отдельно)

Эти проекты демонстрируют продвинутые навыки и вынесены в отдельные репозитории:

| Проект | Описание |
|--------|----------|
| [`api_yamdb`](https://github.com/Klikmok/api_yamdb) | **Флагманский проект**: полноценный REST API с ролевой моделью, JWT-аутентификацией и документацией |
| [`kittygram_final`](https://github.com/Klikmok/kittygram_final) | Docker + CI/CD пайплайны + деплой на VPS |
| [`foodgram-project-react`](https://github.com/Klikmok/foodgram-project-react) | Fullstack проект с React-фронтендом и боевым деплоем |

---

## 📊 Прогресс обучения

- ✅ Основы Python и ООП
- ✅ Telegram боты
- ✅ Django ORM и админка
- ✅ Django Templates и Forms
- ✅ REST API (DRF)
- ✅ Тестирование (Pytest)
- ✅ Docker и CI/CD
- ✅ Деплой на VPS

---

## 🛠 Технологии в проектах

```
🐍 Python 3.9+
🎸 Django 3.2+
🔥 Django REST Framework
🐳 Docker & Docker Compose
🧪 Pytest
🔐 JWT Authentication
📮 Telegram Bot API
🔄 GitHub Actions (CI/CD)
🗄 PostgreSQL / SQLite
```

---

## 📬 Контакты

**Рыбаков Алексей**  
📧 [klikmok@yandex.ru](mailto:klikmok@yandex.ru)  
🔗 [GitHub](https://github.com/Klikmok)

> 💡 **Примечание**: Каждый проект — это отдельный Git-репозиторий, подключённый как сабмодуль.  
> Для просмотра полной истории коммитов перейдите в соответствующий репозиторий по ссылке.
