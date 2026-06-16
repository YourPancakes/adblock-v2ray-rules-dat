# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 28 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-ads-plus` | Built from `category-ads-all` + `core-adguard-dns-filter`, `core-hagezi-pro`, `core-oisd-big`, `core-peter-lowe`, `core-stevenblack-hosts` with deduplication. Result: 425.6% more rules than `category-ads-all`. | 870,581 | 110.1 | [Loyalsoldier geosite.dat](https://cdn.jsdelivr.net/gh/Loyalsoldier/v2ray-rules-dat@release/geosite.dat)<br>[AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt)<br>[HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt)<br>[OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt)<br>[Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)<br>[StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 500,256 | 61.5 | [BlockListProject Adult](https://raw.githubusercontent.com/blocklistproject/Lists/master/porn.txt) |
| `category-adult-hagezi` | Domain rules from HaGeZi Adult. | 97,518 | 14.3 | [HaGeZi Adult](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nsfw-onlydomains.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 119 | 1.7 | [NoADS RU AI](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,459 | 4.9 | [BlockListProject Facebook](https://blocklistproject.github.io/Lists/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 2,500 | 1.2 | [BlockListProject Gambling](https://blocklistproject.github.io/Lists/gambling.txt) |
| `category-gambling-hagezi-medium` | Domain rules from HaGeZi Gambling Medium. | 127,167 | 15.6 | [HaGeZi Gambling Medium](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling.medium-onlydomains.txt) |
| `category-social-hagezi` | Domain rules from HaGeZi Social. | 899 | 1.2 | [HaGeZi Social](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/social-onlydomains.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,699 | 1.6 | [BlockListProject TikTok](https://raw.githubusercontent.com/blocklistproject/Lists/main/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 0.9 | [BlockListProject Twitter](https://blocklistproject.github.io/Lists/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 7.3 | [BlockListProject YouTube](https://blocklistproject.github.io/Lists/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 156,794 | 28.4 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-adguard-dns-filter-allow` | Exceptions from AdGuard DNS Filter. | 207 | 1.4 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-hagezi-multi-normal` | Domain rules from HaGeZi Multi Normal for ads, trackers, and telemetry. | 366,561 | 53.7 | [HaGeZi Multi Normal](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) |
| `core-hagezi-pro` | Domain rules from HaGeZi Pro for ads, trackers, and telemetry. | 506,712 | 68.8 | [HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 336,257 | 41.5 | [OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,505 | 1.7 | [Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 12,864 | 3.4 | [SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 84,973 | 13.0 | [StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `media-non-legal` | fmovies.to, sflix.to, lookmovie.sx, soap2day.rs, hianime.to, animepahe.com, aniwave.to, nyaa.si, tokyotosho.info, 1337x.to, thepiratebay.org, eztv.re, streamtape.com, doodstream.com, mixdrop.co, voe.sx, filemoon.sx, uqload.to, etc. | 1,397 | 0.8 | - |
| `media-non-legal-ru` | rezka.ag, hdrezka.ag, filmix.ac, kinozal.tv, kinogo.ec, lord.kim, seasonvar.ru, alloha.tv, kodik.cc, hdvb.cc, bazon.cc, anilibria.tv, animego.org, animevost.org, jut.su, mangalib.me, ranobelib.me, etc. | 312 | 1.0 | - |
| `regional-cis-noads-ru-hosts` | Domain rules from NoADS RU Hosts. | 186,337 | 26.3 | [NoADS RU Hosts](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blocker.txt) |
| `regional-cis-noads-ru-hosts-fl` | Domain rules from NoADS RU Hosts FL. | 711,475 | 99.3 | [NoADS RU Hosts FL](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blockerFL.txt) |
| `security-hagezi-newly-registered-domains-7d` | Domain rules from HaGeZi Newly Registered Domains 7d. | 0 | 0.0 | [HaGeZi Newly Registered Domains 7d](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nrd7.txt) |
| `security-hagezi-threat-intelligence-feed` | Domain rules from HaGeZi Threat Intelligence Feed. | 1,658,803 | 184.9 | [HaGeZi Threat Intelligence Feed](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 32,244 | 7.6 | [Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 579 | 0.9 | [URLHaus Online](https://urlhaus.abuse.ch/downloads/hostfile/) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 28,214 | 5.7 | - |
