# 🚀 Kite AI Ozone BOT — CDY Edition

A fully automated Python bot for interacting with the Kite AI Ozone testnet. Designed to streamline onboarding, staking, and daily tasks across multiple wallets with proxy support and 2Captcha integration.

> **Made by Cryptodai3 | Powered by YetiDAO**

---

## 📌 Project Link

🔗 **Kite AI Ozone**: [https://testnet.gokite.ai](https://testnet.gokite.ai)

---

## ⚙️ Features

- ✅ Auto Get Account Information  
- 🔁 Proxy Support (Free or Private)  
- 🔐 Multi-Wallet Support via `accounts.txt`  
- 💧 Auto Claim Faucets (requires 2Captcha key)  
- 💸 Auto Deposit KITE Token  
- 💸 Auto Withdraw Tokens  
- 🔄 Auto Stake / Unstake KITE Token  
- 🎁 Auto Claim Stake Rewards  
- 🧠 Auto Complete Daily Quiz  
- 🤖 Auto Interact with AI Agents  
- 🛡️ Auto Create Multisig Wallet  
- 🔀 Auto Make Random Swap  
- 🌉 Auto Make Random Bridge  
- 📈 Stats Tracking for all operations  

---

## 🌍 Proxy Recommendation

For multi-wallet automation, airdrop farming, or bypassing geo-restrictions:

🔗 https://www.nstproxy.com  
👉 Use code **YETIDAO** for **10% OFF**

- From $0.1/GB  
- Global coverage  
- Rotation control  
- Anti-ban tech  

---

🔐 2Captcha Integration
This bot uses [2Captcha](https://2captcha.com/)  to solve captchas automatically during faucet claims and other verification steps.
- Supports reCAPTCHA, image captchas, Cloudflare Turnstile, and more
- Fast solving speed and high accuracy
- API-ready for Python, JavaScript, PHP, and other languages
To use it, simply add your API key to 2captcha_key.txt.

---

## 📦 Requirements

- Python 3.9+  
- `pip` installed  
- 2Captcha API Key  
- Base Sepolia ETH  
- KITE Faucet Tokens  

---

## 🛠 Installation

### 1. Clone Repository

```bash
git clone https://github.com/cryptodai3/Kite-AI-PY-BOT.git
cd Kite-AI-PY-BOT
```

### 2. Set Up Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧩 Configuration

### ✅ `accounts.txt`

Put your private keys here (one per line):

```
0xabc123...
0xdef456...
```

### ✅ `2captcha_key.txt`

Place your 2Captcha API key here (one line):

```
your_2captcha_api_key
```

### ✅ `proxy.txt` (Optional)

Use one proxy per line in any of the following formats:

```
ip:port
http://ip:port
http://user:pass@ip:port
```

---

## ▶️ Running the Bot

```bash
python bot.py
```

The bot will prompt you to:

- Choose proxy mode:  
  `1` → Private Proxy  
  `2` → No Proxy  
- Choose auto-rotate proxies:  
  `y` or `n`

---

## 🧪 Onboarding Checklist

> Complete these steps before running the bot:

1. Register at Kite AI Ozone  
2. Sign in with a new EVM wallet  
3. Connect all social media  
4. Complete onboarding tasks  
5. Stake/Unstake KITE  
6. Interact with AI agents  
7. Claim faucet and rewards  

---

## 🛠 Troubleshooting

- Check Python version:

```bash
python --version
```

- If dependencies fail:

```bash
pip install package_name==version
```

- Common Errors:

  - **Invalid proxy format** → Fix your `proxy.txt`  
  - **2Captcha not working** → Confirm API key is valid  
  - **Wallet errors** → Check if private keys are valid  

---

## ☕ Buy Me a Coffee

- EVM: `0x3b94Ff1611773171E06047C0041099CccCFC609F`

---

## 🌐 Community

📢 Telegram Channel: [CryptoDai3](https://t.me/cryptodai3)  
🌍 By: [YetiDAO](https://t.me/yetidao)

---

## 🧠 License

This project is licensed under the MIT License.

---

> ⭐️ If this helped you, drop a star and share the repo! Let’s grow together.

---

