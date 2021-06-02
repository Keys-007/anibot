Telegram Bot Repo Capable of fetching the following Info via Anilist API inspired from [AniFluid](https://t.me/anifluidbot) and [Nepgear](https://t.me/nepgearbot)
* Anime
* Airing
* Manga
* Character
* Scheduled
* Anilist Activity

Anime Reverse Search Powered by tracemoepy
Reverse Search Powered by SauceNAO                                                           (WIP)
Watch Order from [Chiaki](https://chiaki.site/) using [web api](https://chiaki.vercel.app)


## Available Cmds
```
 /help - Get interactive and detailed help on bot cmds
 /ping - Ping the bot to check if it's online
 /start - To start bot in group (will be logged) or pm (user if not OWNER will be logged)
 /anime - Fetches info on single anime (includes buttons to look up for prequels and sequels)
 /anilist - Fetches info on multiple possible animes related to query
 /character - Fetches info on multiple possible characters related to query
 /manga - Fetches info on multiple possible mangas related to query
 /airing - Fetches info on airing data for anime
 /flex or /me - Fetches anilist info of an authorised user
 /user - Fetches anilist info as per query
 /scheduled - Fetches scheduled animes
 /auth - Fetches info on how to authorize anilist account
 /code - Generates access token from the authorization code from authorization website
 /logout - removes authorization
 /reverse - Reverse search powered by tracemoepy
 /sauce - Reverse Search Powered by SauceNAO                                                 (WIP)
 /watch - Fetches watch order for anime series
```


## Owner/Sudo Cmds
```
 /eval - Runs python code (code must start right after cmd like "/eval print('UwU')")
 /term - Runs the code in terminal
 /stats - Gibs data on bot such as no. of grps/users and ping
```


## Requirements
* Python 3.9.5
* Telegram [API Keys](https://my.telegram.org/apps)
* Bot Token [Token](https://t.me/botfather)
* SauceNAO [API Keys](https://saucenao.com/)
* MongoDB [Database URL](https://cloud.mongodb.com/)
* Anilist [Client Keys](https://anilist.co/settings/developer)


## Goals
* plugins to be added / make it working
 ```
 top - to retrieve top animes for a genre
 trend - to retrieve trends
 ```


## Credits
* AniList Api ([GitHub](https://github.com/AniList/ApiV2-GraphQL-Docs))
* jikanpy ([GitHub](https://github.com/abhinavk99/jikanpy))
* @NotThatMF for [chiaki fast api](https://chiaki.vercel.app/) and for creating base for this bot to work
* @DragSama on telegram for [tracemoepy](https://github.com/code-rgb/USERGE-X) & [AniFluid-Base](https://github.com/DragSama/AniFluid-Base)
* @DeletedUser420 on telegram for [USERGE-X](https://github.com/code-rgb/USERGE-X) & [Userge-Plugins](https://github.com/code-rgb/Userge-Plugins)
* [Phyco-Ninja](https://github.com/Phyco-Ninja) as author of anilist plugin in Userge-Plugins repo
* @blank_x on tg for [sukuinote](https://gitlab.com/blank-x/sukuinote)


For improvements PR or contact @LostB053 (on telegram) 
can ask for support too in @LostB053 but don't expect much (since i myself am learning yet)