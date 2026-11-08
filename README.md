# ÉLÉRA Laser Studio

Односторінковий сайт студії лазерної епіляції. Чистий HTML/CSS/JS, без збірки й залежностей.

## Структура

```
index.html   — увесь сайт (розмітка, стилі, скрипти)
README.md
```

## Публікація на GitHub Pages

1. Створіть новий репозиторій на GitHub (наприклад, `elera-site`).
2. Завантажте файли з архіву: **Add file → Upload files** → перетягніть `index.html` і `README.md` → **Commit changes**.
3. Відкрийте **Settings → Pages**.
4. У **Source** оберіть **Deploy from a branch**, гілка `main`, папка `/ (root)` → **Save**.
5. За 1–2 хвилини сайт буде доступний за адресою `https://<ваш-логін>.github.io/elera-site/`.

Через термінал:

```bash
git init
git add .
git commit -m "ÉLÉRA landing"
git branch -M main
git remote add origin https://github.com/<ваш-логін>/elera-site.git
git push -u origin main
```

## Що замінити перед запуском

- Усе в квадратних дужках `[ ... ]`: ціни, адреса, телефон, імена, статистика, параметри апарата.
- Фото: знайдіть `--img:url('...')` і вставте посилання на своє фото (або покладіть файл поруч, напр. `img/hero.jpg`, і вкажіть `--img:url('img/hero.jpg')`).
- Фото команди — обов'язково на реальних спеціалістів.
- Відгуки — лише реальні, зі згоди клієнтів.
- Відправка форми: у кінці `index.html` знайдіть `TODO` і підключіть CRM / Telegram-бот / Formspree.

Фото-заглушки — з [Unsplash](https://unsplash.com) (безкоштовна ліцензія Unsplash).
