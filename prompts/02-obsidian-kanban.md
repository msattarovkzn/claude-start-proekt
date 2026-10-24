# Промпт: доска задач карточками в Obsidian (плагин Kanban)

Перед промптом: Obsidian установлен, папка `D:\МойБизнес` хотя бы раз открыта в нём как хранилище, и **Obsidian закрыт**.

Вставьте в окно Claude (вкладка Code, папка `D:\МойБизнес`) и отправьте.

```text
Поставь в мою базу плагин Kanban для Obsidian, чтобы Tasks Board.md показывался доской с карточками.

1. Проверь, что в текущей папке есть папка .obsidian. Нет — остановись и скажи мне: значит, папку ещё не открывали в Obsidian как хранилище.
2. Создай папку .obsidian\plugins\obsidian-kanban.
3. Скачай в неё три файла последней версии плагина:
   https://github.com/mgmeyers/obsidian-kanban/releases/latest/download/manifest.json
   https://github.com/mgmeyers/obsidian-kanban/releases/latest/download/main.js
   https://github.com/mgmeyers/obsidian-kanban/releases/latest/download/styles.css
4. В файл .obsidian\community-plugins.json добавь "obsidian-kanban" в список. Нет файла — создай со списком ["obsidian-kanban"]. Другие плагины в списке не трогай.
5. Покажи, что лежит в .obsidian\plugins\obsidian-kanban, и содержимое community-plugins.json.

Перед тем как запускать команды, коротко скажи, что сделаешь.
```

## Что дальше

Откройте Obsidian. Он спросит, доверяете ли вы плагинам этого хранилища, — выберите вариант, который **доверяет автору и включает плагины**. Откройте `Tasks Board` — он покажется колонками с карточками.

Не спросил и доска не появилась: Настройки (шестерёнка внизу слева) → «Сторонние плагины» → выключите «Ограниченный режим» → в списке установленных включите Kanban.
