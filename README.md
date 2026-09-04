# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 21 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-ads-plus` | Built from `category-ads-all` + `core-adguard-dns-filter`, `core-oisd-big`, `core-peter-lowe`, `core-someonewhocares-hosts`, `core-stevenblack-hosts` with deduplication. Result: 134.8% more rules than `category-ads-all`. | 443,466 | 57.0 | [Loyalsoldier geosite.dat](https://cdn.jsdelivr.net/gh/Loyalsoldier/v2ray-rules-dat@release/geosite.dat)<br>[AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt)<br>[OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt)<br>[Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)<br>[SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts)<br>[StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 953,393 | 107.1 | [BlockListProject Adult](https://raw.githubusercontent.com/blocklistproject/Lists/master/porn.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 120 | 0.8 | [NoADS RU AI](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,362 | 4.8 | [BlockListProject Facebook](https://blocklistproject.github.io/Lists/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 342,623 | 39.6 | [BlockListProject Gambling](https://blocklistproject.github.io/Lists/gambling.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,725 | 1.7 | [BlockListProject TikTok](https://blocklistproject.github.io/Lists/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 0.5 | [BlockListProject Twitter](https://blocklistproject.github.io/Lists/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 5.3 | [BlockListProject YouTube](https://blocklistproject.github.io/Lists/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 179,822 | 25.9 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-adguard-dns-filter-allow` | Exceptions from AdGuard DNS Filter. | 211 | 0.6 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 270,101 | 36.9 | [OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,540 | 0.8 | [Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 13,054 | 3.5 | [SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 79,995 | 14.7 | [StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `media-non-legal` | fmovies.to, sflix.to, lookmovie.sx, soap2day.rs, hianime.to, animepahe.com, aniwave.to, nyaa.si, tokyotosho.info, 1337x.to, thepiratebay.org, eztv.re, streamtape.com, doodstream.com, mixdrop.co, voe.sx, filemoon.sx, uqload.to, etc. | 1,463 | 1.0 | - |
| `media-non-legal-ru` | rezka.ag, hdrezka.ag, filmix.ac, kinozal.tv, kinogo.ec, lord.kim, seasonvar.ru, alloha.tv, kodik.cc, hdvb.cc, bazon.cc, anilibria.tv, animego.org, animevost.org, jut.su, mangalib.me, ranobelib.me, etc. | 335 | 1.0 | - |
| `regional-cis-noads-ru-hosts` | Domain rules from NoADS RU Hosts. | 203,680 | 26.2 | [NoADS RU Hosts](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blocker.txt) |
| `regional-cis-noads-ru-hosts-fl` | Domain rules from NoADS RU Hosts FL. | 453,014 | 56.3 | [NoADS RU Hosts FL](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blockerFL.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 38,011 | 7.2 | [Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 385 | 0.5 | [URLHaus Online](https://urlhaus.abuse.ch/downloads/hostfile/) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 27,280 | 7.6 | - |
