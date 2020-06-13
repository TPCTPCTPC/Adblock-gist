# Incert Mock Rules in your Surge Module

```
[Map Local]
URL-REGEX,"^http:\/\/[\s\S]*baidu\.com/.*ad[xs]\.php" data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
URL-REGEX,"^https?:\/\/pan\.baidu\.com\/rest\/2.0\/pcs\/adx" data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
URL-REGEX,"^https?:\/\/pan\.baidu\.com\/act\/api\/activityentry" data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
URL-REGEX,^https?://(api|ps|sv|offnavi|newvector|ulog\.imap|newloc)(\.map|)\.(baidu|n\.shifen)\.com data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
```