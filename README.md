# 🚀 Kite AI Automation Bot - CDY Edition

A fully automated Python bot for interacting with Kite AI's incentivized testnet. This bot simplifies your daily Kite AI tasks and boosts your airdrop farming by automating multiple activities across multiple accounts.

> **Made by Cryptodai3 | Powered by YetiDAO**

---

## 📌 Project Link

🔗 **Kite AI Testnet**: [https://testnet.gokite.ai](https://testnet.gokite.ai/?referralCode=ODMG4EWE)

---

## ⚙️ Features

- ✅ Auto Account Login & Info Retrieval  
- 🔁 Proxy Support (Free or Private)  
- 🔐 Multi-Wallet Support via `accounts.txt`  
- 💧 Auto Claim KITE Faucet (via 2captcha)  
- 🤖 Auto Daily Quiz  
- 💸 Auto Stake & Unstake KITE  
- 🧠 Auto Interact with AI Agents  
- 🌉 Random Bridge Transactions  
- 🔁 Proxy Rotation for Invalid IPs  
- 📈 Stats Tracking for all operations  

---

## 📦 Requirements

- Python 3.9+  
- `pip` installed  
- 2captcha API Key (optional but needed for faucet)
- Base Sepolia ETH  
- KITE Faucet Tokens

---

## 🛠 Installation

1. **Clone Repository**
```bash
git clone https://github.com/cryptodai3/Kite-AI-PY-BOT.git
````
```bash
cd Kite-AI-PY-BOT
````

2. **Install Dependencies**

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

Place your 2captcha API key here (one line):

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

* Choose proxy mode:
  `1` → Proxyscrape Free Proxy
  `2` → Private Proxy
  `3` → No Proxy
* Choose auto-rotate proxies:
  `y` or `n`

---

## 🧪 Project Tasks Overview

> Complete these steps **before running the bot** to get the most out of the testnet:

1. Register here → [Kite AI Testnet](https://testnet.gokite.ai?referralCode=ODMG4EWE)
2. Sign in with **EVM Wallet**
3. Connect all social media
4. Complete missions & agent tasks
5. Interact with Kite Agents
6. Stake/Unstake KITE token
7. Complete Quizzes

---

## 🛠 Troubleshooting

* If installation fails:

  * Check Python version (`python --version`)
  * Ensure all dependencies match versions in `requirements.txt`
  * Use:

    ```bash
    pip install package_name==version
    ```

* Common Errors:

  * **Invalid proxy format** → Fix your `proxy.txt`
  * **2captcha not working** → Confirm API key is valid
  * **Wallet errors** → Check if private keys are valid

---

## ☕ Donate & Support

* **EVM:** `0x3b94Ff1611773171E06047C0041099CccCFC609F`

---

## 🌐 Community

Join the movement and stay updated:

📢 Telegram Channel: [CryptoDai3](https://t.me/cryptodai3)
🌍 By: [YetiDAO](https://t.me/yetidao)

---

## 🧠 License

This project is licensed under the MIT License.

---

> ⭐️ **If this helped you, drop a star and share the repo! Let's grow together.**
