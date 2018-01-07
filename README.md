# Synology NAS Bot

🤖 A Telegram bot for Synology NAS

## Features

- Create download tasks

## Usage

1. [Deploy to Heroku](https://heroku.com/deploy?template=https://github.com/idealhack/synologynasbot)
1. Talk to [@BotFather](https://t.me/BotFather) on Telegram, create your bot.
1. Open your Heroku app **Settings** page, set these **Config Variables**:
    - `SYNOLOGY_NAS_BOT_TOKEN`: The bot’s API token, @BotFather just told you that
    - `SYNOLOGY_NAS_BOT_OWNER`: Your Telegram username, *A robot must obey the orders given it by its master*
    - `SYNOLOGY_NAS_BOT_URL`: Synology URL, should be this form: `https://id.synology.me:port/webapi/`
    - `SYNOLOGY_NAS_BOT_ACCOUNT`: Synology account name
    - `SYNOLOGY_NAS_BOT_PASSWORD`: Synology account password
1. Open your Heroku app **Resources** page, make sure the bot is running.
1. Talk to your lovely bot, it’s all yours.

## See also

Search and download movies by sending [@moviemagnetbot](https://t.me/moviemagnetbot) IMDb links.

## Troubleshooting

Open your Heroku app **View logs** page, see what’s going on.

## Contributing

Features? Bugs? Issues and Pull requests are welcome.
