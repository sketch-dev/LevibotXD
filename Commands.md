# Contents
- [Action](#action)
- [Anime](#anime)
- [Bot](#bot)
- [Core](#core)
- [Economy](#economy)
- [Fun](#fun)
- [Moderation](#moderation)
- [Owner](#owner)
- [Setup](#setup)
- [Utility](#utility)
## Extra
- [Archive](#archive)
- [Removed](#removed)
## Legend
Name | Description
----------------|--------------
`[]` | Indicates a mandatory argument, you must provide this for the command to work!
`<>` | Indicates an optional argument, you do not need to provide this for the command to work
***
<br><br><br>
## Action
Command | Parameters | Description | Example
--------|------------|-------------|--------
`baka`  | User Mention | Sends a random Baka gif pointing to the mentioned user | `m!baka [@User]`
`cry`   | None         | Sends a random Cry gif                                 | `m!cry`
`hug`   | User Mention | Sends a random Hug gif hugging the mentioned user      | `m!hug <@User>`
`kiss`  | User Mention | Sends a random Kiss gif kissing the mentioned user     | `m!kiss [@User]`
`pat`   | User Mention | Sends a random Pat gif patting the mentioned user      | `m!pat <@User>`
`poke`  | User Mention | Sends a random Poke gif poking the mentioned user      | `m!poke [@User]`
`slap`  | User Mention | Sends a random Slap gif slapping the mentioned user    | `m!slap [@User]`
`smug`  | None         | Sends a random Smug                                    | `m!smug`
`tickle`| User Mention | Sends a random Tickle gif tickling the mentioned user  | `m!tickle [@User]`

[Back to top](#Contents)
<br><br><br>
## Anime
Command | Parameters | Description | Example
--------|------------|-------------|--------
`anime`       | **Query** (Anime Title) | Queries Anime on [MyAnimeList](https://myanimelist.net) to get Anime's basic Information | `m!anime <Seishun Buta>`
`animeme`     | **Configuration** (Random, Reload) | Sends a meme fetched from the subredit [r/animemes](https://reddit.com/r/animemes) | `m!anime <random / reload>`
`aniquote`    | **None** | Sends a totally random anime quote | `m!aniquote`
`anirandom`   | **None** | Sends a totally random anime | `m!anirandom`
`character`   | **Query** (Character Name) | Queries Anime Character on [MyAnimeList](https://myanimelist.net) to get Character's basic Information | `m!character <Mai Sakurajima>`
`discover`    | **Type** (Anime or Manga) | Get a personalized anime / manga recommendation | `m!discover [anime / manga]`
`malprofile`  | Configuration (UserMention, set, self, update) | View or set own's MAL profile to your discord account (bot-bound) | `m!malprofile <@User / -self / -set [Mal Username] / -set [Mal Username] -update>`
`manga`       | Query (Character Name) | Queries Manga on [MyAnimeList](https://myanimelist.net). Returns up to 10 results | `m!manga <Seishun Buta>`
`mangarandom` | None | Sends a totally random anime | `m!mangarandom`
`nextairdate` | Query (Anime Title) | Sends the next episode's airdate if a query is provided, or returns the next three airing episodes | `m!nextairdate <Seishun Buta Yarou>`
`sauce`       | ID (6 digit ID) | NSFW WARNING! Grabs the doujin Information based on the provided ID | `m!sauce [5 or 6-digit number]`
`schedule`    | Query (Day of the week) | Returns the provided weekday's anime schedule, or today if none is provided | `m!schedule <Tuesday>`
`seiyuu`      | Query (Seiyuu Name) | Queries Voice Actress on [AniList](https://anilist.co) to get VA's basic Information | `m!seiyuu <Amamiya Sora>`
`waifu`       | None | Generate random waifu image | `m!waifu`

[Back to top](#Contents)
<br><br><br>
## Bot
Command | Parameters | Description | Example
--------|------------|-------------|--------
`feedback` | Feedback Message | Sends a feedback directly to Sakurajimai#6742's inbox | `m!feedback [economy not working pls help]`
`invite`   | None             | Sends the bot's invite link, support server link, the server's link (if previously set up), and/or Advertised server link | `m!invite`
`ping`     | None             | Sends various ping of the bot | `m!ping`
`stats`    | None             | Sends the bot's current status | `m!stats`

[Back to top](#Contents)
<br><br><br>
## Core
Command | Parameters | Description | Example
--------|------------|-------------|--------
`cmd`           | Command Category | Sends the list of commands under selected category | `m!cmd [core]`
`help`          | Command Name | Sends the command information for the provided command name | `m!help <rank>`
`leaderboard`   | None | Sends the server xp leaderboard [Server and Channel Must be xp enabled] | `m!leaderboard`
`mai`           | None | Sends a random Mai Image
`nonxpchannels` | None | Displays the list of channels where xp is disabled [Server must be xp enabled] | `m!nonxpchannels`
`rank`          | User Mention | Displays own / mentioned user's server xp ranking [Server and channel must be xp enabled] | `m!rank <@User Mention>`
`suggest`       | Suggestion Message | Send a suggestion for the server [Requires a set suggest channel] | `m!suggest [add an emoji channel!]`
`watching`      | None | Sends the list of anime under the server's [Anischedule Feature](https://github.com/maisans-maid/Mai/wiki/Anischedule) (if enabled) | `m!watching`

[Back to top](#Contents)
<br><br><br>
## Economy
Command | Parameters | Description | Example
--------|------------|-------------|--------
`bal`      | None   | Checks your current wallet and/or bank balance (If you have a bank) | `m!bal`
`bank`     | None   | Register yourself to the bank (If you don't have a bank yet) | `m!bank`
`beg`      | None   | Beg for some coins. Don't let pride get in your way to get rich! | `m!beg`
`daily`    | None   | Get daily reward from Mai. Remember to keep your streak for increased rewards | `m!daily`
`deposit`  | Amount | Deposit some of your money to the bank (If you have a bank) to prevent [overflow](https://github.com/maisans-maid/Mai/wiki/Economy#WalletOverflow) | `m!deposit [15000]`
`find`     | None   | Find some coins around | `m!find`
`register` | None   | Register yourself to the Economy System for free! | `m!register`
`transfer` | None   | Transfer some of your coins to your friend. Both parties have to be registered to a bank! | `m!transfer [@User] [50000]`
`withdraw` | Amount | Withdraw some coins from your bank | `m!withdraw [15000]`

[More info on Economy Section of the Wiki](https://github.com/maisans-maid/Mai/wiki/Economy) <br>
[Back to top](#Contents)
<br><br><br>
## Fun
Command | Parameters | Description | Example
--------|------------|-------------|--------


[Back to top](#Contents)
<br><br><br>
## Moderation
Command | Parameters | Description | Example
--------|------------|-------------|--------


[Back to top](#Contents)
<br><br><br>
## Owner
Command | Parameters | Description | Example
--------|------------|-------------|--------


[Back to top](#Contents)
<br><br><br>
## Setup
Command | Parameters | Description | Example
--------|------------|-------------|--------


[Back to top](#Contents)
<br><br><br>
## Utility
Command | Parameters | Description | Example
--------|------------|-------------|--------


[Back to top](#Contents)
<br><br><br>
# Extra Commands
## Archive
Command | Description | Archive Reason |
--------|-------------|----------------|


[Back to top](#Contents)
<br><br><br>
## Removed
Command | Description | Removal Reason |
--------|-------------|----------------|


[Back to top](#Contents)
