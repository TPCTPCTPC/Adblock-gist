# Adblock-Gist
Sorted Adblock rules for Surge iOS 4, compatible with Surge Module. Abundant rules are removed/merged to *[Keywords.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Keywords.list)* & *[Suffixes.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Suffixes.list)*

🅰 Check the content before use.

🅱 MITM is required for URL-Regex 'https' rules.

💡 Use AdGuard for a better effect on Safari.

🚨 *[Facebook.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Facebook.list)* & *[360.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/360.list)* are designed to break most functions of theirs!!

🚨 *[360.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/360.list)* could slow down your network, not recommended for Surge iOS if not necessary.

## Work with *[anti-AD](https://github.com/privacy-protection-tools/anti-AD)*:

Since Surge iOS (1641) supports DOMAIN-SET rules, which makes it possible to load advanced rule lists (eg: anti-AD). Hence, If you like to use anti-AD rules, please subscribe the supplement version (deduplicated already).

DOMAIN-SET example:
```
DOMAIN-SET,https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt,REJECT
```

## Create your own Surge Module:
```
#!name=$yourname
#!desc=$yourdescription
// Optional - ignore if you need both
#!system=(ios/mac)

[Rule]
RULE-SET,https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/EXAMPLE.list,REJECT

// Optional
[MITM]
hostname = %APPEND% an.example.com
```
### Why create your own *Module*?

It is your responsibility to avoid risks from the Man-In-The-Middle attack. 
A remote *Module* can be easily incerted any new hostnames and Javascripts, which could significantly increase the risk of your networking safety, if the user did not notice the change when updating the *Module*.

## Credits:
- [anti-AD](https://github.com/privacy-protection-tools/anti-AD)
- [Choler](https://github.com/Choler/Surge)
- [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master)
- [domain-list-community](https://github.com/v2ray/domain-list-community)
- [Lãng Khách](https://github.com/langkhach270389/Scripting/tree/master/Surge)
- [lhie1](https://github.com/lhie1/Rules)
- [onewayticket255](https://github.com/onewayticket255/Surge-Script)
- [primovist](https://github.com/primovist/ScriptsForSurge)
- [Yachen Liu](https://community.nssurge.com/d/225-module)
