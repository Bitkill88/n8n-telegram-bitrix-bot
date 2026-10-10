# Telegram → Bitrix24 AI Lead Qualification Bot

n8n workflow для автоматического сбора данных о клиентах через Telegram
и создания сделок в Bitrix24.

## Стек
- n8n
- PostgreSQL
- Telegram Bot API
- Bitrix24 REST API
- OpenRouter (LLM)

## Установка

1. Импортируйте `workflow.json` в ваш n8n
2. Настройте credentials:
   - Telegram Bot Token
   - PostgreSQL connection
   - Bitrix24 webhook URL
   - OpenRouter API key
3. Замените плейсхолдеры `YOUR_PORTAL`, `YOUR_WEBHOOK_CODE` в HTTP-нодах
4. Создайте таблицы в PostgreSQL:
