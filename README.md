# Free Fire Bio VORTEX AURA Bot 🎮

A powerful Telegram bot designed to update **Garena Free Fire** profile bios instantly. Built with **Telebot (pyTelegramBotAPI)** and **Flask**, supporting both **Webhook** and **Polling** modes for high performance and reliability.

---

## 🌟 Features
- **Instant Bio Update**: Update your Free Fire bio instantly with custom text.
- **Multiple Token Formats**: Supports plain tokens, Kiosgamer links, and Garena Help links.
- **Channel Verification**: Optional channel join requirement for added security.
- **Dual Mode**: Seamlessly switches between Webhook (for production) and Polling (for development).
- **Rich Responses**: Displays updated profile info (Nickname, UID, Platform, Region).
- **Webhook Cleanup**: Automatic webhook deletion to prevent polling conflicts.

---

## 🤖 BOT Demo  

Try this bot directly on Telegram:  

[![Try on Telegram](https://img.shields.io/badge/Try%20on%20Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/paglu_pro_bot) 

## 🤖 Bot Commands
- `/start` - Welcome message and available commands.
- `/bio <access_token> <new bio>` - Update your Free Fire bio (Example: `/bio d8a4e0bd68fb FREE FIRE PRO ⚡`).
- `/help` - Show detailed help with token format examples.

---

## 🚀 Deployment
[![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://dashboard.render.com/web/new)
### Prerequisites
- Python 3.9+
- A Telegram Bot Token from [@BotFather](https://t.me/BotFather)

### Environment Variables
Set the following environment variables in your hosting provider (e.g., Render):

```bash
BOT_TOKEN=8250691654:AAEEMJI2umYAsjPj8-TbLrgAvhe8HDsP4YQ
API_KEY=your_api_key_here
WEBHOOK_URL=https://your-app-domain.com   # Optional: Only for Webhook mode
PORT=5000                                   # Optional: Default is 5000
```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/itz-paglu/Free-Fire-Long-Bio-Bot
   cd Free-Fire-Long-Bio-Bot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the bot:
   ```bash
   python main.py
   ```

---

## 🔗 How it Works
1. **Token Extraction**: Accepts multiple token formats (plain, URL-based) and extracts the access token.
2. **API Integration**: Sends bio update request to the Free Fire API with the provided access token and bio text.
3. **Instant Response**: Returns updated profile information (nickname, UID, platform, region) to the user.


## 📊 Repository Stats

<p align="center">
  <img src="https://img.shields.io/github/stars/itz-paglu/Free-Fire-Long-Bio-Bot?style=for-the-badge&logo=github&color=yellow" />
  <img src="https://img.shields.io/github/forks/itz-paglu/Free-Fire-Long-Bio-Bot?style=for-the-badge&logo=github&color=blue" />
  <img src="https://img.shields.io/github/contributors/itz-paglu/Free-Fire-Long-Bio-Bot?style=for-the-badge&logo=github&color=green" />
  <img src="https://komarev.com/ghpvc/?username=itz-paglu&repo=Free-Fire-Long-Bio-Bot&style=for-the-badge&color=red" />
</p>

---

## 💛 Credits  

<p align="center">
  <a href="https://whatsapp.com/channel/0029VbDQxsgDOQIa81wlIZ0F">
    <img src="https://img.shields.io/badge/Owner-🔥%20@itzpaglu-pink?style=for-the-badge&logo=telegram" />
  </a>
  <a href="https://whatsapp.com/channel/0029VbDQxsgDOQIa81wlIZ0F">
    <img src="https://img.shields.io/badge/Channel-TARIKUL.dev-blue?style=for-the-badge&logo=telegram" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/itz-paglu/Free-Fire-Bio-Updater-Bot/stargazers" target="_blank">
    <img src="https://img.shields.io/badge/⭐%20Star%20This%20Repo-yellow?style=for-the-badge&logo=github" />
  </a>
</p>
