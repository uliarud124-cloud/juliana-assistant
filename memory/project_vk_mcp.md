---
name: VK MCP Setup
description: VK MCP настроен для работы с сообществом Юлия ЧАТ-БОТЫ (id226767399)
type: project
---

VK MCP сервер работает с сообществом "Юлия ЧАТ-БОТЫ" (id226767399), НЕ с личной страницей.

**Why:** Пользователь хочет управлять своим сообществом через Claude — публиковать посты, читать комментарии, смотреть статистику.

**How to apply:** Все VK-инструменты работают с GROUP_ID=-226767399. Остальные группы где Юлия админ — чужие.

## Данные

- VK токен: сохранён в `C:/Juliana/vk.env`
- GROUP_ID: -226767399 (Юлия ЧАТ-БОТЫ)
- MCP сервер: `C:/Juliana/vk-mcp/main.py`
- Зарегистрирован в `C:/Juliana/.mcp.json`

## Доступные инструменты (сообщество)

- `get_wall_posts` — посты сообщества с просмотрами/лайками
- `publish_post(text)` — опубликовать пост от имени сообщества
- `edit_post(post_id, text)` — редактировать пост
- `delete_post(post_id)` — удалить пост
- `pin_post(post_id)` — закрепить пост
- `unpin_post()` — открепить пост
- `get_group_stats` — статистика сообщества
- `get_post_stats(post_id)` — статистика конкретного поста
- `get_comments(post_id)` — комментарии к посту
- `reply_to_comment` — ответить от имени сообщества
- `add_comment` — добавить комментарий от сообщества
- `get_community_messages` — входящие сообщения
- `send_message_from_group` — написать пользователю от имени сообщества
- `get_members` — участники сообщества
- `search_members` — поиск участника

## Если токен истечёт

Открыть в браузере:
`https://oauth.vk.com/authorize?client_id=2685278&scope=groups,wall,messages,photos,stats,offline&redirect_uri=https://oauth.vk.com/blank.html&display=page&response_type=token&v=5.131`
