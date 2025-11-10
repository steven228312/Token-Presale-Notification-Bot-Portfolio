# Token-Presale-Notification-Bot-Portfolio

## Overview
This project is a Token Presale Notification Bot that monitors blockchain events and sends real-time notifications to Telegram and Discord channels when users purchase tokens using ETH, USDT, USDC, or DAI.

<p align="center">
  <img src="https://github.com/imcrazysteven/Token-Presale-Notification-Bot-Portfolio/blob/main/public/TGBot.PNG" alt="Telegram Bot Notification" height="400">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/imcrazysteven/Token-Presale-Notification-Bot-Portfolio/blob/main/public/DiscordBot.PNG" alt="Discord Bot Notification" height="400">
</p>

## Features
- Real-time monitoring of token purchase events on the blockchain
- Automatic notifications to Telegram and Discord channels
- Support for multiple payment methods (ETH, USDT, USDC, DAI)
- Detailed transaction information including:
  - Investor wallet address
  - Purchase amount in original currency
  - Token amount received
  - USD equivalent value
  - Token price (when available)
  - Presale round information
  - Timestamp
  - Transaction hash with explorer link

## Notification Example
When a purchase is detected, the bot sends a formatted message like this:

```
🔔 New Purchase Detected!
👛 Investor: 0x123...abc
💰 Coin Amount: 1.234 ETH
🧰 Token Amount: 1000.00 QSE
💸 USD Amount: 2000.00 USD (💲 Token Price: 2.00 USD)
🚀 Round: 1
⏰ Timestamp: 2025-05-13 12:34:56
🔗 View Transaction
```

## Technical Details
The bot processes the following data from blockchain events:
- User wallet address
- Presale round number
- Purchase amount (with appropriate decimal handling for each currency)
- Currency type (ETH, USDT, USDC, DAI)
- Token amount received
- USD equivalent value
- Transaction timestamp
- Transaction hash

## Setup and Configuration
1. Clone this repository
2. Install dependencies: `npm install`
3. Configure your environment variables:
   - Blockchain provider URL
   - Contract address
   - Telegram bot token and chat ID
   - Discord bot token and channel ID
4. Start the bot: `npm start`

## Requirements
- Node.js
- Ethereum RPC provider (Infura, Alchemy, etc.)
- Telegram bot token and chat ID
- Discord bot token and channel ID

## License
This project is licensed under the [MIT License](./LICENSE).

## 📞 Contact & Support

- **Email**: [imcrazysteven143@gmail.com](mailto:imcrazysteven143@gmail.com)
- **GitHub**: [Steven (@imcrazysteven)](https://github.com/imcrazysteven)
- **Telegram**: [@imcrazysteven](https://t.me/imcrazysteven)
- **Twitter**: [@imcrazysteven](https://x.com/imcrazysteven)
- **Instagram**: [@imcrazysteven](https://www.instagram.com/imcrazysteven/)

---
