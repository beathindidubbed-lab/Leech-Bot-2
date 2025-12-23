<p align="center">
    <a href="https://github.com/beathindidubbed-lab/Leech-bot-2">
        <kbd>
            <img  src="https://i.ibb.co/W4vM6Jk6/logo.png" alt="Beat Anime Leech Bot">
        </kbd>
    </a>

<i>This is an advanced, feature-rich Telegram bot for downloading, leeching, and mirroring content. Built with efficiency and customization in mind, it supports torrents, direct downloads, cloud uploads, and much more. Fully deployable on VPS, Docker, and Heroku.</i>

</p>

<div align=center>

[![](https://img.shields.io/github/repo-size/beathindidubbed-lab/Leech-bot-2?color=green&label=Repo%20Size&labelColor=292c3b)](#) [![](https://img.shields.io/github/commit-activity/m/beathindidubbed-lab/Leech-bot-2?logo=github&labelColor=292c3b&label=Github%20Commits)](#) [![](https://img.shields.io/github/license/beathindidubbed-lab/Leech-bot-2?style=flat&label=License&labelColor=292c3b)](#)|[![](https://img.shields.io/github/issues-raw/beathindidubbed-lab/Leech-bot-2?style=flat&label=Open%20Issues&labelColor=292c3b)](#) [![](https://img.shields.io/github/issues-closed-raw/beathindidubbed-lab/Leech-bot-2?style=flat&label=Closed%20Issues&labelColor=292c3b)](#) [![](https://img.shields.io/github/issues-pr-raw/beathindidubbed-lab/Leech-bot-2?style=flat&label=Open%20Pull%20Requests&labelColor=292c3b)](#) [![](https://img.shields.io/github/issues-pr-closed-raw/beathindidubbed-lab/Leech-bot-2?style=flat&label=Closed%20Pull%20Requests&labelColor=292c3b)](#)
:---:|:---:|
[![](https://img.shields.io/github/languages/count/beathindidubbed-lab/Leech-bot-2?style=flat&label=Total%20Languages&labelColor=292c3b&color=blueviolet)](#) [![](https://img.shields.io/github/languages/top/beathindidubbed-lab/Leech-bot-2?style=flat&logo=python&labelColor=292c3b)](#) [![](https://img.shields.io/github/last-commit/beathindidubbed-lab/Leech-bot-2?style=flat&label=Last%20Commit&labelColor=292c3b&color=important)](#) [![](https://badgen.net/github/branches/beathindidubbed-lab/Leech-bot-2?label=Total%20Branches&labelColor=292c3b)](#)|[![](https://img.shields.io/github/forks/beathindidubbed-lab/Leech-bot-2?style=flat&logo=github&label=Forks&labelColor=292c3b&color=critical)](#) [![](https://img.shields.io/github/stars/beathindidubbed-lab/Leech-bot-2?style=flat&logo=github&label=Stars&labelColor=292c3b&color=yellow)](#) [![](https://badgen.net/docker/pulls/beathindidubbed/leech-bot-2?icon=docker&label=Pulls&labelColor=292c3b&color=blue)](#)
[![](https://img.shields.io/badge/Telegram%20Channel-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=292c3b)](https://t.me/Beat_Hindi_Dubbed) |[![](https://img.shields.io/badge/Support%20Group-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=292c3b)](https://t.me/Beat_Anime_Discussion) |

</div>

---

# 📋 Table of Contents

- [✨ Features](#-features)
- [🚀 Deployment Guide](#-deployment-guide)
  - [VPS Deployment](#vps-deployment)
  - [Docker Deployment](#docker-deployment)
  - [Heroku Deployment](#heroku-deployment)
- [⚙️ Configuration](#️-configuration)
- [📝 Bot Commands](#-bot-commands)
- [🎯 Usage Examples](#-usage-examples)
- [🛠️ Advanced Features](#️-advanced-features)
- [❓ FAQ & Troubleshooting](#-faq--troubleshooting)
- [👨‍💻 Developer](#-developer)
- [📜 License](#-license)

---

## ✨ Features

<details>
<summary><b>🎯 Core Features</b></summary>

### Download & Leech
- 📥 **Multi-Protocol Support**: Torrent, Magnet Links, Direct URLs, YouTube, NZB (Usenet)
- ⚡ **High-Speed Downloads**: Aria2c, qBittorrent, SABnzbd integration
- 🔄 **Batch Processing**: Handle multiple downloads simultaneously
- 📦 **Archive Support**: Extract RAR, ZIP, 7Z, TAR files automatically
- 🎬 **Media Processing**: FFmpeg integration for video/audio conversion
- 🎯 **Selective Downloads**: Choose specific files from torrents via web interface

### Upload & Mirror
- ☁️ **Cloud Storage**: Google Drive, Mega.nz, Rclone (50+ cloud services)
- 📤 **Telegram Upload**: Auto-split large files, custom thumbnails, media grouping
- 🔗 **Direct Links**: Generate streamable/downloadable links
- 🎞️ **YouTube Upload**: Direct upload to your YouTube channel
- 🔄 **Auto-Rename**: Customize file names before upload

### Advanced Features
- 🎨 **Custom Thumbnails**: Set global or per-file thumbnails
- ✏️ **File Renaming**: Rename files/folders before upload
- 🔐 **Password Protection**: Extract password-protected archives
- 📊 **Real-time Status**: Live progress tracking with ETA and speed
- 🚫 **Duplicate Detection**: Avoid re-uploading existing files
- 🌐 **Web Interface**: Beautiful UI for torrent file selection

</details>

<details>
<summary><b>🛠️ Technical Features</b></summary>

- 🐳 **Docker Ready**: One-command deployment with Docker Compose
- 🔄 **Auto-Updates**: Keep bot up-to-date automatically
- 📝 **Comprehensive Logging**: Detailed error tracking and debugging
- 🔌 **Plugin System**: Extend functionality with custom plugins
- 🎚️ **Queue Management**: Control download/upload queues
- 📈 **Resource Management**: CPU and bandwidth limiting
- 🔒 **Security**: User authorization, sudo users, force subscription
- 🌍 **Multi-Language**: Support for multiple languages

</details>

<details>
<summary><b>🎪 Media Features</b></summary>

- 🎬 **Video Processing**: Compress, convert, trim videos
- 🖼️ **Screenshot Generator**: Auto-generate video thumbnails
- 🎵 **Audio Extraction**: Extract audio from videos
- 📺 **Streaming Support**: Generate streaming links
- 🎞️ **Subtitle Support**: Download videos with subtitles
- 🎨 **Custom Captions**: Add custom text to uploads
- 📏 **Split Files**: Auto-split large files for Telegram

</details>

---

# 🚀 Deployment Guide

## Prerequisites

Before deployment, you need:

- **Telegram Bot Token** from [@BotFather](https://t.me/BotFather)
- **Telegram API ID & Hash** from [my.telegram.org](https://my.telegram.org/apps)
- **MongoDB Database URL** (Optional but recommended)
- **Your Telegram User ID** - Get it from [@userinfobot](https://t.me/userinfobot)

---

## VPS Deployment

<details>
  <summary><strong>View All Steps <kbd>Click Here</kbd></strong></summary>

---

### 1. Prerequisites

- **Ubuntu/Debian VPS** (Recommended: 2GB RAM, 20GB Storage)
- **Root/Sudo Access**
- **Tutorial Video from A to Z**

[![See Video](https://img.shields.io/badge/See%20Video-black?style=for-the-badge&logo=YouTube)](https://youtu.be/your-tutorial-link)

---

### 2. Installing Requirements

**Update System:**

```bash
sudo apt update && sudo apt upgrade -y
```

**Install Dependencies:**

```bash
sudo apt install -y git wget curl python3 python3-pip
```

**Clone Repository:**

```bash
git clone https://github.com/beathindidubbed-lab/Leech-bot.git
cd Leech-bot
```

**Install Python Packages:**

```bash
pip3 install -r requirements.txt
```

---

### 3. Configuration

**Copy Sample Config:**

```bash
cp config_sample.py config.py
```

**Edit Configuration:**

```bash
nano config.py
```

**Fill in Required Variables:**

```python
BOT_TOKEN = "your_bot_token_here"
OWNER_ID = your_telegram_id
TELEGRAM_API = your_api_id
TELEGRAM_HASH = "your_api_hash"
DATABASE_URL = "mongodb://localhost:27017/leechbot"
```

Save with `Ctrl+X`, then `Y`, then `Enter`.

---

### 4. Running the Bot

**Method 1: Direct Run (Testing)**

```bash
python3 -m bot
```

**Method 2: Using Screen (Background)**

```bash
# Install screen
sudo apt install screen -y

# Create new screen session
screen -S leechbot

# Run bot
python3 -m bot

# Detach from screen: Press Ctrl+A, then D
# Reattach to screen
screen -r leechbot
```

**Method 3: Using PM2 (Recommended)**

```bash
# Install Node.js & PM2
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs
sudo npm install -g pm2

# Start bot
pm2 start "python3 -m bot" --name leechbot

# Auto-restart on system reboot
pm2 startup
pm2 save

# View logs
pm2 logs leechbot

# Stop bot
pm2 stop leechbot

# Restart bot
pm2 restart leechbot
```

---

</details>

---

## Docker Deployment

<details>
  <summary><strong>View All Steps <kbd>Click Here</kbd></strong></summary>

---

### Using Docker Compose (Recommended)

**Note:** This is the easiest and most reliable method for deployment.

---

### 1. Install Docker & Docker Compose

**For Ubuntu/Debian:**

```bash
# Install Docker
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

# Install Docker Compose
sudo apt install docker-compose -y

# Add user to docker group (optional)
sudo usermod -aG docker $USER
```

---

### 2. Clone Repository

```bash
git clone https://github.com/beathindidubbed-lab/Leech-bot.git
cd Leech-bot
```

---

### 3. Setup Configuration

**Create .env file:**

```bash
cp .env.sample .env
nano .env
```

**Add your configuration:**

```bash
BOT_TOKEN=your_bot_token_here
OWNER_ID=your_telegram_id
TELEGRAM_API=your_api_id
TELEGRAM_HASH=your_api_hash
DATABASE_URL=mongodb://mongo:27017/leechbot
BASE_URL=http://your-server-ip
BASE_URL_PORT=80
```

---

### 4. Create Required Directories

```bash
mkdir -p downloads thumbnails accounts tokens rclone
chmod -R 777 downloads thumbnails accounts tokens rclone
```

---

### 5. Build and Run

**Start the bot:**

```bash
sudo docker-compose up -d
```

**View logs:**

```bash
sudo docker-compose logs -f
```

**Stop the bot:**

```bash
sudo docker-compose stop
```

**Restart the bot:**

```bash
sudo docker-compose restart
```

**Rebuild after changes:**

```bash
sudo docker-compose up -d --build
```

---

### Using Official Docker Commands

**Start Docker daemon** (skip if already running):

```bash
sudo dockerd
```

**Build the Docker image:**

```bash
sudo docker build . -t leechbot
```

**Run the image:**

```bash
sudo docker run -p 80:80 -p 8080:8080 leechbot
```

**To stop the running container:**

First, list running containers:

```bash
sudo docker ps
```

Then, stop using container ID:

```bash
sudo docker stop <container_id>
```

---

### Docker Notes

**IMPORTANT:**

1. Set `BASE_URL_PORT` and `RCLONE_SERVE_PORT` variables to any port you want. Default is `80` and `8080`.
2. Stop the running container before deleting it.
3. Delete the container before deleting the image.

**Delete container:**

```bash
sudo docker container prune
```

**Delete images:**

```bash
sudo docker image prune -a
```

**Optimize qBittorrent:**

Check CPU cores with `nproc` and multiply by 4, then edit `AsyncIOThreadsCount` in `qBittorrent/config/qBittorrent.conf`.

---

**Tutorial Video for Docker Deployment:**

[![See Video](https://img.shields.io/badge/See%20Video-black?style=for-the-badge&logo=YouTube)](https://youtu.be/your-docker-tutorial)

---

</details>

---

## Heroku Deployment

<details>
  <summary><strong>View All Steps <kbd>Click Here</kbd></strong></summary>

---

### Quick Deploy

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/beathindidubbed-lab/Leech-bot-2)

---

### Manual Heroku Deployment

**Check the Detailed Guide:** [Click Here](https://github.com/beathindidubbed-lab/Leech-bot-2/wiki/Heroku-Deploy)

**Steps:**

1. Fork this repository
2. Go to [Heroku Dashboard](https://dashboard.heroku.com/)
3. Create New App
4. Connect to GitHub
5. Select your forked repository
6. Go to Settings → Config Vars
7. Add all required variables
8. Go to Deploy tab
9. Click "Deploy Branch"

---

**Required Config Vars:**

```
BOT_TOKEN = your_bot_token
OWNER_ID = your_telegram_id
TELEGRAM_API = your_api_id
TELEGRAM_HASH = your_api_hash
DATABASE_URL = your_mongodb_url
```

---

</details>

---

## ⚙️ Configuration

### Essential Variables

<details>
<summary><b>Click to view all configuration options</b></summary>

### Required Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `BOT_TOKEN` | Bot token from BotFather | `1234567890:ABCdefGhIjKlmNoPQRsTUVwxyZ` |
| `OWNER_ID` | Your Telegram user ID | `123456789` |
| `TELEGRAM_API` | API ID from my.telegram.org | `12345678` |
| `TELEGRAM_HASH` | API Hash from my.telegram.org | `0123456789abcdef0123456789abcdef` |
| `DATABASE_URL` | MongoDB connection string | `mongodb://localhost:27017/bot` |

### Optional Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `AUTHORIZED_CHATS` | Allowed chat IDs (space-separated) | - |
| `SUDO_USERS` | Admin user IDs (space-separated) | - |
| `STATUS_LIMIT` | Number of tasks in status | `10` |
| `DEFAULT_UPLOAD` | Default upload destination | `gd` |
| `LEECH_SPLIT_SIZE` | Split size for Telegram upload | `2GB` |

### Upload Configuration

```python
# Google Drive
GDRIVE_ID = "folder_id"
IS_TEAM_DRIVE = False
INDEX_URL = "https://example.com"

# Rclone
RCLONE_PATH = "remote:path"
RCLONE_FLAGS = "--drive-chunk-size=128M"
```

### Limits

```python
TORRENT_LIMIT = 0  # 0 = unlimited
DIRECT_LIMIT = 0
YTDLP_LIMIT = 0
CLONE_LIMIT = 0
MEGA_LIMIT = 0
STORAGE_LIMIT = 0

# User limits
BOT_MAX_TASKS = 0
USER_MAX_TASKS = 2
```

</details>

---

## 📝 Bot Commands

### 👤 User Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `/start` | Start the bot | `/start` |
| `/help` | Show help menu | `/help` |
| `/mirror` | Mirror to cloud | `/mirror <link>` |
| `/leech` | Leech to Telegram | `/leech <link>` |
| `/clone` | Clone Google Drive | `/clone <gdrive_link>` |
| `/ytdl` | YouTube download | `/ytdl <youtube_link>` |
| `/status` | Check tasks status | `/status` |
| `/cancel` | Cancel task | `/cancel <gid>` |
| `/stats` | User statistics | `/stats` |

### 🔧 Advanced Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `/qbmirror` | Mirror with qBittorrent | `/qbmirror <magnet>` |
| `/qbleech` | Leech with qBittorrent | `/qbleech <magnet>` |
| `/extract` | Extract archive | `/extract <link>` |
| `/archive` | Create archive | `/archive <link>` |
| `/rename` | Rename file | `/rename newname` |
| `/thumb` | Set thumbnail | `/thumb` (reply to image) |
| `/split` | Split file size | `/split 2GB` |

### 👑 Owner Commands

| Command | Description | Usage |
|---------|-------------|-------|
| `/auth` | Authorize user | `/auth <user_id>` |
| `/unauth` | Unauthorize user | `/unauth <user_id>` |
| `/addsudo` | Add sudo user | `/addsudo <user_id>` |
| `/rmsudo` | Remove sudo | `/rmsudo <user_id>` |
| `/restart` | Restart bot | `/restart` |
| `/log` | Get log file | `/log` |
| `/shell` | Execute shell command | `/shell ls -la` |
| `/broadcast` | Broadcast message | `/broadcast` (reply to msg) |

---

## 🎯 Usage Examples

### Basic Leech

```
/leech https://example.com/file.zip
```

### Custom Name

```
/leech https://example.com/file.zip | CustomName.zip
```

### Batch Download

```
/leech
https://link1.com
https://link2.com
https://link3.com
```

### YouTube Download

```
/ytdl https://youtube.com/watch?v=xxxxx
```

### Mirror to Google Drive

```
/mirror https://example.com/largefile.zip
```

### Selective Download

```
/qbmirror magnet:?xt=urn:btih:xxxxx -s
```
Bot will provide a link to select specific files.

---

## 🛠️ Advanced Features

<details>
<summary><b>🎨 Custom Thumbnails</b></summary>

Set global or temporary thumbnails:

```
# Set global thumbnail
/thumb (reply to image)

# Temporary thumbnail (one-time use)
/thumb temp (reply to image)
/leech <link>
```

</details>

<details>
<summary><b>📂 Google Drive Setup</b></summary>

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project
3. Enable Google Drive API
4. Create credentials (OAuth 2.0)
5. Download `credentials.json`
6. Place it in the bot directory
7. Run `python3 generate_drive_token.py`
8. Get `token.pickle` file
9. Add folder ID to config

</details>

<details>
<summary><b>☁️ Rclone Setup</b></summary>

```bash
# Install rclone
curl https://rclone.org/install.sh | sudo bash

# Configure remote
rclone config

# Place rclone.conf in bot directory
cp ~/.config/rclone/rclone.conf rclone/
```

</details>

---

## ❓ FAQ & Troubleshooting

<details>
<summary><b>Bot not responding?</b></summary>

1. Check if bot is running: `pm2 status` or `docker ps`
2. Check logs: `pm2 logs` or `docker-compose logs`
3. Verify bot token is correct
4. Ensure MongoDB is running

</details>

<details>
<summary><b>Downloads not working?</b></summary>

1. Check disk space: `df -h`
2. Verify permissions: `chmod 777 downloads`
3. Check logs for errors
4. Ensure required services are running (aria2c, qBittorrent)

</details>

<details>
<summary><b>Upload to Google Drive failing?</b></summary>

1. Regenerate `token.pickle`
2. Check `credentials.json` is valid
3. Verify folder ID is correct
4. Ensure Google Drive API is enabled

</details>

---

## 👨‍💻 Developer

<details>
    <summary><b>Click Here For Info</b></summary>

|<img width="120" src="https://i.ibb.co/W4vM6Jk6/logo.png">|
|:---:|
|[`BeatAnimes`](https://github.com/beathindidubbed-lab)|
|**Telegram Bot Developer & Content Creator**|
|Specialized in Anime, Hindi Dubbed Content & Automation|

**Connect with me:**

[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-blue?logo=telegram)](https://t.me/Beat_Hindi_Dubbed)
[![Support Group](https://img.shields.io/badge/Telegram-Group-blue?logo=telegram)](https://t.me/Beat_Anime_Discussion)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/beathindidubbed-lab)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:beathindidubbed@gmail.com)

</details>

---

## 🙏 Credits

- Based on [mirror-leech-telegram-bot](https://github.com/anasty17/mirror-leech-telegram-bot)
- Enhanced and customized with additional features
- Thanks to all contributors and testers

---

## 📜 License

This project is licensed under the **GNU Affero General Public License v3.0**

```
Copyright (C) 2025 BeatAnimes

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
```

See [LICENSE](LICENSE) file for full details.

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

### 🍴 Fork it to create your own version!

### 📢 Join our [Telegram Channel](https://t.me/Beat_Hindi_Dubbed) for updates!

---

**Made with ❤️ by [BeatAnimes](https://github.com/beathindidubbed-lab)**

**For Anime Lovers & Hindi Dubbed Content Fans**

</div>
