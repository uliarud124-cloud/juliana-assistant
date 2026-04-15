---
name: Telegram MCP Setup
description: Статус настройки telegram-mcp интеграции для Claude Code
type: project
---

Telegram MCP сервер полностью настроен и готов к работе.

**Why:** Пользователь хотел подключить Telegram к Claude Code через MCP сервер chigwell/telegram-mcp.

**How to apply:** При вопросах о Telegram интеграции — всё уже настроено, нужен только перезапуск Claude Code.

## Что сделано

- Репозиторий клонирован: `C:/Users/а356/AppData/Local/Temp/telegram-mcp`
- Python-зависимости установлены через pip (telethon, mcp, qrcode, pillow)
- `uv` установлен: `C:/Users/а356/.local/bin/uv.exe`
- Зависимости uv синхронизированы с `UV_CACHE_DIR=C:/Juliana/.uv_cache`
- Авторизация Telegram пройдена через QR-код (аккаунт +79787178384)
- Session string и `.env` сохранены в `C:/Users/а356/AppData/Local/Temp/telegram-mcp/.env`
- MCP сервер зарегистрирован в `C:/Users/а356/.claude/mcp.json`

## Каналы Юлии в Telegram

- **Основной канал (экспертиза):** «Мастерская Юлии | Чат-Боты»
  - ID: 2351365716, username: @Provodnic_freelans
  - 675 подписчиков, контент: чат-боты, кейсы, экспертиза, личные истории
  - Рубрики: «Не тяжёлый понедельник» (лайф) + «Промты субботы» (AI-промты)
  - Стиль: тёплый, ироничный, личный, использует «💙» как маркеры списков

- **Второй канал (дизайн/таргет):** @yuli_udalenka
  - ID: 2425282481, 851 подписчик
  - Аудитория: кураторы онлайн-школ
  - Контент: визуал VK, дизайн, таргет — НЕ чат-боты

- **Канал с кейсами:** @design_yuliya_slyus

## Файлы

- `C:/Juliana/tg_qr_auth.py` — скрипт для повторной авторизации (если сессия истечёт)
- `C:/Juliana/.env` — копия env с session string
- `C:/Users/а356/.claude/mcp.json` — конфиг MCP сервера
