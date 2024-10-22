## 🚀 Getting Started

To get started with the bot, follow these steps:

1. **Install Dependencies and Modules:**

   ```
   npm i; npm i user-agents cloudscraper axios colors p-limit https-proxy-agent
   ```

2. **Prepare Configuration Files:**

   You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜

```json
{
  "countdown": 300, //time to restarts all the accounts - count by seconds
  "ref": "6713068747", //referral
  "teamID": "20", //guild id
  "game2048": 10, // how many game do you want of it
  "gameStack": 10, // how many game do you want of it
  "countdown": 300, //countdown time by seconds
  "country_time": "vi-VN" // your country time format
}
```

### 2. `datas.txt` 🗂️

```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - This is temporarily not working, dont need to fill.

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐

```txt
http://user:password@host:port
http://user:password@host:port
http://user:password@host:port
```

💡 Usage:

    To run the bot, use the following command: node 1

🎇Enjoy!
