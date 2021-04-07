# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(ad|abtest|sp|hot|log|mlivestream|store|mlog|search/(specialkeyword|defaultkeyword|hot)) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/eapi\/ad\/loading\/get data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/eapi\/pl\/count data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/api\/feedback\/client data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% interface.music.163.com
```
