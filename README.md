<div align="center">
	<br />
	<p>
		<img src="https://i.imgur.com/urpknNJ.png" width="546" alt="discord.js">
	</p>
	<br />
	<p>
		<a href="https://discord.gg/syntexscripts"><img src="https://img.shields.io/discord/1?color=5865F2&logo=discord&logoColor=white&label=Community" alt="Discord server" /></a>
		<a href="https://github.com/SyntexDev/Discord-Bot/commits/main"><img src="https://img.shields.io/github/last-commit/SyntexDev/Discord-Bot.svg?logo=github&logoColor=ffffff" alt="Last commit." /></a>
		<a href="https://github.com/SyntexDev/Discord-Bot/graphs/contributors"><img src="https://img.shields.io/github/contributors/SyntexDev/Discord-Bot.svg?maxAge=3600&logo=github&logoColor=fff&color=00c7be" alt="contributors" /></a>
	</p>
</div>

## About

This repository contains only .md files and folders to showcase the contents of this Discord bot. It is a [Node.js](https://nodejs.org/en) Discord bot that is easy to configure using the [Discord API](https://discord.com/developers/docs/intro).

## Features

- **Welcome Message** ([info][feature-welcomemessage]) - Sends a message to a selected channel welcoming new members to the server.
- **Auto-Role** ([info][feature-autorole]) - Automatically assigns a chosen role to new members when they join.
- **Tickets** - Easy to setup ticket system for support.
- **Custom Status** ([info][feature-customstatus]) - Displays the number of members currently in the server.
- **Moderation** - Provides important moderation commands to manage the server effectively

## Commands

- `/help` ([info][command-help]) - Displays a list of all available commands the bot can execute.
- `/serverinfo` ([info][command-serverinfo]) - Displays detailed information about the server, including member count and owner details and much more...
- `/suggestion` ([info][command-suggestion]) - Sends a suggestion made by a user to a specified channel.
- `/setupticketpanel` ([info][command-setupticketpanel]) - Sets up the ticket system in the channel where the message is sent.
- `/clear` ([info][command-clear]) - Clears a specified number of messages from the channel.
- `/ban` ([info][command-ban]) - Bans a user from the server.
- `/unban` ([info][command-unban]) - Unbans a previously banned user from the server.
- `/website` ([info][command-website]) - Sends a message with a button that directs users to the server’s website.
- `/wiki` ([info][command-wiki]) - Sends a message with a button that directs users to the server’s wiki.
- `/uptime` ([info][command-uptime]) - Displays the bot uptime.

## Links

- [Website][website]
- [Discord][discord]

## Contributing

This project is a one-person project, and I am using it to learn how things work. As this repository only contains .md files that showcase my progress, I am not accepting contributions at this time. 

The goal of this repository is to display my learning journey and the steps I am taking in developing a Discord bot using Node.js. I appreciate your understanding!

[website]: https://syntexscripts.nl
[discord]: https://discord.gg/syntexscripts

[info]: https://github.com/SyntexDev/discord.js/tree/main/packages/Discord-Bot

[command-help]: https://github.com/SyntexDev/discord.js/blob/main/commands/help.md
[command-clear]: https://github.com/SyntexDev/discord.js/blob/main/commands/clear.md
[command-ban]: https://github.com/SyntexDev/discord.js/blob/main/commands/ban.md
[command-serverinfo]: https://github.com/SyntexDev/discord.js/blob/main/commands/serverinfo.md
[command-setupticketpanel]: https://github.com/SyntexDev/discord.js/blob/main/commands/setupticketpanel.md
[command-suggestion]: https://github.com/SyntexDev/discord.js/blob/main/commands/suggestion.md
[command-unban]: https://github.com/SyntexDev/discord.js/blob/main/commands/unban.md
[command-uptime]: https://github.com/SyntexDev/discord.js/blob/main/commands/uptime.md
[command-website]: https://github.com/SyntexDev/discord.js/blob/main/commands/website.md
[command-wiki]: https://github.com/SyntexDev/discord.js/blob/main/commands/wiki.md

[feature-autorole]: https://github.com/SyntexDev/discord.js/blob/main/events/autorole.md
[feature-welcomemessage]: https://github.com/SyntexDev/discord.js/blob/main/events/welcomemessage.md
[feature-customstatus]: https://github.com/SyntexDev/discord.js/blob/main/events/customstatus.md
