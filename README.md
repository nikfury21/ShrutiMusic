# 🎵 Shruti Music Bot 🎵

<!-- === Shruti Management Repo === -->
<div align="center">
  <svg width="100%" height="120" viewBox="0 0 600 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Shruti Music Bot Equalizer">
    <!-- Gradient glow -->
    <defs>
      <linearGradient id="eqGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"  stop-color="#FF6B6B"/>
        <stop offset="50%" stop-color="#9B59B6"/>
        <stop offset="100%" stop-color="#4ECDC4"/>
      </linearGradient>
      <filter id="softGlow">
        <feGaussianBlur stdDeviation="3.5" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <style>
        /* Animate up-down like DJ beat */
        @keyframes bounce {
          0%   { transform: scaleY(0.2); }
          25%  { transform: scaleY(0.9); }
          50%  { transform: scaleY(0.35); }
          75%  { transform: scaleY(0.75); }
          100% { transform: scaleY(0.2); }
        }
        .bar {
          transform-origin: 50% 100%;
          animation: bounce 1.2s infinite ease-in-out;
        }
        /* Make it look smooth on dark & light themes */
        .baseline { opacity: .18 }
      </style>
    </defs>

    <!-- Faint baseline line -->
    <rect class="baseline" x="0" y="100" width="600" height="2" fill="currentColor"/>

    <!-- Bars (auto-spaced) -->
    <!-- You can change BAR_COUNT by adding/removing <rect> elements. -->
    <!-- Each bar has a slight delay so the wave looks organic. -->
    <!-- Left half -->
    <g filter="url(#softGlow)" fill="url(#eqGrad)">
      <!-- 24 bars total; tweak height (h) & delay (anim-delay) for custom rhythm -->
      <!-- spacing = 20px, bar width = 10px -->
      <!-- indexes: -12 ... +11 (centered) -->
      <!-- Left side -->
      <rect class="bar" x="60"  y="20"  width="10" height="80" style="animation-delay:-0.00s"/>
      <rect class="bar" x="80"  y="34"  width="10" height="66" style="animation-delay:-0.10s"/>
      <rect class="bar" x="100" y="50"  width="10" height="50" style="animation-delay:-0.20s"/>
      <rect class="bar" x="120" y="34"  width="10" height="66" style="animation-delay:-0.30s"/>
      <rect class="bar" x="140" y="24"  width="10" height="76" style="animation-delay:-0.40s"/>
      <rect class="bar" x="160" y="12"  width="10" height="88" style="animation-delay:-0.50s"/>
      <rect class="bar" x="180" y="22"  width="10" height="78" style="animation-delay:-0.60s"/>
      <rect class="bar" x="200" y="36"  width="10" height="64" style="animation-delay:-0.70s"/>
      <rect class="bar" x="220" y="52"  width="10" height="48" style="animation-delay:-0.80s"/>
      <rect class="bar" x="240" y="36"  width="10" height="64" style="animation-delay:-0.90s"/>
      <rect class="bar" x="260" y="24"  width="10" height="76" style="animation-delay:-1.00s"/>
      <rect class="bar" x="280" y="14"  width="10" height="86" style="animation-delay:-1.10s"/>

      <!-- Right side (mirror-ish, with slight variation so it feels live) -->
      <rect class="bar" x="310" y="18"  width="10" height="82" style="animation-delay:-1.15s"/>
      <rect class="bar" x="330" y="30"  width="10" height="70" style="animation-delay:-1.05s"/>
      <rect class="bar" x="350" y="48"  width="10" height="52" style="animation-delay:-0.95s"/>
      <rect class="bar" x="370" y="32"  width="10" height="68" style="animation-delay:-0.85s"/>
      <rect class="bar" x="390" y="22"  width="10" height="78" style="animation-delay:-0.75s"/>
      <rect class="bar" x="410" y="12"  width="10" height="88" style="animation-delay:-0.65s"/>
      <rect class="bar" x="430" y="24"  width="10" height="76" style="animation-delay:-0.55s"/>
      <rect class="bar" x="450" y="38"  width="10" height="62" style="animation-delay:-0.45s"/>
      <rect class="bar" x="470" y="52"  width="10" height="48" style="animation-delay:-0.35s"/>
      <rect class="bar" x="490" y="36"  width="10" height="64" style="animation-delay:-0.25s"/>
      <rect class="bar" x="510" y="22"  width="10" height="78" style="animation-delay:-0.15s"/>
      <rect class="bar" x="530" y="16"  width="10" height="84" style="animation-delay:-0.05s"/>
    </g>
  </svg>
</div>
<!-- === /Musuc Mangement Repo === -->

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
