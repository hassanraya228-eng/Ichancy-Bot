# 🎰 Ichancy Bot

A powerful Discord/Telegram bot for gaming and entertainment with advanced features.

## 📋 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- 🎲 **Gaming System** - Interactive games and activities
- 👥 **User Management** - Advanced user tracking and profiles
- 💰 **Economy System** - Currency and trading system
- 🏆 **Leaderboards** - Track top players
- ⚙️ **Customizable** - Easy configuration and extensions
- 🔐 **Secure** - Built-in security features
- 📊 **Statistics** - Detailed analytics and reporting

## 🚀 Installation

### Prerequisites

- Python 3.8+
- pip (Python package manager)
- Discord/Telegram account

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/hassanraya228-eng/Ichancy-Bot.git
   cd Ichancy-Bot
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the bot**
   ```bash
   cp .env.example .env
   # Edit .env with your settings
   ```

5. **Run the bot**
   ```bash
   python main.py
   ```

## ⚙️ Configuration

Create a `.env` file with the following variables:

```env
# Discord Bot
DISCORD_TOKEN=your_discord_token_here
DISCORD_PREFIX=!

# Telegram Bot
TELEGRAM_TOKEN=your_telegram_token_here

# Database
DATABASE_URL=sqlite:///bot.db

# Logging
LOG_LEVEL=INFO
```

## 💻 Usage

### Starting the Bot

```bash
python main.py
```

### Available Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `!help` | Show all commands | `!help` |
| `!play` | Start a game | `!play [game_name]` |
| `!profile` | View your profile | `!profile [@user]` |
| `!leaderboard` | Show leaderboard | `!leaderboard` |
| `!stats` | View statistics | `!stats [@user]` |

## 📚 Project Structure

```
Ichancy-Bot/
├── main.py              # Main bot entry point
├── config.py            # Configuration file
├── requirements.txt     # Python dependencies
├── .env.example         # Environment variables template
├── .gitignore          # Git ignore rules
├── README.md           # This file
├── CONTRIBUTING.md     # Contribution guidelines
├── LICENSE             # MIT License
└── bot/
    ├── __init__.py
    ├── commands/       # Bot commands
    ├── cogs/           # Discord cogs
    ├── utils/          # Utility functions
    ├── database/       # Database models
    └── handlers/       # Event handlers
```

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

## 👤 Author

**Hassan Raya** - [@hassanraya228-eng](https://github.com/hassanraya228-eng)

## 🔗 Links

- [Discord Server](https://discord.gg/) - Coming soon
- [Documentation](./docs) - Additional documentation
- [Issue Tracker](https://github.com/hassanraya228-eng/Ichancy-Bot/issues)

## ⭐ Support

If you like this project, please give it a star! ⭐

---

**Last Updated:** 2026-06-21
**Version:** 1.0.0
