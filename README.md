# Ubuntu Development Setup Script

A comprehensive setup script for Ubuntu-based development environments.

## 🚀 Usage

1. Review the script contents:
   ```bash
   nano setup.sh
   ```

2. Make executable and run:
   ```bash
   chmod +x setup.sh && ./makeBetterUbuntu.sh
   ```

3. Restart your session after completion

## 📦 Installed Components

### System Tools
- Base utilities (curl, git, vim, etc.)
- Brave Browser
- VSCode
- Media players (VLC, Spotify)

### Development
- Python 3 + pip + core packages
- Node.js LTS + npm
- Docker + Docker Compose
- PyCharm Community
- Postman

### Communication
- Telegram
- Discord
- Skype
- Slack

## ⚠️ Requirements
- Ubuntu 20.04/22.04 LTS
- Sudo privileges
- Internet connection

## 🔄 Post-Install
- Verify installations:  
  ```bash
  docker --version && node --version && python --version
  ```
- Restart for Docker group permissions