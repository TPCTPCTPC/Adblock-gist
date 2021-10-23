# Incert Mock Rules in your Surge Module

```
[General]
force-http-engine-hosts = %APPEND% interface3.music.163.com:80,interface3.music.163.com:443,interface3.music.163.com.163jiasu.com:80,interface3.music.163.com.163jiasu.com:443

[Map Local]
^https?:\/\/interface3?\.music\.163\.com\/eapi\/(ad|abtest|sp|hot|log|mlivestream|store|mlog|search/(specialkeyword|defaultkeyword|hot)) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/eapi\/ad\/loading\/get data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/eapi\/pl\/count data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^http?:\/\/music\.163\.com\/api\/feedback\/client data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/eapi\/ad\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/((25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/eapi\/v1\/content\/exposure\/comment\/banner data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% interface3.music.163.com, 59.111.*
```
