# Incert Mock Rules in your Surge Module

```
[Map Local]
^https?:\/\/www\.zhihu\.com\/api\/v4\/mcn data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https?:\/\/api\.zhihu\.com\/(ab|adx|xen|club|fringe|zst|commercial|ad-style-service|market/popover|search/(top|tab|preset)|.*(guide|recommendations|extended|featured-comment-ad)) data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https:\/\/118\.89\.204\.198\/resolv\?host=mqtt\.zhihu\.com data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https:\/\/118\.89\.204\.198\/resolv\?host=sugar\.zhihu\.com data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"
^https:\/\/118\.89\.204\.198\/resolv\?host=zhihu-web-analytics\.zhihu\.com data="https://raw.githubusercontent.com/TPCTPCTPC/Adblock-gist/master/Mock/empty.json"

[MITM]
hostname = %APPEND% ap*.zhihu.com, www.zhihu.com, 118.89.204.198
```
