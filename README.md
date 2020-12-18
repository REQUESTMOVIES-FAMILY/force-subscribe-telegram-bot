# Introduction
**A Telegram Bot to force users to join a specific channel before sending messages in a group.**
- Find it on Telegram as [[RM] Promoter](https://t.me/ForceSubscribeBot)

## Todo
- [ ] Add multiple channels support
- [X] Configure different groups with different channels
- [X] Clean messages after completion
- [ ] LOGGER support.

## Deploy
### You can tap the Deploy To Heroku button below to deploy straight to Heroku!
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/REQUESTMOVIES-FAMILY/force-subscribe-telegram-bot)


### Installation
- Clone this repo
```
git clone https://github.com/REQUESTMOVIES-FAMILY/force-subscribe-telegram-bot
```
- Change directory
```
cd force-subscribe-telegram-bot
```
- Install requirements
```
pip3 install -r requirements.txt
```

### Configuration
Add [APP_ID](https://my.telegram.org/apps), [API_HASH](https://my.telegram.org/apps), [BOT_TOKEN](https://t.me/botfather) in [Config.py](Config.py) or in Environment Variables.

### Deploying
- Run bot.py
```
python3 bot.py
```

## Thanks to
- [PyroGram](https://PyroGram.org)
- for helping.
