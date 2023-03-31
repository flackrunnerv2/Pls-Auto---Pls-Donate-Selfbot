# Pls Auto | Pls Donate Selfbot
An automated self-bot for the game [PLS DONATE](https://www.roblox.com/games/8737602449).

Useful to make robux while being afk.
If there are bugs please make an issue.

## Script

```lua
---These getgenv's can be changed if you want to change your settings

getgenv().Settings = {
    AntiAfkDisconnect = true,

    Goal = true,
    GoalText = "MY GOAL:"
    GoalIncrement = 15,

    BoothText = "",
    BoothUpdateInterval = 2,

    Beg = false,
    BegInterval = 15,
    BegText = "pls donate",

    HopAtPlayerCount = 10,
    WaitTillServerHop = 10,

    SendWebhookMessageOnDonate = true,
    WebhookLink = ""
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/flackrunnerv2/Pls-Auto-Pls-Donate-Selfbot/main/src.lua", true))()
```
