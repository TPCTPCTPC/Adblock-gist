# Incert Mock Rules in your Surge Module

```
[Map Local]
// Chelaile
^https?:\/\/(api|atrace)\.chelaile\.net\.cn\/adpub\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/api\.chelaile\.net\.cn\/goocity\/advert\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/atrace\.chelaile\.net\.cn\/exhibit\?&adv_image data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/pic1\.chelaile\.net\.cn\/adv\/ data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

// Didi
^https?:\/\/res\.xiaojukeji\.com\/resapi\/activity\/get(Ruled|Preload) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/*\.didistatic\.com\/static\/starimg\/node data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/*\.didistatic\.com\/static\/ad_oss data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% res.xiaojukeji.com, *.chelaile.net.cn,*.didistatic.com
```
