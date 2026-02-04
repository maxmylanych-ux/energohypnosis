[README.md](https://github.com/user-attachments/files/25077868/README.md)
# 🌟 Світлоносці - Енергоінформаційний гіпноз

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsvetonoscy.online)](https://svetonoscy.online)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)

Професійний сайт для практиків енергоінформаційного гіпнозу. Повністю адаптивний, двомовний (UA/RU), з інтеграцією EmailJS та Plausible Analytics.

🌐 **Live Demo:** [svetonoscy.online](https://svetonoscy.online)

---

## ✨ Особливості

- 🌍 **Двомовний інтерфейс** (Українська/Російська)
- 🎨 **Сучасний дизайн** з плавними анімаціями
- 📱 **Повністю адаптивний** (Mobile-first)
- 🍪 **GDPR-сумісний** Cookie Banner
- 📧 **Контактна форма** через EmailJS
- 📊 **Privacy-friendly аналітика** (Plausible)
- ⚡ **Швидкий** (< 2s завантаження)
- ♿ **Доступний** (WCAG 2.1 AA)
- 🔒 **Безпечний** (SSL, CSP headers)

---

## 🚀 Швидкий старт

### 1. Клонувати репозиторій
```bash
git clone https://github.com/username/svetonoscy.git
cd svetonoscy
```

### 2. Налаштувати EmailJS

1. Зареєструватись на [emailjs.com](https://www.emailjs.com/)
2. Створити Email Service
3. Створити Email Template
4. Вставити ключі в `index.html`:

```javascript
emailjs.init('YOUR_PUBLIC_KEY');
const serviceID = 'YOUR_SERVICE_ID';
const templateID = 'YOUR_TEMPLATE_ID';
```

### 3. Додати зображення

Помістити в папку `images/`:
- `maxim.jpg` (250x400px)
- `alla.jpg` (250x400px)
- `og-cosmic-light-v2.jpg` (1200x630px)
- `favicon.svg` або `favicon.png`

### 4. Запустити локально

Просто відкрити `index.html` у браузері або використати локальний сервер:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve

# VS Code
# Live Server extension
```

### 5. Deploy

**Netlify (рекомендовано):**
```bash
# Drag & drop на netlify.com
# або
netlify deploy --prod
```

**GitHub Pages:**
```bash
# Settings → Pages → Deploy from main
```

---

## 📂 Структура проекту

```
svetonoscy.online/
├── index.html              # Головний файл (HTML + CSS + JS)
├── images/                 # Зображення
│   ├── favicon.svg
│   ├── favicon.png
│   ├── og-cosmic-light-v2.jpg
│   ├── maxim.jpg
│   └── alla.jpg
├── DOCUMENTATION.md        # Повна документація
├── QUICK-START.md         # Швидкий старт
├── TECHNICAL-SPEC.md      # Технічна специфікація
└── README.md              # Цей файл
```

---

## 🛠️ Технології

### Frontend
- **HTML5** - семантична розмітка
- **CSS3** - Grid, Flexbox, CSS Variables
- **JavaScript (ES6+)** - без фреймворків

### Залежності
- [Google Fonts](https://fonts.google.com/) - Cormorant, Montserrat
- [Font Awesome 6](https://fontawesome.com/) - іконки
- [EmailJS](https://www.emailjs.com/) - форма зв'язку
- [Plausible](https://plausible.io/) - аналітика
- [ipapi.co](https://ipapi.co/) - геолокація

---

## 📖 Документація

- 📚 [**Повна документація**](DOCUMENTATION.md) - детальний опис всіх функцій
- 🚀 [**Quick Start Guide**](QUICK-START.md) - швидкий старт за 5 хвилин
- 🔧 [**Технічна специфікація**](TECHNICAL-SPEC.md) - архітектура та API

---

## 🎨 Кастомізація

### Зміна кольорів

Відредагуйте CSS змінні в `index.html`:

```css
:root {
    --bg-main: #F4EFE7;       /* Основний фон */
    --bg-sections: #E6DDC8;   /* Фон секцій */
    --accent: #4E6B4A;        /* Акцентний колір */
    --text-main: #2F3E34;     /* Основний текст */
    --text-light: #FAF9F6;    /* Світлий текст */
    --decorative: #C9B37E;    /* Декоративний */
}
```

### Додавання контенту

**Новий відгук:**
1. Додати HTML в секцію `#reviews`
2. Додати переклади в `translations.uk` та `translations.ru`

**Нове FAQ:**
1. Додати `.faq-item` в секцію `#faq`
2. Додати переклади питання та відповіді

---

## 🧪 Тестування

```bash
# Локальне тестування
# 1. Перемкнути мову (UA ↔ RU)
# 2. Відправити тестову форму
# 3. Перевірити cookie banner
# 4. Тест на мобільному
```

**Автоматичні тести:**
- [PageSpeed Insights](https://pagespeed.web.dev/)
- [WAVE Accessibility](https://wave.webaim.org/)
- [GTmetrix](https://gtmetrix.com/)

---

## 📊 Metrics

| Метрика | Значення |
|---------|----------|
| Performance Score | 95+ |
| Accessibility Score | 95+ |
| Best Practices | 100 |
| SEO Score | 100 |
| Page Load Time | < 2s |
| Mobile Friendly | ✅ |

---

## 🔒 Безпека

- ✅ HTTPS (обов'язково)
- ✅ CSP Headers (рекомендовано)
- ✅ XSS Protection
- ✅ GDPR Compliance
- ✅ Privacy-focused Analytics

---

## 🤝 Внесок

Це приватний проект. Якщо ви знайшли баг або маєте пропозицію:

1. Відкрийте Issue
2. Опишіть проблему/ідею
3. Додайте скріншоти (якщо є)

---

## 📄 Ліцензія

© 2026 Світлоносці. Всі права захищені.

**Код:** Proprietary (не для комерційного використання без дозволу)  
**Контент:** Copyright Світлоносці

---

## 👥 Автори

**Максим** - Оператор · Контактер  
**Алла** - Контактер · Оператор

---

## 📞 Контакти

- 📧 Email: svet0noscy@gmail.com
- 🌐 Website: [svetonoscy.online](https://svetonoscy.online)
- 📱 Instagram: [Your Handle]
- 📺 YouTube: [Your Channel]
- 💬 Telegram: [Your Channel]

---

## 🙏 Подяки

- [Google Fonts](https://fonts.google.com/) - шрифти
- [Font Awesome](https://fontawesome.com/) - іконки
- [EmailJS](https://www.emailjs.com/) - email сервіс
- [Plausible](https://plausible.io/) - аналітика
- [ipapi.co](https://ipapi.co/) - геолокація
- Всім клієнтам за відгуки 💚

---

## 🗺️ Roadmap

- [ ] Англійська версія
- [ ] Онлайн-бронювання
- [ ] Блог з статтями
- [ ] Темна тема
- [ ] PWA версія
- [ ] Особистий кабінет

---

## 📝 Changelog

### Version 2.0 (Лютий 2026)
- ✨ Додано FAQ акордеон
- ✨ Покращена секція "Про нас"
- ✨ Іконки замість тексту в cookie banner
- 🐛 Виправлено переклади відгуків
- 🐛 Виправлено автовизначення мови
- ⚡ Оптимізація швидкості завантаження

### Version 1.0 (Січень 2026)
- 🎉 Початковий реліз

---

**⭐ Якщо проект сподобався - поставте зірку!**

---

<p align="center">Made with 💚 by Світлоносці</p>
