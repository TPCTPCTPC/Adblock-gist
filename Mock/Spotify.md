# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/spclient.wg.spotify.com\/ad-logic\/* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/ads\/* data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+ad_slot data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+banners data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+canvases data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+cards data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+crashlytics data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+doubleclick.net data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+enabled-tracks data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+event data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/spclient.wg.spotify.com\/.+promoted_offer data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% spclient.wg.spotify.com
```
