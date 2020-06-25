# URL-REGEX Rules for Surge 4
🅰️ MITM required.

🅱️ Add hostnames to your configurations or Surge Modules manually.

## How to use?
See [Create your own Surge Module](https://github.com/TPCTPCTPC/Adblock-gist#create-your-own-surge-module)

## Force HTTP hosts
Some TCP connections need to be converted to HTTP, add a force-http-engine in [General] section to your configurations or *Surge Module* if it is required in the rule-list.

See sample:

```
[General]
force-http-engine-hosts = %APPEND% vali.cp31.ott.cibntv.net
```
