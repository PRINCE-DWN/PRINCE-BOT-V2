# 💫 ANURAG FACEBOOK CHAT BOT 💫  
### _The Official Rebranded Messenger Bot by Anurag Mishra_

---

## 🚀 Overview
**Anurag Facebook Chat Bot** is a powerful and fully rebranded Facebook Messenger chatbot developed using the **[`fca-anurag`](https://www.npmjs.com/package/fca-anurag)** package.  
It’s optimized, fast, modular, and fully customizable — built **by Anurag Mishra**, from the ground up for automation, fun, and control.

> 💻 100% Rebranded & Developed by **Anurag Mishra**  
> 🔥 Based on the original messenger-bot framework but completely rebuilt with **Anurag’s FCA**  
> ⚡ Tested and verified with 282 commands & 8 event modules

---

## 🧠 Project Information
| Property | Details |
|-----------|----------|
| **Project Name** | `anurag-bot-v2` |
| **Version** | `10.1.1` |
| **Main File** | `Anurag.js` |
| **Entry Point** | `index.js` |
| **FCA Package** | `fca-anurag@19.0.1` |
| **Author / Owner** | 🧑‍💻 **Anurag Mishra** |
| **Language** | JavaScript (Node.js) |
| **Database** | SQLite (via Sequelize) |
| **Timezone** | Asia/Kolkata |
| **Dashboard Port** | 8080 |

---

## 🧩 Project Structure
(rebranded from old structure) │   ├── commands/            # 282 modular command files │   │   ├── cache/ │   │   │   ├── checktuongtac/  # User activity tracking │   │   │   └── datlich.json    # Scheduled messages │   └── events/               # 8 event handler files ├── includes/                 # Core engine (controllers, handlers, listeners) │   ├── controllers/ │   ├── database/ │   ├── handle/ │   └── listen.js ├── languages/                # Language files (English, Vietnamese) ├── utils/                    # Utility helpers (loggers, formatters) ├── Anurag.js                 # Main bot process file ├── index.js                  # Entry point with Express & child process ├── config.json               # Global config ├── AnuragFca.json            # Custom FCA configuration ├── appstate.json             # Facebook login session └── package.json              # Dependencies and scripts
---

## ⚙️ Configuration
| Key | Description | Example |
|------|-------------|----------|
| **Bot Name** | Display name for the bot | `ANURAG💔INSIDE` |
| **Prefix** | Command prefix | `/` |
| **Language** | Default language | `en.lang` |
| **Timezone** | Region for scheduling | `Asia/Kolkata` |
| **Package** | Facebook Chat API | `fca-anurag` |
| **Owner** | Bot developer name | `Anurag Mishra` |

---

## 💎 Key Features
✅ Fully rebranded to **Anurag’s identity**  
✅ Facebook Messenger automation using **fca-anurag**  
✅ 282 custom command modules  
✅ 8 event handlers (joins, leaves, reactions, etc.)  
✅ SQLite database with Sequelize ORM  
✅ Daily/weekly interaction tracking (checktuongtac)  
✅ Scheduled message system (datlich)  
✅ Auto-restart monitoring system  
✅ Express web dashboard (port 8080)  
✅ Multi-language support  
✅ Beautiful colored console logging (chalk)  
✅ Simple setup & deploy anywhere  

---

## 🧰 Dependencies
- **fca-anurag** → Custom Facebook Chat API by Anurag Mishra  
- **express** → Web server for the dashboard  
- **sequelize** → ORM for SQLite  
- **axios** → HTTP client  
- **moment-timezone** → Time management  
- **chalk** → Console styling  
- **canvas** → Image generation for media commands  
- **body-parser, fs-extra, node-cron, pm2, etc.**  
> (See `package.json` for full dependency list)

---

## 🧾 How to Run the Bot
Run the bot using Node.js:

```bash
node index.js
