# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/.+extshort\.weixin\.qq\.com\/cgi-bin\/mmoc-bin\/ad\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
https://mp.weixin.qq.com/mp/.+report\? data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
https://mp.weixin.qq.com/mp/.+ad\? data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
https://mp.weixin.qq.com/mp/.+monitor\? data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% mp.weixin.qq.com
```
