# yourls-discord-bot
Integrating YOURLS inside a Discord bot.

# Install

It requires 3 npm packages;
* yourls
* discord.js
* valid-url

3 settings are needed to be set in the index.js file;
* yourlsURL - the URL of your YOURLS installation
* yourlsSECRET - your YOURLS secret signature token, found on /admin/tools.php
* discordTOKEN - your Discord application's bot token (https://discord.com/developers/applications)

discordSTATUS is optional, it defaults to "Shortening your URLs"

# Usage

Run it on your computer or external server by running the following command in Command Prompt (or Terminal, if you're using Linux);

`node index.js`

I recommend using it in a separate Discord server dedicated only to the bot, as it replies to **every** URL and image posted.

