# 📰 NewsBot — Telegram бот для автоматической публикации новостей

NewsBot — это Telegram-бот, который автоматически парсит новости с RSS/HTML сайтов и публикует их в Telegram-канал.  
Дополнительно бот умеет генерировать краткие аннотации новостей с помощью OpenAI API.

---

## 🚀 Возможности
- Парсинг RSS или HTML страниц (через `feedparser` и `BeautifulSoup`).
- Автоматическая публикация новостей в Telegram-канал каждые N минут.
- Генерация кратких описаний (аннотаций) через OpenAI API.
- Поддержка картинок, заголовков и кнопки «Читать подробнее».
- Фильтрация повторяющихся новостей (SQLite база).
- Ручная команда `/latest` для мгновенного постинга.

---

## 🛠 Используемые технологии
- **Python 3.11+**
- [python-telegram-bot](https://docs.python-telegram-bot.org/)
- [feedparser](https://pypi.org/project/feedparser/)
- [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/)
- [OpenAI Python SDK](https://github.com/openai/openai-python)
- SQLite (для хранения истории новостей)

---

## 📦 Установка и запуск

1. Клонируем репозиторий:
   ```bash
   git clone https://github.com/username/newsbot.git
   cd newsbot
