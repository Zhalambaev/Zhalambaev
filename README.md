# Denis Zhalambaev

### Python Backend Developer

Python-разработчик с фокусом на backend-разработке, API, автоматизации бизнес-процессов и интеграции AI/LLM-сервисов.

Работаю с Django, DRF, FastAPI, PostgreSQL, Celery, Redis и Docker. Есть опыт самостоятельной разработки сервисов от проектирования моделей данных и бизнес-логики до интеграции внешних API, тестирования и развёртывания на Linux-серверах.

Также работаю с прикладными LLM/RAG-решениями: embeddings, vector search, ChromaDB, LangChain, GigaChat API.

## Tech Stack

**Backend:**  
Python, Django, Django REST Framework, FastAPI

**Databases:**  
PostgreSQL, SQL, SQLAlchemy, Alembic

**Async & Background Tasks:**  
asyncio, Celery, Redis, Aiogram

**Testing:**  
Pytest

**Infrastructure:**  
Docker, Docker Compose, Linux, Nginx, Gunicorn, Git

**AI / LLM:**  
RAG, LangChain, ChromaDB, embeddings, GigaChat API

## Public Projects

### [Content API](https://github.com/Zhalambaev/content_api_drf)

REST API на Django REST Framework для работы со страницами и различными типами контента.

Реализованы:
- Django REST Framework
- пагинация API
- связанные модели данных
- оптимизация запросов через `prefetch_related`
- фоновые задачи Celery
- атомарное обновление счётчиков через Django `F()`
- автотесты API

**Stack:** Python, Django, DRF, Celery, Redis, Pytest

### [Document Processing](https://github.com/Zhalambaev/test_ds_bank)

Сервис обработки финансовых документов: извлечение данных, классификация документов и проверка назначения платежей.

Проект разделён на отдельные модули для извлечения данных, классификации и бизнес-проверок.

**Stack:** Python, pandas, RapidFuzz, Pytest

## Other Experience

Разрабатывал коммерческие и внутренние проекты, исходный код которых не находится в открытом доступе:

- сервис онлайн-записи клиентов на Django / DRF с Telegram-ботом, расписанием, временными слотами и напоминаниями через Celery / Redis;
- AI-ассистент с RAG-архитектурой, семантическим поиском по базе документов, embeddings и PostgreSQL;
- backend-интеграции с внешними REST API;
- сервисы интернет-платежей;
- внутренние системы автоматизации.

## Contacts

- Telegram: [@zhalambaevdenis](https://t.me/zhalambaevdenis)
- Email: zhalambaevdenis@yandex.ru
- Location: Novosibirsk, Russia
