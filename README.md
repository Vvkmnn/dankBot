# coinBot

A script to [farm fake coins on the internet](http://dankmemer.lol/); forked from [this](https://github.com/spaceface777/DankMemerBotBot).

![](./screenshot.png)

### Features

-   [Concurrency](https://www.npmjs.com/package/concurrently) for active
    horizontal scaling
-   [Background Process](https://pm2.keymetrics.io/) for even fancier background
    management
-   Argument toggling for profiles
-   ++ `pls hunt` and possibly more later

### Disclaimer(s)

-   Using a user account as a bot is technically against Discord's ToS.
-   This is for eductional purposes / jokes only; if you get banned from
    anything, I told you so.
-   Also got a few accounts justifiably blacklisted for throttling while testing, so yeah; go easy.

### Donate

If you're having fun, donate to the [Dank Memer
team](https://www.patreon.com/dankmemerbot) for a cool bot.

### Usage

1.  Make a copy of `config.example.json` into `config.json`
2.  Edit `config.json` and put in your account's [Discord token](https://github.com/Tyrrrz/DiscordChatExporter/wiki/Obtaining-Token-and-Channel-IDs#how-to-get-a-user-token)
3.  Edit any other config params you wish to change in `index.js`, such as
    timeouts
4.  Run the script: `$ npm start`, or the concurrent version with `\$ npm run
    dev'
5.  Go to the Discord channel where you want your bot to work and try `$start` (or `$s`)
6.  ???
7.  Profit

![](./clown.jpg)
