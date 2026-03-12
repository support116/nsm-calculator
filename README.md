# Solid Water — NSM Calculator

Файлы для деплоя на Vercel как отдельный сайт.

## Структура
```
index.html      ← калькулятор (главная страница)
api/claude.js   ← прокси к Anthropic API
vercel.json     ← настройки Vercel
```

## Деплой

1. Загрузи все 3 файла на GitHub (новый репозиторий)
2. Зайди на vercel.com → Add New Project → выбери репозиторий → Deploy
3. В Settings → Environment Variables добавь:
   - Name:  ANTHROPIC_API_KEY
   - Value: sk-ant-api03-...твой ключ...
4. Redeploy

Готово! Сайт будет на: https://ИМЯ-ПРОЕКТА.vercel.app
