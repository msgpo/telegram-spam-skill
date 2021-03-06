# <img src='https://raw.githack.com/FortAwesome/Font-Awesome/master/svgs/brands/telegram-plane.svg' card_color='#0088CC' width='50' height='50' style='vertical-align:bottom'/> Telegram Spam Skill
A skill to connect a telegram bot to MyCroft.
This will send you everything that is happening, if you are looking for the "normal" telegram skill -> https://github.com/luke5sky/telegram-skill

## About 

You need to create a telegram bot (via BotFather) and save the Bot Token, your ChatID and your MyCroft Device name on home.mycroft.ai under skill settings.
After this restart your MyCroft Unit.
You can now commmunicate with your MyCroft Unit via this bot.

Settings:
- BOT TOKEN (MANDATORY): Your bot token you got from BotFather
- MYCROFT DEVICE NAME (MANDATORY): Your Device name you configured on home.mycroft.ai - Devices - Registered Devices
- USERNAME (OPTIONAL): You do not need to put anything here, the skill does not use this field. It is only for yourself to know which Chat ID belongs to whom
- CHAT ID (MANDATORY): You will get your Chat ID from the Telegram-Skill if you have configured BOT TOKEN (first field) and MYCROFT DEVICE NAME, saved and then write anything to the bot.

Detailed HowTo:

- Install this skill on your Mycroft Device

- Create a telegram bot:
Open Telegram App on your smartphone, click on the search symbol in the upper right corner<br/>
Search for BotFather and click on it<br/>
Now type /newbot hit enter<br/>
Botfather should reply with: Alright, a new bot. How are we going to call it? please chosse a name for your bot.<br/>
Give your bot a displayname like Mycroft<br/>
Botfather should reply with: Good. Now let's choose a username for your bot. It must end in bot. Like this, for example: TetrisBot or tetris-bot.<br/>
Give your bot unique username like lukesmycroftbot<br/>
Botfather should now give you your token for this bot<br/>
Save this token and don't post it online or send it to people, safety first!<br/>

Telegram documentation on botfather: https://core.telegram.org/bots#6-botfather

- Go to home.mycroft.ai - skills and search for the telegram-skills settings

- Copy/paste your token botfather gave you in the field BOT TOKEN (MANDATORY)

- Copy/paste your device name from home.mycroft.ai - devices in MYCROFT DEVICE NAME (MANDATORY)

- SAVE and wait till the settings are synced to your Mycroft Unit (or reboot your device to trigger the sync)

- Open Telegram App on your smartphone and search (upper right corner) for your bot (username or displayname) click on it and write test or hello to your bot
  It should respond with: This is your ChatID: YOURCHATID

- Copy/paste this under CHAT ID (MANDATORY)
 
- reboot your device to trigger the sync

- Your bot should send you this welcome message: Telegram-Skill on Mycroft Unit YOURUNIT is loaded and ready to use

## Credits 
Lukas Gangel (@luke5sky)



## Category
IoT
**Productivity**

## Tags
#messenger
#bot
#telegram-bot
