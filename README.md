# MC Aternos discord bot
## Overview
i am assuming if you are gonna use this repo , you already have a mc aternos server or you know about mc aternos.
This is a discord bot which can start or stop your minecraft aternos server by using customisable commands.
The main purpose behind making this script was so that my friends can start or stop our smp minecraft server right from discord without me logging into my aternos account and starting it manually everytime.

## Installation

>intended to be used on vps but its your choice. 

- `git clone https://github.com/Pyr0sec/mc-aternos-discord.git`
- `cd mc-aternos-discord`
- `pip install -r requirements.txt`

Now, the installation is done we need to setup a bot account in discord developer portal so you can connect this code with discord.

## Setting up a bot account in discord developer portal
Instead of me explaining it here in text you should watch this portion of the video, which guides you in depth on how to setup a bot account in discord developer portal.

URL: https://www.youtube.com/watch?v=fU-kWx-OYvE?t=68

Timestamp: (1:08 to 4:39)

Now that this is done, we need to configure the code according to our details before actually starting the bot.

## Configuration
- Now, open the code in an editor of your choice (preferably one which shows line number like sublime text or you can fork this repo and use the inbuilt github editor)
- In **line 6**, replace `paste-your-token-here` with your token which you copied from discord developer portal.
- In **line 10** replace `your-aternos-username` with your aternos account username and `your-aternos-password` with your aternos account password.
- In **line 40** replace `yourservername.aternos.me` with your aternos server name which you can find in your aternos dashboard page.
	eg: `testserver.aternos.me`
- In **line 45** replace `yourservername.aternos.me:serverport` with your aternos server name with the port number which you can find in your aternos dashboard.
	eg:`testserver.aternos.me:62810`

## Commands
>Note(VERY IMPORTANT): this bot will only work in a channel with the name `bot-cmnds` , yea so you need to make a new channel named `bot-cmnds` and send commands there only.
>sorry for this but i made this script specifically for my server and i am too lazy to change it now so you can customize it your way if u want.

- `?server_start` --> to start minecraft server 
- `?server_stop` --> to stop minecraft server

## Deploy on Heroku (free ($0/month) dyno)
Best solution might be to host this bot on herokuapp. so you need to follow these steps.
- Fork this repository.
- Complete the [Setting up a bot account in discord developer portal](#setting-up-a-bot-account-in-discord-developer-portal) and [Configuration](#configuration) steps.
- [Sign up to Heroku](https://signup.heroku.com/) and [log in to your account](https://id.heroku.com/login).
- Click the button below and follow the instructions.

## Screenshots
![Pasted image 20220609232650](https://user-images.githubusercontent.com/74669749/172929877-c63d9474-d569-4757-b0b3-0f5445a39474.png)

![Pasted image 20220609233552](https://user-images.githubusercontent.com/74669749/172929923-153affbb-5041-45c5-90ce-32e3881aaef9.png)

> Note: when you send the command `?server_start` it may take a few minutes for the server to actually start because aternos is a free service so it usually puts you up in a queue and then you have 5 minutes to join until the server stops automatically.
> so you should usually wait for 2-3 minutes after the command and then join your minecraft server.

Hope this helps ❤

open to any suggestions 😊

just message me @ [Twitter Pyr0sec](https://twitter.com/Pyr0sec) 🐤
