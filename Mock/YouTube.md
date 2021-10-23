# Incert Mock Rules in your Surge Module

```
[Map Local]
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
^https?:\/\/.+\.googleapis\.com\/.+ad data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis\.com\/ads data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis\.com\/youtubei\/v1\/notification_registration data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis\.com\/youtubei\/v1\/guide data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis\.com\/youtubei\/v1\/log_event data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/.+\.googleapis\.com\/youtubei\/v1\/issuetoken data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[URL Rewrite]
(^https?:\/\/[\w-]+\.googlevideo\.com\/.+)(ctier=L)(&.+) $1$3 302

[MITM]
hostname = %APPEND% *.googlevideo.com,*.youtube.com,www.googleapis.com
```
