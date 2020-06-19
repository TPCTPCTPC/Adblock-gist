# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/.+\.googlevideo\.com\/.+ctier data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googlevideo\.com\/.+oad= data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googlevideo\.com\/ptracking data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googlevideo\.com\/videogoodput data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/.+adformat data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/.+get_ads data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/api\/stats\/ads data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/api\/stats\/qoe data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/csi_204 data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/error_204 data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/get_midroll data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/pagead data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.youtube\.com\/ptracking data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis.com/.+ad_break data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis.com/adsmeasurement data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% *.googlevideo.com,*.youtube.com,*.googleapis.com
```
