[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# Discord Bot Heroku
A dead simple one-click [Discord](https://discordapp.com) bot deployed on [Heroku](https://heroku.com). Based on [discord.py rewrite](https://github.com/Rapptz/discord.py/tree/rewrite).

## How to Bot

1. Create an app at https://discordapp.com/developers. You'll need a discord account, obviously.
2. Create a bot for the app.
3. [Deploy this repository to Heroku](https://heroku.com/deploy), then insert the bot token.
4. Give your app a name, assign dynos, and profit.

## Caveats

* You'll need a credit card to get enough dynos to run for the entire month unless you are grandfathered in from running an app on Heroku in 2016.
* Your bot will sleep after [30 mins of inactivity](https://www.heroku.com/pricing#dyno-comparison).
* No voicechat or music support. (to be added later)

Want to run 24/7 without the above three caveats? Get a [VPS](https://en.wikipedia.org/wiki/Virtual_private_server). I recommend [AWS](https://aws.amazon.com), [GCP](https://cloud.google.com), [DigitalOcean](https://m.do.co/c/6906a2f19dea) or [Linode](https://www.linode.com/?r=5b3797e6db42b0d37d9a1017f98a48da38185644).

### Contribute

1. Fork this repo.
2. Make your changes
3. Submit a pull request.

### License

MIT
