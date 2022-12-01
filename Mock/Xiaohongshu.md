# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/.+\.xiaohongshu\.com\/.+(collect|metrics|report|Report)  data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% *.xiaohongshu.com
```
