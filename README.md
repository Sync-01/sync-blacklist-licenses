# 🚀 Blacklist Checker Script

## 📌 About
This script is designed to check whether a user is blacklisted based on their license and send notifications via a Discord webhook. If a user is blacklisted, they will receive a predefined message.

## 🛠️ Features
- ✅ Webhook integration to notify a Discord channel.
- 🔒 Blacklist system to block specific licenses.
- ⚡ Lightweight and easy to use.

## 📂 Configuration
Modify the `config.json` file to set up the script according to your needs:

```json
{
  "webhook_url": "https://discord.com/api/webhooks/your_webhook_url",
  "blacklisted_licenses": [
      "license:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
      "license:yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy"
  ],
  "blacklist_message": "You Are Blacklisted From This Server By Zedk."
}
```

### 🔧 Parameters:
- `webhook_url`: The URL of the Discord webhook where notifications will be sent.
- `blacklisted_licenses`: A list of blocked licenses.
- `blacklist_message`: The message displayed to blacklisted users.

## 🚀 Usage
1. Ensure you have the correct dependencies installed.
2. Configure the `config.json` file with your webhook and blacklisted licenses.
3. Run the script and let it check for blacklisted users!

## 📜 License
This script is for personal use. Modification and redistribution should follow the original author's terms.

---
**Developed by Sync**
