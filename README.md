# 🐓 FrancRun

> A Telegram Mini App game built on the $FRANC token ecosystem — *Francis Le Coq*

[![Telegram](https://img.shields.io/badge/Play-Telegram-blue?logo=telegram)](https://t.me/FrancisLeCoqBot/FrancRun)
[![Solana](https://img.shields.io/badge/Powered%20by-Solana-purple?logo=solana)](https://solana.com)

---

## 🎮 Play Now

**[▶ Launch FrancRun on Telegram](https://t.me/FrancisLeCoqBot/FrancRun)**

---

## 📖 How to Play

Collect golden eggs and dodge enemies across **11 levels** of increasing difficulty.

| Milestone | Effect |
|---|---|
| 30 eggs | +1 level |
| Level 4 | 🔫 Pistol unlocked |
| Level 7 | 💥 Screen clear + breather |
| Level 11 | 💀 Sudden Death — fight to the end! |

**Controls:**
- 📱 **Mobile** — Drag to move or use the joystick (toggle bottom-right)
- 🖥️ **Desktop** — Move your mouse

---

## 💎 $FRANC Holder Bonuses

Hold [$FRANC](https://solana.com) in your Solana wallet to unlock exclusive in-game advantages:

| Benefit | Without $FRANC | With $FRANC |
|---|---|---|
| ❤️ Lives | 1 | **10** |
| 🔫 Weapon | Basic | **Triple shot** |
| 💀 Sudden Death lives | ❌ | ❌ |

> Connect your wallet via [@FrancisLeCoqBot](https://t.me/FrancisLeCoqBot) or the in-game wallet button.

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| 🎮 Game | Vanilla HTML5 Canvas + JavaScript |
| 📱 Platform | Telegram Mini App (WebApp API) |
| ☁️ Backend | Supabase Edge Functions (Deno) |
| 🔗 Blockchain | Solana RPC — $FRANC token detection |
| 🤖 Bot | @FrancisLeCoqBot (Telegram Bot API) |
| 🌐 Hosting | GitHub Pages |

---

## 🗂️ Project Structure

```
FrancRun/
├── index.html          # Game (HTML5 Canvas, all-in-one)
├── coq_pilote.png      # Player sprite
├── piece_1f.png        # Coin sprite
└── README.md

Wallet/ (separate repo)
└── connect-wallet.html # Universal wallet connection page

Backend (Supabase Edge Functions)
├── bot-handler/        # Telegram webhook — all commands
├── check-franc/        # Verify $FRANC balance
├── link-wallet/        # Link Solana address
└── save-score/         # Leaderboard
```

---

## 🤖 Bot Commands

| Command | Description |
|---|---|
| `/connect` | Link your Solana wallet |
| `/disconnect` | Unlink your wallet |
| `/status` | Check your $FRANC balance |
| `/play` | Launch FrancRun |
| `/setup` | Post pinned welcome message (admin) |
| `/setup1` | Post pinned wallet message (admin) |
| `/setup2` | Post pinned FrancRun message (admin) |

---

## 🔐 Wallet Connection

The wallet connection is handled via a dedicated Mini App:

**[t.me/FrancisLeCoqBot/wallet](https://t.me/FrancisLeCoqBot/wallet)**

- Paste your Solana public address
- $FRANC balance is checked in real-time
- One wallet per Telegram account
- Bonuses apply instantly across all games

---

## 🏆 Leaderboard

Top 10 scores are tracked globally via Supabase.  
$FRANC holders are identified with a 💎 badge.

---

## 🌐 Community

| Platform | Link |
|---|---|
| 🤖 Telegram Bot | [@FrancisLeCoqBot](https://t.me/FrancisLeCoqBot) |
| 🐔 The Chicken Coop | [Join the group](https://t.me/+your_invite_link) |
| 🎮 Play FrancRun | [Launch game](https://t.me/FrancisLeCoqBot/FrancRun) |

---

## 📄 License

MIT — feel free to fork and build your own token-gated Telegram game!

---

*Made with ❤️ by Francis Le Coq — powered by $FRANC on Solana*
