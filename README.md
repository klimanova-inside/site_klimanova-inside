# Эльвира — персональный коучинг · лендинг

Одностраничный лендинг для коуча Эльвиры. Статический сайт (HTML + CSS + немного JS), без сборки.

**Прод:** https://elvira-landing.vercel.app

## Структура
- `index.html` — вся страница (inline CSS/JS)
- `assets/` — фото коуча (`elvira.png` / `elvira.webp`), OG-картинка, иконки
- `favicon.svg`, `robots.txt`, `sitemap.xml`

## Локальный запуск
```bash
python3 -m http.server 4551
# открыть http://localhost:4551
```

## Деплой (Vercel)
```bash
npx vercel@latest deploy --prod --yes --scope <team>
```

## Осталось подставить
- Реальные контакты (Telegram/почта) вместо плейсхолдеров `t.me/username`
- Приёмник формы заявок (Telegram-бот / Formspree / CRM)
- Данные для блоков «Обо мне» и «Формат сессии», метод PWS, цена
