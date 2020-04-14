# Adblock-gist
Sorted Adblock rules for Surge iOS 4, compatible with Surge Module. Some abundant rules are removed/merged to [Keywords.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Keywords.list)&[Suffixes.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Suffixes.list)

🅰 Check the content before use.

🅱 MITM is required for URL-Regex rules.

🚨 [Facebook.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Facebook.list) & [360.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/360.list) are designed to break most functions of theirs!!


## Create your own Surge Module:
```
#!name=$yourname
#!desc=$yourdescription
// Optional-ignore if you need both
#!system=(ios/mac)

[Rule]
RULE-SET,https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/*EXAMPLE*.list,REJECT

// Optional
[MITM]
hostname = %APPEND% a.example.com

```


### Credits:
[Choler](https://github.com/Choler/Surge)
[ConnersHua](https://github.com/ConnersHua/Profiles/tree/master)
[lhie1](https://github.com/lhie1/Rules)
[onewayticket255](https://github.com/onewayticket255/Surge-Script)
[Yachen Liu](https://community.nssurge.com/d/225-module)
