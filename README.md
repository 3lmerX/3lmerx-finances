
# 3lmerX Finances 💸

Personal finance manager built as a single HTML file.
Track your balance across bank, mobile wallet, and cash — register income and expenses, set savings goals, and visualize monthly reports.

## ✨ Features
- 💳 Multi-wallet tracking (Bank, Mobile, Cash, Other)
- 📈 Income & expense registration with categories
- 🎯 Savings goal with progress bar
- 📊 Monthly charts & category breakdown
- 🌍 Multi-language: Português, English, Español, Français
- 💾 Auto-save (localStorage) — works fully offline
- ☁️ Google Drive sync ready (configure Client ID)
- 📱 Mobile-friendly — add to home screen on iOS/Android

## 🚀 Usage
Just open `index.html` in any browser — no installation needed.

Or visit the live version: **[your-username.github.io/3lmerx-finances]()**

## ☁️ Enable Google Drive Sync
1. Go to [console.cloud.google.com](https://console.cloud.google.com)
2. Create a project → Enable **Google Drive API**
3. Create **OAuth 2.0 Client ID** (Web Application)
4. Add your GitHub Pages domain to Authorized JS Origins
5. Replace `YOUR_CLIENT_ID` in `index.html` with your Client ID

## 🛠 Tech Stack
- Vanilla HTML / CSS / JavaScript
- Google Identity Services (GIS) for OAuth
- Google Drive API (appDataFolder) for cloud sync
- localStorage for offline persistence

## 📱 Install on iPhone
1. Open the live link in Safari
2. Tap **Share** → **Add to Home Screen**
3. Done — works like a native app

---
*powered by elmer aguiar*
```

---

## 🔒 Configuração extra recomendada

**Após publicar no GitHub Pages**, vai ao Google Console e adiciona o teu domínio nas origens autorizadas:
```
https://teu-usuario.github.io
