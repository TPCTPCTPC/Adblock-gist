# Incert Mock Rules in your Surge Module

```
[Map Local]
// CMB
^https?:\/\/mlife\.cmbchina\.com\/BaseService\/startAppForV5\.json$ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/mlife\.cmbchina\.com\/ClientFaceService\/preCacheAdvertise\.json$ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/mlife\.cmbchina\.com\/ClientFaceService\/getAdvertisement\.json data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/pic1cdn\.cmbchina\.com\/appinitads\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

// ICBC
^https?:\/\/v\.icbc\.com\.cn\/userfiles\/Resources\/WAP\/advertisement\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% mlife.cmbchina.com, resource.cmbchina.com
```
