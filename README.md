# 🎵 Shruti Music Bot 🎵

<div align="center">
  <img src="https://raw.githubusercontent.com/NoxxOP/ShrutiMusic/main/ShrutiMusic/assets/ShrutiBots.jpg" alt="ShrutiMusicBot Logo" width="500px">
  
  <h1>🎵 Shruti Music Bot 🎵</h1>
  
  <p><b>A Powerful Telegram Music Bot to Play Songs in Voice Chats</b></p>
  
  <!-- Animated badges with hover effects -->
  <p>
    <a href="https://t.me/ShrutiBots">
      <img src="https://img.shields.io/badge/Support%20Channel-FF6B6B?style=for-the-badge&logo=telegram&logoColor=white&labelColor=4ECDC4" alt="Support Channel">
    </a>
    <a href="https://t.me/ShrutiBotSupport">
      <img src="https://img.shields.io/badge/Support%20Group-4ECDC4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=FF6B6B" alt="Support Group">
    </a>
    <a href="https://t.me/WTF_WhyMeeh">
      <img src="https://img.shields.io/badge/Owner-9B59B6?style=for-the-badge&logo=telegram&logoColor=white&labelColor=3498DB" alt="Owner">
    </a>
  </p>
  
  <!-- Social stats with gradient styling -->
  <p>
    <a href="https://github.com/NoxxOP/ShrutiMusic/fork">
      <img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=2ECC71" alt="GitHub Forks">
    </a>
    <a href="https://github.com/NoxxOP/ShrutiMusic/stargazers">
      <img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=F39C12" alt="GitHub Stars">
    </a>
    <a href="https://github.com/NoxxOP/ShrutiMusic/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=E74C3C" alt="GitHub Contributors">
    </a>
  </p>
</div>

---

## 🚀 Quick Deploy Options

<div align="center">
  
  ### 🔥 Deploy to Heroku
  <a href="https://dashboard.heroku.com/new?template=https://github.com/NoxxOP/ShrutiMusic">
    <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-6762A6?style=for-the-badge&logo=heroku&logoColor=white&labelColor=9C88FF" width="280px" alt="Deploy to Heroku">
  </a>
  
  ### ☁️ Deploy to Render (Free)
  <a href="https://render.com/deploy?repo=https://github.com/NoxxOP/ShrutiMusic">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render" width="280px">
  </a>
  
  ### 🎵 Simple Music Bot
  <a href="https://github.com/NoxxOP/ShrutixMusic">
    <img src="https://img.shields.io/badge/Simple%20Music%20Bot-FF4757?style=for-the-badge&logo=github&logoColor=white&labelColor=2F3542" width="280px" alt="Simple Music Bot">
  </a>
  
</div>

---

## ✨ Features

<div align="center">

| 🎵 **Play Music** | 🔗 **Multiple Sources** | 📋 **Playlists** | 🌐 **Multi-Language** |
|:-----------------:|:------------------------:|:-----------------:|:----------------------:|
| Stream high-quality music in Telegram voice chats | YouTube, Spotify, SoundCloud, and local files | Create and manage playlists for your group | Available in multiple languages |

| 🎨 **Elegant UI** | 👑 **Group Management** | 🔊 **High Quality** | ⚡ **Fast & Reliable** |
|:-----------------:|:------------------------:|:--------------------:|:----------------------:|
| Clean and modern user interface | Powerful admin commands | Crystal clear audio streaming | Lightning fast response time |

</div>

---

## 📊 Repository Stats

<div align="center">
  <img src="https://img.shields.io/github/repo-size/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=FF6B6B&labelColor=4ECDC4" alt="Repo Size">
  <img src="https://img.shields.io/github/issues/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=4ECDC4&labelColor=FF6B6B" alt="Issues">
  <img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=9B59B6&labelColor=3498DB" alt="Forks">
  <img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=F39C12&labelColor=E74C3C" alt="Stars">
  <img src="https://img.shields.io/github/license/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=2ECC71&labelColor=F39C12" alt="LICENSE">
  <img src="https://img.shields.io/github/last-commit/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=E74C3C&labelColor=2ECC71" alt="Last Commit">
</div>

---

## 🔥 Essential Commands

<div align="center">

| Command | Description | Usage |
|---------|-------------|-------|
| `/play` | 🎵 Play song from YouTube | `/play [song name/URL]` |
| `/pause` | ⏸️ Pause the current stream | `/pause` |
| `/resume` | ▶️ Resume the paused stream | `/resume` |
| `/skip` | ⏭️ Skip to the next song | `/skip` |
| `/stop` | ⏹️ Stop the streaming | `/stop` |
| `/playlist` | 📋 Show the playlist | `/playlist` |
| `/song` | 📥 Download a song as audio | `/song [song name]` |
| `/settings` | ⚙️ Open bot settings | `/settings` |

</div>

---

## 🚀 Deployment Guide

### 🔧 VPS Deployment (Step by Step)

#### Prerequisites

First, update your system and install required packages:

```bash
sudo apt-get update && sudo apt-get upgrade -y
```

Install Python, Pip, FFmpeg, Git, Screen, Node.js, npm

```bash
sudo apt-get install python3 python3-pip ffmpeg git screen curl -y
```

Install Node.js (LTS Version) and npm

```bash
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
```

```bash
sudo apt-get install -y nodejs
```

#### Clone the Repository

```bash
git clone https://github.com/NoxxOP/ShrutiMusic
```

```bash
cd ShrutiMusic
```

#### Run 24x7 bot using screen

```bash
screen
```

#### Setup Virtual Environment

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

#### Install Dependencies

```bash
pip3 install -U pip
```

```bash
pip3 install -U -r requirements.txt
```

#### Configuration

Copy example config file and edit it with your values:

```bash
nano .env
```

**Fill in your:**

- `API_ID` & `API_HASH` from my.telegram.org
- `BOT_TOKEN` from @BotFather  
- `MONGO_DB_URI` from your MongoDB Atlas cluster
- `OWNER_ID` (Your Telegram user ID)
- `OWNER_USERNAME` (Your Telegram username without @)
- `BOT_USERNAME` (Your bot's username without @)
- `UPSTREAM_REPO` (GitHub repo URL for updates Recommend : Original Source)
- `STRING_SESSION` (Generate using @Sessionbbbot)
- `GIT_TOKEN` (If your repo is private)
- `LOG_GROUP_ID` (Log group/channel ID starting with -100)
- `SUPPORT_GROUP` (Full Link of your Support Group)
- `SUPPORT_CHANNEL` (Full Link Of your Support channel)
- `COOKIE_URL` (Optional: If no cookies file in Your Repo)
- `START_IMG_URL` (Image URL for /start message thumbnail)

#### Starting the Bot

There are two ways to start the bot:

**1. Using Python directly:**

```bash
python3 -m ShrutiMusic
```

**2. Using Bash script:**

```bash
bash start
```

To detach the screen, press `Ctrl+A` then `D`

To reattach the screen later:

```bash
screen -ls
```

See Your Screen ID and then:

```bash
screen -r {screen_id}
```

Make Sure Fill Your Screen ID without Bracket {} .  
Example : `screen -r 108108`

---

## ☁️ Heroku Deployment

<div align="center">
  <a href="https://dashboard.heroku.com/new?template=https://github.com/NoxxOP/ShrutiMusic">
    <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-6762A6?style=for-the-badge&logo=heroku&logoColor=white&labelColor=9C88FF" width="250px" alt="Deploy to Heroku">
  </a>
</div>

**Steps:**

1. **Click the button above**

2. **Fill in the required details:**
   - App name
   - API_ID & API_HASH
   - BOT_TOKEN
   - MUSIC_BOT_NAME
   - SESSION_STRING
   - SUDO_USERS (your User ID)

3. **Click "Deploy App"**

4. **Once deployed, go to Resources tab and turn on the worker**

---

## 🔄 How to Generate Session String

Use our Session Generator Bot: [@Sessionbbbot](https://t.me/Sessionbbbot)

1. **Start the bot**
2. **Send phone number with country code**
3. **Enter the OTP**
4. **Your session string will be generated**

---

## 🤔 Common Issues & Fixes

<div align="center">

| Issue | Solution |
|-------|----------|
| 🤖 **Bot not responding** | Check if the bot is running and has proper permissions |
| 🔇 **No sound in VC** | Ensure ffmpeg is properly installed |
| 🚫 **Can't join voice chat** | Make sure the bot is an admin with voice chat permissions |
| ⚠️ **API Issues** | Double check your API_ID and API_HASH |

</div>

---

## 🌟 Credits and Acknowledgements

<div align="center">
  
**👨‍💻 Main Developer:** [NoxxOP](https://github.com/NoxxOP)

**🙏 Special Thanks:** All contributors who helped make this project better

</div>

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📞 Support

<div align="center">

**For any questions or help, join our Support Group**

<a href="https://t.me/ShrutiBotSupport">
  <img src="https://img.shields.io/badge/Join%20Support%20Group-FF6B6B?style=for-the-badge&logo=telegram&logoColor=white&labelColor=4ECDC4" alt="Support Group">
</a>

---

<img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-NoxxOP-red?style=for-the-badge&logo=heart&labelColor=FF69B4" alt="Made with love">

---

**🎵 Enjoy Streaming Music with Shruti Bot! 🎵**

</div>
