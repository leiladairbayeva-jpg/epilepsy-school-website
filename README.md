# Школа Эпилептологии — Д-р Лейла Даирбаева

**Официальный сайт:** [epilepsyschool.kz](https://leiladairbayeva-jpg.github.io)

## 📁 Структура проекта

| Файл | Описание |
|------|----------|
| `index.html` | Главный лендинг — Школа Эпилептологии |
| `crm-dashboard.html` | CRM-панель для управления заявками |
| `README.md` | Описание проекта |

## 🚀 Воркшоп

**Тема:** Эпилептология для врачей — базовый уровень (ILAE Level 1)  
**Дата:** 29–31 мая 2026  
**Место:** Уральск, Казахстан  
**Стоимость:** 30 000 ₸  

## ⚙️ Настройка перед запуском

### 1. Telegram-бот (уведомления о заявках)
В `index.html` найдите и замените:
```js
var TG_BOT_TOKEN = 'YOUR_BOT_TOKEN'; // от @BotFather
var TG_CHAT_ID   = 'YOUR_CHAT_ID';  // от @userinfobot
```

### 2. GitHub Pages (хостинг)
1. Settings → Pages → Source: `main` / `root`
2. Сайт будет доступен по адресу: `https://leiladairbayeva-jpg.github.io`

### 3. Кастомный домен
1. Купите `epilepsyschool.kz` на [nic.kz](https://nic.kz)
2. Settings → Pages → Custom domain → введите домен
3. Создайте файл `CNAME` с содержимым: `epilepsyschool.kz`

## 🤖 AI-помощник
Чатбот использует `claude-sonnet-4` через Anthropic API.  
Для работы нужен API-ключ на стороне сервера (не в HTML).  
Рекомендуется подключить через [Cloudflare Workers](https://workers.cloudflare.com).

## 📊 CRM
Откройте `crm-dashboard.html` локально или разместите рядом с сайтом.  
Данные хранятся в `localStorage` браузера.

## 👩‍⚕️ Автор
**Д-р Лейла Даирбаева** — невролог-эпилептолог, член Комиссии по терапии ILAE  
30+ лет в неврологии · 25+ лет в эпилептологии и ЭЭГ
