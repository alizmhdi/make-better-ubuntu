# Ubuntu Development Setup Script

A comprehensive setup script for Ubuntu-based development environments.

## Usage

1. Review the script contents:
   ```bash
   nano makeBetterUbuntu.sh
   ```

2. Make executable and run:
   ```bash
   chmod +x makeBetterUbuntu.sh && ./makeBetterUbuntu.sh
   ```

3. Restart your session after completion

## Installed Components

### System Tools & Utilities
- Base utilities (curl, git, vim, wget, gnupg, ca-certificates, etc.)
- Brave Browser
- VSCode
- Media players (VLC, Spotify)
- Terminator (advanced terminal)
- GDebi (Debian package installer)
- libfuse2 (AppImage support)
- htop (system monitor)
- neofetch (system info)
- tmux (terminal multiplexer)
- nmap (network scanner)
- gparted (disk utility)
- flameshot (screenshot tool)
- obs-studio (screen recording/streaming)
- zsh & Oh My Zsh (advanced shell)
- tree (directory listing)
- unzip (archive utility)
- ffmpeg (media conversion)
- jq (JSON processor)

### Development
- Python 3 + pip + core packages (requests, pandas, numpy, virtualenv)
- Node.js LTS + npm
- Docker + Docker Compose
- Build-essential (compilers & dev tools)
- PyCharm Community
- Postman

### AI
- Claude Code (`claude`)
- OpenAI Codex CLI (`codex`)
- GitHub Copilot CLI (`copilot`)
- Gemini CLI (`gemini`)
- Ollama (run models locally)
- VS Code extensions: GitHub Copilot Chat, Claude Code, Codex

### Communication
- Telegram
- Discord
- Skype
- Slack

## Requirements
- Ubuntu 20.04/22.04 LTS
- Sudo privileges
- Internet connection

## Post-Install
- Verify installations:  
  ```bash
  docker --version && node --version && python --version
  ```
- Restart for Docker group permissions
- Sign in to the AI tools on first run (`claude`, `codex`, `copilot`, `gemini`); each needs its own account or API key
- A failed AI tool install only prints a warning, so check the output if one is missing
