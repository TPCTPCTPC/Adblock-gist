# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/acs\.m\.taobao\.com\/gw\/mtop\.((trip\.activity|film\.mtopadvertiseapi)\.querytmsresources|(taobao\.idle\.home|aliyun\.mobile)\.welcome(page)?|.*?\.ads?\.) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/gw\.alicdn\.com\/(t(f|p)s\/.+\d{3,4}-\d{4}|mt) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.taobao\.wireless\.home\.splash\.awesome\.get\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% gw.alicdn.com, *acs.m.taobao.com
```
