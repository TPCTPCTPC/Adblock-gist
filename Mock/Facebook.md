# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/connect\.facebook\.net\/en_US\/fbadnw\.js data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://graph.facebook.com/.+activities data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://graph.facebook.com/.+advertiser_id=* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://graph.facebook.com/.+events data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://graph.facebook.com/network_ads_common/* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://www.facebook.com/adnw_logging/* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://www.facebook.com/adnw_sync/* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?://www.facebook.com/tr data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% connect.facebook.net,graph.facebook.com,www.facebook.com
```
