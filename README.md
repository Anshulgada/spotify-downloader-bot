
# Telegram Music Downloader
A Simple Music Downloader Bot For Telegram with Youtube Music, Spotify & Deezer Support.

<p align="center">
    <a href="https://python.org">
        <img src="http://forthebadge.com/images/badges/made-with-python.svg" alt="made-with-python">
    </a>
    <a href="https://GitHub.com/rozari0">
        <img src="http://ForTheBadge.com/images/badges/built-with-love.svg" alt="built-with-love">
    </a> <br>
    <img src="https://img.shields.io/github/license/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="LICENSE">
    <img src="https://img.shields.io/github/contributors/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="Contributors">
    <img src="https://img.shields.io/github/repo-size/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="Repository Size"> <br>
    <img src="https://img.shields.io/badge/python-3.9-green?style=for-the-badge&logo=appveyor" alt="Python Version">
    <img src="https://img.shields.io/github/issues/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="Issues">
    <img src="https://img.shields.io/github/forks/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="Forks">
    <img src="https://img.shields.io/github/stars/rozari0/MusicDownloader?style=for-the-badge&logo=appveyor" alt="Stars">
</p>



## Demo

[You Need Music?](https://t.me/NeedMusicRobot)


## Deployment

To deploy this project run

### Easy Way (Local)
```bash
  cp sample_config.env config.env
  pip3 install -r requirements.txt
  python3 -m mbot
```

### Docker
```bash
  cp sample_config.env config.env
  docker build . -t musicbot
  docker run musicbot
```
### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/rozari0/MusicDownloader/)

# Variables

`API_ID`  
`API_HASH`api Id and hash get it from  [Telegram](https://my.telegram.org)
`BOT_TOKEN`get it from [@BotFather](https://t.me/BotFather)
`SPOTIPY_CLIENT_ID` &
`SPOTIPY_CLIENT_SECRET`get it from [Spotify](https://developers.spotify.com)
`LOG_GROUP` &
`AUTH_CHATS`Get IDs add a group management bot and type /id
`ARQ_API_KEY`Get it from @ARQRobot and paste [here](https://github.com/Masterolic/Spotify-Downloader/blob/38dcc1788a55542ae6ef686f78e644f312faefde/mbot/__init__.py#L61)
`BUG`put your bug log group id there [click here](https://github.com/Masterolic/Spotify-Downloader/blob/9b718abd57474b9e8d1f0bdade92aae2da6e2e53/mbot/utils/mainhelper.py#L29)

## Environment Variables

To run this project, you will need to add the following environment variables to your config.env file

`API_ID`
`API_HASH`
`BOT_TOKEN`
`SPOTIPY_CLIENT_ID`
`SPOTIPY_CLIENT_SECRET`
`UPDATES_CHANNEL`
`LOG_GROUP`
`DATABASE_URL`
`AUTH_CHATS`

# DEPLOY

Add your variables in [config.env](https://github.com/Masterolic/Spotify-repo/blob/4d98480ec837325d38eedd20886a748c5d6fa598/config.env#L12)

*Step 1* ⚙️ `apt update && apt upgrade && apt install ffmpeg -y `

*Step 2* ⚙️ `pip install --upgrade pip && pip install -r requirements.text`

*Step 3* ⚙️ `python3 -m mbot`

## License

[MIT](https://choosealicense.com/licenses/mit/)

