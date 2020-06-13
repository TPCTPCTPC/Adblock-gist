# Incert Mock Rules in your Surge Module

```
[Map Local]
https://app.bilibili.com/(pgc/season/rank/cn|x/v2/(rank.*rid=(168|5)|search/(defaultword|hot|recommend|resource))) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% app.bilibili.com
```