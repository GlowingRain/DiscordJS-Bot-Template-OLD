# Discord.JS Bot Template

An easy to-understand template for making Discord.JS bots. Built by following the **[official guide](https://discordjs.guide/)** of Discord.JS.

## Requirements

- [git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/es/)
- A "good" understanding of JavaScript
- And of course, [Discord.JS](https://discord.js.org/)

## Features

* Event Handler.
* Command Handler.
* Custom logger using chalk and moment.
* Tools & errors modules, such as CMDError, noPerms, etc.
* **Dinamically executed commands**

## How-To

1. Clone the repository by doing in a terminal `git clone https://github.com/GlowingRain/DiscordJS-Bot-Template.git`
2. After cloning, do `npm install`
3. Create a file named `config.json` and copy-paste this inside it:

```json
{
    "owner_ID": "",
    "prefix": "",
    "token": "",
    "version": ""
}
```

You can locate your bot's token going to the [Discord Developer Portal](https://discordapp.com/developers/applications/me). Most like everything you will need for now.

As you might already noticed by browsing files over the **`storage`** folder, you have a `channels.json` file. It holds every [Channel Id](https://discord.js.org/#/docs/main/stable/class/GuildChannel?scrollTo=id) that the bot is going to need to perform and/or complete actions such as **_welcoming new users_** and so on. You can add more channels as you wish.

**That's it! You're good to go now, I'll be adding further code whenever I feel like doing it, stay updated if you want to.**

## Reminder 

If you're going to publish your work on Github or somewhere else, please, **NEVER** but **NEVER** publish the `config.json` file **if you have the bot's token there**. Add a `.gitignore` to your proyect instead.

## To-Do

* [x] Event Handler.
* [x] Command Handler.
* [ ] Basic permission level.
* [ ] Help command with categories.

## License

MIT
