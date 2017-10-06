# Steps to Create a bot
```
mkdir git-bot
cd git-bin/
mkdir claudia
cd claudia/
npm init
npm install claudia -g
npm install claudia-bot-builder -S
nano bot.js
claudia create --region us-east-1 --api-module bot --configure-fb-bot
```

# Create another bot for Telegram
`claudia update --region us-central-1 --api-module bot --configure-telegram-bot`
