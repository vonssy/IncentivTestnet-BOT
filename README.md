# 🚀 Incentiv Testnet BOT (Paid BOT)

> Automated onchain solution for efficient crypto farming and multi-account management

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/vonssy/IncentivTestnet-BOT.svg)](https://github.com/vonssy/IncentivTestnet-BOT/stargazers)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Proxy Recommendation](#proxy-recommendation)
- [Support](#support)
- [Contributing](#contributing)

## 🎯 Overview

Incentiv Testnet BOT is an automated tool designed to streamline onchain operations across multiple accounts. It provides seamless integration with Incentiv network and offers robust proxy support for enhanced security and reliability.

**🔗 Get Started:** [Register on Incentiv Testnet](https://testnet.incentiv.io/login?refCode=mUyNWvs8rzF6ssue38uepw)

> **Important:** Sign-Up With Passkey or New EVM Wallet.

## ✨ Features

<div align="left">
  <img src="images/features.png" alt="Feature Lists" width="500">
  <p><em>Features Of Incentiv Testnet BOT</em></p>
</div>

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- 💰 **Testnet Tokens Claims** - Automated testnet tokens claiming
- 📞 **Add Contact** - Automated add contact operations
- 📤 **Transfer Transactions** - Automated random transfer operations
- ⚡ **Swap Transactions** - Automated random swap operations
- 📦 **Bunlde Action Transactions** - Automated bundle action operations
- 👥 **Multi-Account Support** - Manage multiple accounts simultaneously

## 🏷️ Price
- **Price:** $5 in Cryptocurrency
- **Contact:** [Vonssy](https://t.me/vonssy_2nd)

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended
- **Compatible libraries:** web3, eth-account, eth-utils, eth-abi (see requirements.txt)
- **2captcha Key:** For automated captcha turnstile solving

## 🛠 Installation

### 1. Extract The Zip File

```bash
unzip IncentivTestnet-BOT
cd IncentivTestnet-BOT
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

### 3. Library Version Management

> ⚠️ **Important:** Ensure library versions match those specified in `requirements.txt`

**Check installed library version:**
```bash
pip show library_name
```

**Uninstall conflicting library:**
```bash
pip uninstall library_name
```

**Install specific library version:**
```bash
pip install library_name==version
```

## ⚙️ Configuration

### 2captcha Key Setup (Optional)

Create or edit `2captcha_key.txt` in the project directory:

```
your_2captcha_key
```

### Config Setup

Create or edit `.env` in the project directory:

```
# Transfer Amount
TCENT_TRANSFER_AMOUNT = 0.1
SMPL_TRANSFER_AMOUNT = 0.1
BULL_TRANSFER_AMOUNT = 0.1
FLIP_TRANSFER_AMOUNT = 0.1

# Swap Amount
TCENT_SWAP_AMOUNT = 0.1
SMPL_SWAP_AMOUNT = 0.1
BULL_SWAP_AMOUNT = 0.1
FLIP_SWAP_AMOUNT = 0.1

# Bundle Action Amount
BUNDLE_ACTION_AMOUNT = 0.1
```

### Account Setup

Create or edit `accounts.json` in the project directory:

```json
[
    {
        "private_key": "your_private_key_1"
    },
    {
        "private_key": "your_private_key_2"
    },
    {
        "mnemonic": "your_mnemonic_1"
    },
    {
        "mnemonic": "your_mnemonic_2"
    }
]
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

## 🚀 Usage

Run the bot using one of the following commands:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxy
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation

## 🌐 Proxy Recommendation

<div align="left">
  <img src="images/banner.png" alt="NST Proxy Banner" width="300">
</div>

For reliable multi-wallet automation and geo-restriction bypass, we recommend **Nstproxy**:

### Why Nstproxy?
- 💰 **Affordable pricing** starting from $0.1/GB
- 🌍 **Global coverage** with multiple locations
- 🔄 **Advanced rotation control**
- 🛡️ **Anti-ban technology**

### Get Started with Nstproxy
- 🔗 **Website:** [Nstproxy.com](https://www.nstproxy.com/?utm_source=vonssy)
- 💬 **Telegram:** [@nstproxy](https://t.me/nstproxy)
- 🎮 **Discord:** [Join Server](https://discord.gg/5jjWCAmvng)
- 📚 **GitHub:** [Nstproxy Repository](https://github.com/Nstproxy)

> 🎁 **Special Offer:** Use code `VONSSY` for **10% OFF** your first purchase!

## 💖 Support the Project

If this project has been helpful to you, consider supporting its development:

### Cryptocurrency Donations

| Network | Address |
|---------|---------|
| **EVM** | `0xe3c9ef9a39e9eb0582e5b147026cae524338521a` |
| **TON** | `UQBEFv58DC4FUrGqinBB5PAQS7TzXSm5c1Fn6nkiet8kmehB` |
| **SOL** | `E1xkaJYmAFEj28NPHKhjbf7GcvfdjKdvXju8d8AeSunf` |
| **SUI** | `0xa03726ecbbe00b31df6a61d7a59d02a7eedc39fe269532ceab97852a04cf3347` |

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. ⭐ **Star this repository** if you find it useful
2. 👥 **Follow** for updates on new features
3. 🐛 **Report issues** via GitHub Issues
4. 💡 **Suggest improvements** or new features
5. 🔧 **Submit pull requests** for bug fixes or enhancements

## 📞 Contact & Support

- **Developer:** vonssy
- **Issues:** [GitHub Issues](https://github.com/vonssy/IncentivTestnet-BOT/issues)
- **Discussions:** [GitHub Discussions](https://github.com/vonssy/IncentivTestnet-BOT/discussions)

---

<div align="center">

**Made with ❤️ by [vonssy](https://github.com/vonssy)**

*Thank you for using Incentiv Testnet BOT! Don't forget to ⭐ star this repository.*

</div>