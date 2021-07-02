# twitch_bot
A bot that counts!!!

Simple Twitch bot template with three commands:

 * `!count`: shows the `count` from [`data.json`](./data.json)
 * `!add NUMBER`: adds `NUMBER` to `count` in  [`data.json`](./data.json)
 * `!sub NUMBER`: subtracts `NUMBER` from `count` in  [`data.json`](./data.json)
 *

TO ADD ENV FILES!!


Open `.env` and insert the following fields:

| Field        | Explanation                                                           |
|--------------|-----------------------------------------------------------------------|
| `TMI_TOKEN`  | OAuth Token with `oauth:` as a prefix                                 |
| `CLIENT_ID`  | Client ID obtained from Twitch's Developer site                       |
| `BOT_NICK`   | Twitch name of the Bot                                                | 
| `BOT_PREFIX` | Prefix for commands the bot should listen to (set to `!` per default) |
| `CHANNEL`    | The name of the your Twitch channel you want the bot to run at        |


To Start Bot:

```
python3 bot.py
