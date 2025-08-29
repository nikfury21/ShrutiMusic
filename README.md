# 🎵 Shruti Music Bot 🎵

<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 620 120" width="100%" height="120" role="img" aria-label="Equalizer">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="#FF6B6B"/>
        <stop offset="0.5" stop-color="#9B59B6"/>
        <stop offset="1" stop-color="#4ECDC4"/>
      </linearGradient>
      <filter id="blur">
        <feGaussianBlur stdDeviation="2.5"/>
      </filter>
    </defs>

    <!-- baseline -->
    <rect x="0" y="102" width="620" height="2" fill="currentColor" opacity="0.12"/>

    <g fill="url(#g)" filter="url(#blur)">
      <!-- each bar uses SMIL animate on height and y for up-down motion -->
      <!-- adjust x positions or add/remove <rect> to change count -->
      <rect x="40"  y="20" width="12" height="80" rx="3">
        <animate attributeName="height" values="16;92;30;70;16" dur="1.4s" repeatCount="indefinite" begin="0s"/>
        <animate attributeName="y"      values="92;28;62;50;92" dur="1.4s" repeatCount="indefinite" begin="0s"/>
      </rect>

      <rect x="70"  y="34" width="12" height="66" rx="3">
        <animate attributeName="height" values="28;78;22;68;28" dur="1.38s" repeatCount="indefinite" begin="0.08s"/>
        <animate attributeName="y"      values="78;42;70;52;78" dur="1.38s" repeatCount="indefinite" begin="0.08s"/>
      </rect>

      <rect x="100" y="50" width="12" height="50" rx="3">
        <animate attributeName="height" values="12;86;36;54;12" dur="1.46s" repeatCount="indefinite" begin="0.16s"/>
        <animate attributeName="y"      values="88;34;64;56;88" dur="1.46s" repeatCount="indefinite" begin="0.16s"/>
      </rect>

      <rect x="130" y="34" width="12" height="66" rx="3">
        <animate attributeName="height" values="30;82;28;60;30" dur="1.32s" repeatCount="indefinite" begin="0.24s"/>
        <animate attributeName="y"      values="72;28;64;52;72" dur="1.32s" repeatCount="indefinite" begin="0.24s"/>
      </rect>

      <rect x="160" y="20" width="12" height="80" rx="3">
        <animate attributeName="height" values="18;90;40;66;18" dur="1.5s" repeatCount="indefinite" begin="0.30s"/>
        <animate attributeName="y"      values="88;30;58;54;88" dur="1.5s" repeatCount="indefinite" begin="0.30s"/>
      </rect>

      <rect x="190" y="12" width="12" height="96" rx="3">
        <animate attributeName="height" values="26;96;44;72;26" dur="1.36s" repeatCount="indefinite" begin="0.18s"/>
        <animate attributeName="y"      values="86;24;58;48;86" dur="1.36s" repeatCount="indefinite" begin="0.18s"/>
      </rect>

      <rect x="220" y="24" width="12" height="76" rx="3">
        <animate attributeName="height" values="22;80;30;68;22" dur="1.44s" repeatCount="indefinite" begin="0.10s"/>
        <animate attributeName="y"      values="78;32;60;52;78" dur="1.44s" repeatCount="indefinite" begin="0.10s"/>
      </rect>

      <rect x="250" y="36" width="12" height="64" rx="3">
        <animate attributeName="height" values="20;74;28;64;20" dur="1.28s" repeatCount="indefinite" begin="0.22s"/>
        <animate attributeName="y"      values="74;40;62;56;74" dur="1.28s" repeatCount="indefinite" begin="0.22s"/>
      </rect>

      <rect x="280" y="14" width="12" height="86" rx="3">
        <animate attributeName="height" values="30;92;36;70;30" dur="1.5s" repeatCount="indefinite" begin="0.02s"/>
        <animate attributeName="y"      values="86;28;60;50;86" dur="1.5s" repeatCount="indefinite" begin="0.02s"/>
      </rect>

      <!-- right side mirrored with different timings -->
      <rect x="330" y="18" width="12" height="82" rx="3">
        <animate attributeName="height" values="18;90;34;68;18" dur="1.42s" repeatCount="indefinite" begin="0.12s"/>
        <animate attributeName="y"      values="84;28;58;52;84" dur="1.42s" repeatCount="indefinite" begin="0.12s"/>
      </rect>

      <rect x="360" y="30" width="12" height="70" rx="3">
        <animate attributeName="height" values="24;80;30;66;24" dur="1.34s" repeatCount="indefinite" begin="0.20s"/>
        <animate attributeName="y"      values="76;36;60;54;76" dur="1.34s" repeatCount="indefinite" begin="0.20s"/>
      </rect>

      <rect x="390" y="48" width="12" height="52" rx="3">
        <animate attributeName="height" values="16;72;28;60;16" dur="1.38s" repeatCount="indefinite" begin="0.28s"/>
        <animate attributeName="y"      values="76;36;60;54;76" dur="1.38s" repeatCount="indefinite" begin="0.28s"/>
      </rect>

      <rect x="420" y="32" width="12" height="68" rx="3">
        <animate attributeName="height" values="20;84;34;64;20" dur="1.46s" repeatCount="indefinite" begin="0.04s"/>
        <animate attributeName="y"      values="84;28;56;52;84" dur="1.46s" repeatCount="indefinite" begin="0.04s"/>
      </rect>

      <rect x="450" y="22" width="12" height="78" rx="3">
        <animate attributeName="height" values="22;88;40;70;22" dur="1.40s" repeatCount="indefinite" begin="0.16s"/>
        <animate attributeName="y"      values="86;24;58;50;86" dur="1.40s" repeatCount="indefinite" begin="0.16s"/>
      </rect>

      <rect x="480" y="12" width="12" height="96" rx="3">
        <animate attributeName="height" values="26;96;46;74;26" dur="1.30s" repeatCount="indefinite" begin="0.26s"/>
        <animate attributeName="y"      values="86;20;54;48;86" dur="1.30s" repeatCount="indefinite" begin="0.26s"/>
      </rect>

      <rect x="510" y="24" width="12" height="76" rx="3">
        <animate attributeName="height" values="20;78;32;66;20" dur="1.36s" repeatCount="indefinite" begin="0.06s"/>
        <animate attributeName="y"      values="78;34;60;52;78" dur="1.36s" repeatCount="indefinite" begin="0.06s"/>
      </rect>

      <rect x="540" y="38" width="12" height="62" rx="3">
        <animate attributeName="height" values="18;76;30;64;18" dur="1.44s" repeatCount="indefinite" begin="0.14s"/>
        <animate attributeName="y"      values="74;40;60;56;74" dur="1.44s" repeatCount="indefinite" begin="0.14s"/>
      </rect>

      <rect x="570" y="52" width="12" height="48" rx="3">
        <animate attributeName="height" values="12;70;26;60;12" dur="1.48s" repeatCount="indefinite" begin="0.22s"/>
        <animate attributeName="y"      values="76;34;62;54;76" dur="1.48s" repeatCount="indefinite" begin="0.22s"/>
      </rect>
    </g>
  </svg>
</div>


<div align="center">
  <img src="https://raw.githubusercontent.com/NoxxOP/ShrutiMusic/main/ShrutiMusic/assets/ShrutiBots.jpg" alt="ShrutiMusicBot Logo" width="500px">
  
  <h1>🎵 Shruti Music Bot 🎵</h1>
  
  <p><b>A Powerful Telegram Music Bot to Play Songs in Voice Chats</b></p>
  
  <!-- Bold and vibrant badges with striking combinations -->
  <p>
    <a href="https://t.me/ShrutiBots">
      <img src="https://img.shields.io/badge/Support%20Channel-FF0000?style=for-the-badge&logo=telegram&logoColor=white&labelColor=000000" alt="Support Channel">
    </a>
    <a href="https://t.me/ShrutiBotSupport">
      <img src="https://img.shields.io/badge/Support%20Group-00FF00?style=for-the-badge&logo=telegram&logoColor=black&labelColor=FF0000" alt="Support Group">
    </a>
    <a href="https://t.me/WTF_WhyMeeh">
      <img src="https://img.shields.io/badge/Owner-FFFF00?style=for-the-badge&logo=telegram&logoColor=black&labelColor=8A2BE2" alt="Owner">
    </a>
  </p>
  
  <!-- Bold social stats with high contrast -->
  <p>
    <a href="https://github.com/NoxxOP/ShrutiMusic/fork">
      <img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=FF1493&color=00CED1" alt="GitHub Forks">
    </a>
    <a href="https://github.com/NoxxOP/ShrutiMusic/stargazers">
      <img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=FF4500&color=32CD32" alt="GitHub Stars">
    </a>
    <a href="https://github.com/NoxxOP/ShrutiMusic/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/NoxxOP/ShrutiMusic?style=social&logo=github&labelColor=DC143C&color=FFD700" alt="GitHub Contributors">
    </a>
  </p>
</div>

---

## 🚀 Quick Deploy Options

<div align="center">
  
  ### 🔥 Deploy to Heroku
  <a href="https://dashboard.heroku.com/new?template=https://github.com/NoxxOP/ShrutiMusic">
    <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-FF0080?style=for-the-badge&logo=heroku&logoColor=white&labelColor=000080" width="280px" alt="Deploy to Heroku">
  </a>
  
  ### ☁️ Deploy to Render (Free)
  <a href="https://render.com/deploy?repo=https://github.com/NoxxOP/ShrutiMusic">
    <img src="https://img.shields.io/badge/Deploy%20To%20Render-00FF80?style=for-the-badge&logo=render&logoColor=black&labelColor=800080" width="280px" alt="Deploy to Render">
  </a>
  
  ### 🎵 Simple Music Bot
  <a href="https://github.com/NoxxOP/ShrutixMusic">
    <img src="https://img.shields.io/badge/Simple%20Music%20Bot-FF4000?style=for-the-badge&logo=github&logoColor=white&labelColor=008000" width="280px" alt="Simple Music Bot">
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
  <img src="https://img.shields.io/github/repo-size/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=FF1493&labelColor=000080" alt="Repo Size">
  <img src="https://img.shields.io/github/issues/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=FF4500&labelColor=008B8B" alt="Issues">
  <img src="https://img.shields.io/github/forks/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=32CD32&labelColor=8B0000" alt="Forks">
  <img src="https://img.shields.io/github/stars/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=FFD700&labelColor=4B0082" alt="Stars">
  <img src="https://img.shields.io/github/license/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=00CED1&labelColor=DC143C" alt="LICENSE">
  <img src="https://img.shields.io/github/last-commit/NoxxOP/ShrutiMusic?style=flat-square&logo=github&color=FF6347&labelColor=2F4F4F" alt="Last Commit">
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
    <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-FF0080?style=for-the-badge&logo=heroku&logoColor=white&labelColor=000080" width="250px" alt="Deploy to Heroku">
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
  <img src="https://img.shields.io/badge/Join%20Support%20Group-FF0040?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0080FF" alt="Support Group">
</a>

---

<img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-NoxxOP-FF1493?style=for-the-badge&logo=heart&labelColor=000080" alt="Made with love">

---

**🎵 Enjoy Streaming Music with Shruti Bot! 🎵**

</div>
