### Привет, я Роман 👋

Python backend-разработчик с фокусом на AI/LLM, 2 года коммерческого опыта. Довожу LLM-решения до production: AI-агенты с tool calling и MCP, RAG-индексация документов, streaming-чаты через SSE, голосовые боты в реальном времени. Работаю с self-hosted моделями (vLLM, Qwen) и российскими AI-сервисами (GigaChat, SaluteSpeech), поэтому умею строить AI-системы для закрытого контура.

Backend-база: FastAPI, asyncio, SQLAlchemy, PostgreSQL, Redis Streams, Celery/Taskiq, gRPC, Docker, GitLab CI. Надёжные асинхронные процессы (Transactional Outbox), интеграции с платёжными системами и OAuth/SSO.

📫 [Telegram](https://t.me/mellettan)

### Стек

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Celery](https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/gitlab%20CI-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black)

**AI/LLM:** LLM-агенты, function calling, MCP, RAG, LangChain, vLLM, GigaChat, SaluteSpeech, OpenAI API

### Проекты

| Проект | О чём | Стек |
|---|---|---|
| [**voicebot**](https://github.com/mellettan/sber_sst_ai_tts) | Голосовой ассистент в реальном времени: потоковое распознавание, ответ LLM озвучивается по предложениям, память диалога | FastAPI WebSocket, grpc.aio, SaluteSpeech, GigaChat, Redis |
| [**web-agent**](https://github.com/mellettan/ai_agent) | AI-агент, который выполняет задачи в браузере, и MCP-сервер с инструментами браузера; работает с OpenAI и self-hosted моделями через vLLM | Playwright, function calling, MCP |
| [**incident-api**](https://github.com/mellettan/incident_api) | Сервис учёта инцидентов: машина состояний, блокировки строк, миграции, тесты на PostgreSQL | FastAPI, SQLAlchemy 2.0 async, Alembic, mypy strict |
| [**github-top**](https://github.com/mellettan/ecomet_tasks) | Асинхронный сбор топа GitHub с лимитами RPS/конкурентности и батчевой загрузкой в ClickHouse | aiohttp, ClickHouse, asyncpg |
| [**url-shortener**](https://github.com/mellettan/boto_tasks) | Короткие ссылки с алиасами, сроком жизни, кэшем редиректов и rate limit | FastAPI, PostgreSQL, Redis |
| [**dbsync**](https://github.com/mellettan/test_18022026) | CLI для синхронизации схемы и данных между базами PostgreSQL, с dry-run и режимом для CI | psycopg 3, rich |
| [**sky**](https://github.com/mellettan/sky) | Звёздное небо в терминале: эфемериды, кометы, спутники, затмения, живые обои | numpy, sgp4 |
