Telegram Bot Boilerplate
======================

Telegram Bot Boilerplate based on Node.js and [Telegraf](https://github.com/telegraf/telegraf) framework. ES6/ES7 used. Easy deployment to [Zeit Now](https://zeit.co/now).

## Before you start
First rename `.env-sample` file to `.env` and fill in all necessary values.
```
BOT_TOKEN="<YOUR_BOT_API_TOKEN>"
USERNAME="<YOUR_BOT_USERNAME>"
WEBHOOK_URL="<THE_URL_OF_YOUR_WEBHOOK>"
PORT="<PORT>"
```

For deployment just create `.env.prod` with your production values. 

## Start your server
```
yarn install
yarn dev
```

## Deploy to Now
The hardest part.
```
yarn deploy
```

Pull Requests are welcomed :)
