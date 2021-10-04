# URL to GDrive (Python Project)
Personal bot for URL to GDRIVE Uploader by Python

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


![GitHub Repo stars](https://img.shields.io/github/stars/rialms/url_to_gdrive?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/rialms/url_to_gdrive?color=green&style=flat)
![GitHub contributors](https://img.shields.io/github/contributors/rialms/url_to_gdrive?style=flat)
![GitHub watchers](https://img.shields.io/github/watchers/rialms/url_to_gdrive)
[![Channel](https://img.shields.io/badge/Subscribe%20Newsletter-!-red)](https://www.rokibulroni.com)
![rialms](https://cdn.jsdelivr.net/gh/rialms/resources@master/urlgdrive.gif)


# Google Drive Uploader Bot
# Here Is Live Version Of Bot  [uprialms_bot](http://telegram.dog/uprialms_bot)


# Update (04 OCT 2021)

- Teamdrive Support added 
- Fix Bugs

## Features
- [X] Telegram files support.
- [X] Direct Links support.
- [X] Custom Upload Folder.
- [X] TeamDrive Support.
- [X] Clone/Copy Google Drive Files.
- [X] Delete Google Drive Files.
- [X] Empty Google Drive trash.
- [X] youtube-dl support.
- [X] Facebook Supported
- [X] LK21 Supported
- [X] Docker Supported



## Deploying

### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/rialms/url_to_gdrive)

### Deploy on Railway

[![Deploy To Railway](https://railway.app/button.svg)](https://railway.app)

### Deploy on Qovery

[![Deploy to Qovery](https://img.shields.io/badge/Deploy-Qovery-6EC0D9.svg)](https://qovery.com)




### Installation
- Install required modules.
```sh
apt install -y git python3 ffmpeg
```
- Clone this git repository.
```sh 
git clone https://github.com/rialms/url_to_gdrive
```
- Change Directory
```sh 
cd GDUPLOAD_BOT2
```
- Install requirements with pip3
```sh 
pip3 install -r requirements.txt
```

### Configuration
**There are two Ways for configuring this bot.**
1. Add values to Environment Variables. And add a `ENV` var to Anything to enable it.
2. Add values in [config.py](./bot/config.py). And make sure that no `ENV` environment variables existing.

### Configuration Values
- `BOT_TOKEN` - Get it by contacting to [BotFather](https://t.me/botfather)
- `APP_ID` - Get it by creating app on [my.telegram.org](https://my.telegram.org/apps)
- `API_HASH` - Get it by creating app on [my.telegram.org](https://my.telegram.org/apps)
- `SUDO_USERS` - List of Telegram User ID of sudo users, seperated by space.
- `DATABASE_URL` - Postgres database url.
- `DOWNLOAD_DIRECTORY` - Custom path for downloads. Must end with a forward `/` slash. (Default to `./downloads/`)

### Deploy 
```sh 
python3 -m bot
```

### COMMANDS FOR THE BOT TO BE USED-
```
- start - useless command
- help - How to use me
- auth - Authorizing GDrive Account
- setfolder - Set Custom Upload Folder
- copy - Copy GDrive Files
- revoke - Revoke GDrive Account
- del - Delete GDrive Files
```
## Credits
- [breakdowns](https://github.com/breakdowns) for creating [slam-mirrorbot](https://github.com/breakdowns/slam-mirrorbot)


## Copyright & License
- Copyright (©) 2021 by [Rokibul Roni](https://www.rokibulroni.com)
- Licensed under the terms of the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE)
