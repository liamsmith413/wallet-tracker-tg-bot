# 🚀 Wallet Tracker  

**A powerful bot that tracks wallet activity on Solana, including SOL transfers, token transfers, and swaps, with instant notifications to your Telegram account.**  

---

## 📌 Features  
- ✅ **Real-time wallet monitoring** – Track incoming and outgoing transactions  
- ✅ **Token price tracking** – Get price updates for monitored assets  
- ✅ **Customizable filters** – Set alerts based on specific criteria  
- ✅ **Whale tracking** – Detect and analyze large transactions  
- ✅ **Copy trading** – Automatically replicate whale trades  
- ✅ **Multi-DEX support** – Compatible with **43+ Solana DEXs**  

---

## 💡 What This Bot Monitors  

### **🔄 Token Swap Tracking**  
Supports **all Solana DEXs**, including:  
- Jupiter  
- Raydium  
- Meteora  
- Orca  
- Pump.fun  
- 1DEX  
- ... and **37+ more**  

#### **Tracked Swap Data**  
- Swap token amount  
- Wallet address  
- Swap route details  
- InAmount & OutAmount  
- Conversion to **USD, PnL, and Market Cap**  

#### **Supported DEX Routes**  
| No | DEX | Route Key |
|:---:|---|---|
| 1 | Meteora DLMM | LBUZKhRxPF3XUpBCjp4YzTKgLccjZhTSDM9YuVaPwxo |
| 2 | Meteora | Eo7WjKq67rjJQSZxS6z3YkapzY3eMj6Xy8X5EQVn5UaB |
| 3 | Raydium | 675kPX9MHTjS2zt1qfr1NYHuzeLXfQM9H24wFSUt1Mp8 |
| 4 | Raydium CLMM | CAMMCzo5YL8w4VFF8KVHrK22GGUsp5VTaW7grrKgrWqK |
| 5 | Pump.fun | 6EF8rrecthR5Dkzon8Nwu78hRvfCKubJ14M5uBEwF6P |
| ... | ... | ... |

---

### **💰 SOL Transfer Tracking**  
- Transfer amount  
- Sender & recipient wallet addresses  
- Solana price at the time of transfer  
- Current market cap & supply  

### **📦 Token Transfer Tracking**  
- Transfer amount  
- Sender & recipient wallet addresses  
- Token info (Name, Symbol, Market Cap, Current Price)  
- Solana price & current supply  

---

## 🔐 **Security Features (Hash Bot Private)**  
- Encrypts private keys using **dual-variable hashing** stored in a **database and local file**  
- Even if the DB or local file is compromised, **hacking is impossible**  

---

## 🛠️ **Installation**  

###  **ENV File**  
```env
MAINNET_RPC=https://mainnet.helius-rpc.com/?api-key=your-api-key
DEVNET_RPC=https://devnet.helius-rpc.com/?api-key=your-api-key
GEYSER_RPC=wss://atlas-mainnet.helius-rpc.com/?api-key=your-api-key

TOKEN=your_telegram_bot_token

INTERVAL_FOR_TOKEN_MONITOR=your_interval_time
INTERVAL_FOR_EXPIRE=your_expiry_time

FEE_ADDR=your_wallet_address  # Wallet to receive tracking fees

DATABASE_URL=postgres://your_database_url
```

## 📞 Contact Me
If you have any questions, need support, or want to purchase the bot, reach out to me:
📱 Telegram: [T-rustdev](https://t.me/T_rustdev)

## 🛑 Disclaimer
🚨 Use this bot at your own risk. The developer is not responsible for any financial loss or misuse of this script. Make sure you understand how blockchain tracking and liquidity monitoring work before using this bot.