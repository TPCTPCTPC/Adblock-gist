# Adblock-Gist
Sorted Adblock rules for Surge iOS 4 and Quantumult X, compatible with Surge Module. Abundant rules are removed/merged to *[Keywords.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Keywords.list)* & *[Suffixes.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Suffixes.list)*

🅰 Check the content before use.

🅱 MITM is required for URL-Regex 'https' rules.

💡 Use AdGuard for a better effect on Safari.

## Compatibility

|                                                                                    |`Surge iOS/Mac`|`Quantumult X`|
|------------------------------------------------------------------------------------|:-------------:|:------------:|
|*[Suffixes.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Suffixes.list)*                      |☑️|☑️|
|*[Keywords.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Keywords.list)*                      |☑️|☑️|
|*[Others.list](https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Others.list)*                          |☑️|☑️|
|*[domain rules](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/DOMAINs)*                             |☑️|☑️|
|*[url-regex](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/URL-REGEX)*                              |☑️|   |
|*[url-rewrite](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/URL-REWRITE)*                          |   |☑️|
|*[mocking](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/Mock)*                                     |☑️|   |
|*[Supplement for anti-AD](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/Supplement%20for%20anti-AD)*|☑️|☑️|

## Work with *[anti-AD](https://github.com/privacy-protection-tools/anti-AD)*:

Since Surge iOS (1641) supported DOMAIN-SET rules, which makes it possible to load advanced rule lists (eg: anti-AD). Hence, If you like to use anti-AD rules, please subscribe the supplement version (deduplicated already).

DOMAIN-SET example:
```
DOMAIN-SET,https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt,REJECT
```

## Work with *Mock (Map Local)*

Since Surge iOS (1723) supported Mock, allowing Surge to return an empty json to the request, which can save up more memories than Javascripts. Users can also load Mock rules in a Module. For now, the fuction of mocking in this gist is duplicate with URL-REGEX rules, choose one you prefer.

Check Mocking Examples in:
```
https://github.com/TPCTPCTPC/Adblock-gist/blob/master/Mock
```

## Create your own Surge Module:
```
#!name=$yourname
#!desc=$yourdescription
// Optional - ignore if you need both
#!system=(ios/mac)

[Rule]
RULE-SET,https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/DOMAINs/EXAMPLE.list,REJECT
RULE-SET,https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/URL-REGEX/EXAMPLE.list,REJECT

[Map Local]
^https://mp\.weixin\.qq\.com/mp/getappmsgad data="empty.json" //You can generate an empty json on your own surge.

// Optional
[MITM]
hostname = %APPEND% an.example.com
```

### Why create your own *Module*?

It is your responsibility to avoid risks from the Man-In-The-Middle attack. 
A remote *Module* can be easily incerted any new hostnames and Javascripts, which could significantly increase the risk of your networking safety, if the user did not notice the change when updating the *Module*.

## Quantumult X Users?
ADBLOCK-GIST now supports QX with [domain rules](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/DOMAINs) compatibly and [url-rewrites rules](https://github.com/TPCTPCTPC/Adblock-gist/tree/master/URL-REWRITE) exclusively.

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
