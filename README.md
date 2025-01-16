# 🤖 Orion Discord Bot | Source Code on Releases

<div align="center">

![Orion Bot Banner](https://i.ibb.co/DW6MRff/0e288f8ba473130bcb190bdcb0ff93e9.png)

*A powerful Discord bot powered by Mistral AI, bringing intelligent conversations and image analysis to your server.*

[Features](#features) •
[Installation](#installation) •
[Usage](#usage) •
[Contributing](#contributing) •
[Support](#support)

</div>

## ✨ Features

- 🧠 **Advanced AI Conversations** - Powered by Mistral AI for natural and context-aware interactions
- 🖼️ **Image Analysis** - Detailed image descriptions and visual content understanding
- 📄 **File Processing** - Handle PDF, DOCX, and XLSX files with ease
- ⚡ **Slash Commands** - Modern Discord command system
- 📝 **Smart Logging** - Comprehensive logging system for monitoring and debugging

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16.9.0 or higher
- [Discord Bot Token](https://discord.com/developers/applications)
- [Mistral AI API Key](https://console.mistral.ai/)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/orion-discord-bot.git
cd orion-discord-bot
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure environment variables**
   
Create a `.env` file in the root directory:
```env
# Discord Configuration
DISCORD_TOKEN=your_discord_bot_token
CLIENT_ID=your_discord_client_id

# Logging
LOG_LEVEL=info

# Mistral AI
MISTRAL_API_KEY=your_mistral_api_key
MISTRAL_MODEL=use-pixtral
MISTRAL_TEMPERATURE=
MISTRAL_MAX_TOKENS=
MISTRAL_SAFE_MODE=false
```

4. **Deploy commands**
```bash
npm run deploy-commands
```

5. **Start the bot**
```bash
npm start
```

For development with auto-reload:
```bash
npm run dev
```

## 💡 Usage

### Available Commands

#### AI Commands
| Command | Description |
|---------|-------------|
| `/orion` | Start an AI-powered conversation with image analysis capabilities |

#### Moderation Commands
| Command | Description |
|---------|-------------|
| `/ban` | Ban a user from the server |
| `/unban` | Unban a user from the server |
| `/kick` | Kick a user from the server |
| `/mute` | Mute a user in the server |
| `/unmute` | Unmute a user in the server |
| `/mutehistory` | View mute history for a user |
| `/purge` | Delete multiple messages at once |

#### Admin Commands
| Command | Description |
|---------|-------------|
| `/autorole` | Configure automatic role assignment |
| `/setlogs` | Set up logging channels |
| `/logs` | View server logs and configurations |


```

---
Made with ❤️ by KleoSr
