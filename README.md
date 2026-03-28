# AI-Privacy-Guard-System
Nowadays, privacy is very important. The AI Privacy Guard System helps users by detecting sensitive things like screens, documents, or people and automatically hiding them. This makes users feel safer and prevents privacy leaks.

Features

- Real-time **object detection** using YOLOv8
- **Biometric face verification** for owner recognition
- Automatic **alerts via Telegram** for unauthorized access
- **Privacy protection**: blurs unauthorized users or threats
- GUI built with **PyQt5**
- Secure handling of sensitive credentials using `.env` file
- Logs screenshots of potential threats in `Threat_Log

Setup environment variables:
Copy .env.example to .env
Add your Telegram BOT_TOKEN and CHAT_ID in .env
Example .env:
BOT_TOKEN=your_bot_token_here
CHAT_ID=your_chat_id_here
