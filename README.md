# gdrive_uploader_tg
Personal bot for URL to GDRIVE Uploader by Python

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


![GitHub Repo stars](https://img.shields.io/github/stars/rialms/url_to_gdrive?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/rialms/url_to_gdrive?color=green&style=flat)
![GitHub contributors](https://img.shields.io/github/contributors/rialms/url_to_gdrive?style=flat)
![GitHub watchers](https://img.shields.io/github/watchers/rialms/url_to_gdrive)
[![Channel](https://img.shields.io/badge/Subscribe%20Newsletter-!-red)](https://www.rokibulroni.com)
[![rialms](https://cdn.jsdelivr.net/gh/rialms/resources@master/urlgdrive.gif)]


# Google Drive Uploader Bot
Here Is Live Version Of Bot  [uprialms_bot](http://telegram.dog/uprialms_bot)


# Update (04 OCT 2021)

- Teamdrive Support added 
- Fix Bugs


`Teamdrive is not for users You have to hardcode it ,`
`Wait for V2 bot This Bot don't have active development I will add User Specfic Teamdrive option`

# How can You Add Teamdrive
-  Replace `TEAMDRIVE_FOLDER_ID` and `TEAMDRIVE_ID` in [creds.py](./creds.py) 


### What Is this ?
 ```
   A Telegram Bot Written In Python 

 ```
 ### what can it do ?

 ```  
 It Can Upload Your Direct and Supported links into Google Drive.

 ```
### Install Module 
```
  sudo pip3 install -r requirements.txt
```
### Run This bot
```
python3 bot.py
```
 ### How Can We use It 
  - First authorise Bot Using `/auth` command Generate a Key and send it To bot .
  - Now You can Send Supported Link To Bot.

### Avalible Commands
  - `/start` =  Start Message
  - `/auth` = Authorise You
  - `/revoke` = Delete Your Saved credential
  - `/help` =  help Text

## Supported Links : 
 - Direct Link
 - Mega.nz Link
 - openload link (not avalibe anymore)
 - Dropbox Link

## Requirements
  - [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (Others type)  `Required`
  - Telegram Bot Token (Using BotFather)  `Required`
  - Openload ftp login and Key  `optional`
  - Mega Email and Password  `Optional`

 ` If You  wanna Change Openload Api and Mega Email Password You Can Change it From Given Path`
   - Mega => Plugins > TEXT.py
   - Openload  => Plugins > dlopenload.py

## Setup Your Own Bot
```
1. Create Your  [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (other type) and Download  Its json

2. Paste it In Bot Root Directroy  and Rename it "client_secrets.json"

3. Replace Your Bot Token in  [creds.py file](./creds.py)

4. Your Bot is Ready to Host. 
```
### You Can Use Heroku To host It.

 `Make sure You have Changed Your Bot Token and google client api Before Hosting It`


# TODO
  - Rename file while uploading
  - Adding Telegram File Support [ slow Download :( ]
  - Add  Youtube-dl
  - Fix openload support
  - Adding zippyshare , Mediafire , cloud mail  , Yandex disk ,Sourceforge {these are already written In PPE plugin you can use these from there}
  - Google Drive Direct Link Generator


### Licence
  - GPLv3

### Thanks To  :heart: 
  - [SpEcHiDe](https://github.com/SpEcHiDe)
