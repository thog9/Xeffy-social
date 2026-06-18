# Xeffy Bot Scripts 🚀

This collection of Python scripts automates task completion on the Xeffy platform — a Telegram-based Web3 ecosystem where users earn points by completing social tasks, daily quizzes, attendance check-ins, and Twitter/X account linking.

🔗 Register: [Xeffy](https://t.me/Xeffy_Bot?start=ref_921415493)

---

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Reads Telegram query data from `accounts.txt` to process multiple accounts in parallel.
- **Central Menu System**: Interactive menu for easy script selection via `main.py`.
- **Colorful CLI**: Uses `colorama` for visually appealing output with box-drawing borders and colored icons.
- **Asynchronous Execution**: Built with `asyncio` for efficient concurrent task processing.
- **Error Handling**: Comprehensive error catching with retry logic for API failures.
- **Bilingual Support**: Supports both English and Vietnamese output.
- **Proxy Support**: Supports HTTP, HTTPS, and SOCKS5 proxies via `proxy.txt`.

---

### Included Scripts

✨ **Task Bot** (`social.py`)

- ✅ Automatic task listing & submission
- ✅ Twitter Like, Retweet, Comment, Follow
- ✅ Telegram & Discord join verification
- ✅ Daily quiz answering with correct answer detection
- ✅ Smart period tracking — skips only same-period submissions
- ✅ Multi-account parallel execution
- ✅ Proxy support

✨ **Check-In** (`checkin.py`)

- ✅ Daily attendance check-in
- ✅ Checks already-checked status to avoid duplicates
- ✅ Points balance display
- ✅ Multi-account support
- ✅ Proxy support

✨ **Connect Twitter** (`connect.py`)

- ✅ X (Twitter) account linking via OAuth
- ✅ Checks existing connection status before flow
- ✅ Auto-opens browser for authentication
- ✅ Username display after successful connection
- ✅ Sequential account processing for OAuth flow
- ✅ Proxy support

✨ **Airdrop Bot** (`airdrop.py`)

- ✅ Automatic check Xeffy Airdrop registration status
- ✅ X (Twitter) follow verification
- ✅ Vault open & registration completion
- ✅ Display wallet, Discord, X handle info
- ✅ Support update/edit registration
- ✅ Proxy & multi-threading support

---

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- **Python 3.8+**
- **pip** (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt`
- **accounts.txt**: Add Telegram query data (one per line) — obtain via browser DevTools on the Xeffy mini app
- **proxy.txt** (optional): Add proxy addresses for network requests

---

## 📦 Installation

1. **Clone or download this repository:**
   ```sh
   git clone https://github.com/thog9/Xeffy-social.git
   cd Xeffy-social
   ```

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Prepare Input Files:**

   Create `accounts.txt` in the root directory with Telegram query data (one per line):
   ```
   query_id=AAFFr-s9AAAAA...
   query_id=AAFFr-s9AAAAA...
   ```

   Create `proxy.txt` (optional) — one proxy per line:
   ```
   http://user:pass@ip:port
   socks5://user:pass@ip:port
   ```

4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese / English).
   - Select the script you want to run.

**Language Selection:**
- Choose between Vietnamese (Tiếng Việt) and English.
- All scripts support bilingual output.

---

## 📁 Project Structure

```
Xeffy-social/
├── main.py                 # Central menu system
├── accounts.txt            # Telegram query data
├── proxy.txt               # Proxies (optional)
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── scripts/                # Individual scripts
    ├── social.py           # Task automation bot
    ├── checkin.py          # Daily check-in
    ├── connect.py          # Twitter OAuth connection
    └── airdrop.py          # Xeffy Airdrop registration bot

```

---

## 📨 Contact

Connect with us for support or updates:

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099)

---

## ☕ Support Us

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)
