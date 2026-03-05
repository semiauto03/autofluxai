# AutoFlux Ai 🤖⚡
### Empowering Business Growth with AI

A sleek, single-page marketing website for **AutoFlux Ai** — an AI automation agency that helps businesses scale smarter through intelligent automation systems.

---

## 🌐 Live Site

> _Add your deployed URL here (e.g. `https://autofluxai.vercel.app`)_

---

## 📋 Overview

AutoFlux Ai's landing page is a fully self-contained `index.html` file featuring:

- **Hero section** with an autoplay demo video and animated headline
- **Services section** showcasing 6 core AI offerings
- **How It Works** step-by-step process breakdown
- **Pricing plans** with tiered options
- **Testimonials / social proof**
- **Contact form** with live validation, EmailJS integration, and Google Sheets webhook logging
- **CTA section** for booking a free strategy call
- **Responsive footer** with service links and social media

---

## 🛠️ Services Featured

| Service | Description |
|---|---|
| 🎯 Lead Qualification | AI-powered lead scoring and filtering |
| 📱 Social Media Automation | Automated content and engagement workflows |
| 🤖 AI Chatbot | Intelligent customer support bots |
| 💬 WhatsApp AI | Automated WhatsApp communication |
| ⚙️ Workflow Automation | End-to-end business process automation |
| 📊 AI Analytics | Data insights and reporting automation |

---

## 🧰 Tech Stack

- **HTML5** — Single-file architecture
- **CSS3** — Custom properties, CSS Grid, Flexbox, animations
- **Vanilla JavaScript** — No frameworks
- **Fonts** — [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- **EmailJS** — Contact form email delivery
- **Google Sheets Webhook** — Form submission logging

---

## 📁 Project Structure

```
autoflux-ai/
├── index.html       # Entire website (single file)
├── favicon.png      # Site favicon
└── README.md        # This file
```

---

## 🚀 Deployment

### Option 1 — Netlify Drop (Fastest)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html`
3. Live in seconds ✅

### Option 2 — Vercel via GitHub
1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repository and click **Deploy**

### Option 3 — Vercel CLI
```bash
npm install -g vercel
vercel
```

---

## ⚙️ Configuration

### EmailJS
The contact form uses EmailJS. To connect your own account:
1. Sign up at [emailjs.com](https://www.emailjs.com)
2. Replace the Service ID and Template ID in `index.html`:
```js
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', { ... })
```

### Google Sheets Webhook
Form submissions are also logged to a Google Sheet. To update:
```js
var SHEET_WEBHOOK_URL = 'YOUR_GOOGLE_SHEET_WEBHOOK_URL';
```

---

## 📬 Contact

**AutoFlux Ai**
- 📧 autofluxai1@gmail.com
- 💬 WhatsApp
- 🔗 LinkedIn
- 📸 Instagram

---

© 2025 AutoFlux Ai. All rights reserved.
