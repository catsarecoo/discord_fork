---
description: Powerful multifunction bot Yuigahama
name: Yuigahama - 由比ヶ浜結衣
---

# YuigahamaBot v1.0.3

# Language  
Japanese(日本語): `yui!conf set language ja-JP`  
English(英語): `yui!conf set language en-US`


# AutoRole
Give the designated role when the member joined.

# Join and Quit log
Logs to specific channel when user joins / leaves. It is also possible to convey a message.

# Many commands
There are several commands that will entertain you.

| Command Name          | Aliases                                                      |         Category         | Description                                           | Extended Help                                                | Usage                                                        |
| :-------------------- | ------------------------------------------------------------ | :----------------------: | ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| conf                  |                                                              |     Admin - General      | Define per-guild settings.                            |                                                              | `yui!conf <set|show|remove|reset> (key:key) (value:value) [...]` |
| help                  | commands                                                     | General - Chat Bot Info  | Display help for a command.                           |                                                              | `yui!《help|commands》 (Command:command)`                    |
| info                  | details, what                                                | General - Chat Bot Info  | Provides some information about this bot.             |                                                              | `yui!《info|details|what》`                                  |
| invite                |                                                              | General - Chat Bot Info  | Displays the join guild link of the bot.              |                                                              | `yui!invite`                                                 |
| ping                  |                                                              | General - Chat Bot Info  | Runs a connection test to Discord.                    |                                                              | `yui!ping`                                                   |
| stats                 |                                                              | General - Chat Bot Info  | Provides some details about the bot and stats.        |                                                              | `yui!stats`                                                  |
| botinfo               |                                                              | General - Chat Bot Info  | Shows the environment in which the bot is running.    |                                                              | `yui!botinfo`                                                |
| donate                |                                                              | General - Chat Bot Info  | Send donation page URL.                               |                                                              | `yui!donate`                                                 |
| userconf              |                                                              | General - User Settings  | Define per-user settings.                             |                                                              | `yui!userconf <set|show|remove|reset> (key:key) (value:value) [...]` |
| avatar                |                                                              |      User - General      | Send avatar images of yourself or other users.        |                                                              | `yui!avatar [user:user]`                                     |
| discordjs             |                                                              |  DevTools - JavaScript   | Search the document of Discord.js.                    |                                                              | `yui!《discordjs|djs|djsdocs》 <commando|rpc|main:default> <query:string> [branch:string]` |
| pocketmine            | pocketmine-mp, pocketminemp, pmmp                            | DevTools - PocketMine-MP | View the details of the latest PocketMine-MP release. |                                                              | `yui!《pocketmine|pmmp|pocketmine-mp|pocketminemp》`         |
| poggit                |                                                              | DevTools - PocketMine-MP | Search for PocketMine-MP plugins from Poggit.         |                                                              | `yui!poggit <query:...string>`                               |
| fortnite              |                                                              |     Game - Fortnite      | You can check various information about Fortnite.     | Older versions of plug-ins may appear in the search results. be careful. | `yui!fortnite <news|challenges>`                             |
| minecraft-namehistory | mc-namehistory, mc-nh, minecraftnamehistory, mcnamehistory, mcnh |     Game - Minecraft     | Send player name history.                             |                                                              | `yui!《minecraft-namehistory|mc-namehistory|mc-nh|minecraftnamehistory|mcnamehistory|mcnh》 <name:string>` |
| minecraft-uuid        | mc-uuid, mcuuid, minecraftuuid                               |     Game - Minecraft     | Get UUID from player name.                            |                                                              | `yui!《minecraft-uuid|mc-uuid|minecraftuuid|mcuuid》 <name:string>` |
| channelinfo           |                                                              |   Guild - Information    | You can check the channel information.                | Only text and voice channels can be checked.                 | `yui!channelinfo <channel:channel>`                          |
| guildinfo             | serverinfo                                                   |   Guild - Information    | You can check the information of the server.          |                                                              | `yui!《guildinfo|serverinfo》`                               |
| memberinfo            |                                                              |   Guild - Information    | You can check the information of server members.      |                                                              | `yui!memberinfo <member:member>`                             |
| ban                   |                                                              |     Guild - Manager      | Ban members from the server.                          |                                                              | `yui!ban <user:user> [days:int{1,7}] [reason:...string]`     |
| kick                  |                                                              |     Guild - Manager      | Kick member from the server.                          |                                                              | `yui!kick <member:member> [reason:...string]`                |
| hug                   |                                                              |      Picture - Fun       | Hug to other memebr.                                  |                                                              | `yui!hug <member:member>`                                    |
| cat                   |                                                              |      Picture - SFW       | Send cat images.                                      |                                                              | `yui!cat`                                                    |
| dog                   |                                                              |      Picture - SFW       | Send dog images.                                      |                                                              | `yui!dog`                                                    |
| foxgirl               |                                                              |      Picture - SFW       | Send fox girl images.                                 |                                                              | `yui!foxgirl`                                                |
| nekogirl              |                                                              |      Picture - SFW       | Send neko girl images.                                | If you add --gif, a GIF image will be sent.                  | `yui!nekogirl`                                               |
| yuigahama             | yui                                                          |      Picture - SFW       | Send Yuigahama images.                                |                                                              | `yui!《yuigahama|yui》`                                      |