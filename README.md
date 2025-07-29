
# 7DTD Discord Bot

A Discord bot for 7 Days to Die servers. Features:

✅ Bidirectional chat relay (Discord ↔ Server)  
✅ Role & channel-based command restrictions  
✅ Telnet integration for server control  

## Setup

1. Install Python 3.9+
2. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
3. Fill in `config.json` with your server and Discord info.
4. Run the bot:  
   ```
   python bot.py
   ```

## Commands

- `/status` – Show server status & players  
- `/say <msg>` – Send message to in-game chat  
- `/restart` – Restart server  

Commands are restricted by channel & role.

## License
This bot is provided by CALLUMGAMES for personal use with 7 Days to Die servers. Modifying, redistributing, or using the code without permission is strictly prohibited. See [LICENSE](./LICENSE) for full details.

