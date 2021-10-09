# TG-MusicPlayer
A Telegram Userbot to play songs in Telegram Voice Chats
It's made with [PyTgCalls](https://github.com/pytgcalls/pytgcalls) and [Pyrogram](https://github.com/pyrogram/pyrogram)


## Requirements
- Python 3.8+
- FFMPEG
- Nodejs v16+


## Deployment

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Local Deploy
1) Installing NodeJS
```curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs```
2) Installing FFMPEG and Git
```sudo apt-get install git ffmpeg -y```
3) Cloning the Repo
```git clone https://github.com/Lost-In-Dark/TG-MusicPlayer
cd TG-MusicPlayer```
4) Rename `example.env` to `.env` and Fill in the Environment Variables
5) Installing Requirements
```pip3 install -U -r requirements.txt```
6) Run the Bot
```python3 main.py```


## Environment Variables
- `API_ID`
- `API_HASH`
- `SESSION` - A Pyrogram String Session. Get one from [Here](https://replit.com/@dashezup/generate-pyrogram-session-string)
- `HNDLR` - Your Userbot Handler (Default is !)


## Commands and Usage
1) Start the Userbot, check if the Userbot is running by `!ping`.
2) Commands of this userbot are accessible to and can be used by the Account itself and it's Contacts.
3) Check `!help` for commands.


## Credits ✨
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Laky](https://github.com/Laky-64) for [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
