# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 24 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 953,393 | 107.9 | [BlockListProject Adult](https://raw.githubusercontent.com/blocklistproject/Lists/main/porn.txt) |
| `category-adult-hagezi` | Domain rules from HaGeZi Adult. | 107,371 | 14.2 | [HaGeZi Adult](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nsfw-onlydomains.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 119 | 1.6 | [NoADS RU AI](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,362 | 5.0 | [BlockListProject Facebook](https://raw.githubusercontent.com/blocklistproject/Lists/main/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 342,623 | 40.0 | [BlockListProject Gambling](https://raw.githubusercontent.com/blocklistproject/Lists/main/gambling.txt) |
| `category-gambling-hagezi-medium` | Domain rules from HaGeZi Gambling Medium. | 141,821 | 20.5 | [HaGeZi Gambling Medium](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling.medium-onlydomains.txt) |
| `category-social-hagezi` | Domain rules from HaGeZi Social. | 898 | 1.3 | [HaGeZi Social](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/social-onlydomains.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,725 | 1.7 | [BlockListProject TikTok](https://raw.githubusercontent.com/blocklistproject/Lists/main/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 1.2 | [BlockListProject Twitter](https://raw.githubusercontent.com/blocklistproject/Lists/main/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 6.7 | [BlockListProject YouTube](https://raw.githubusercontent.com/blocklistproject/Lists/main/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 162,017 | 25.8 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-adguard-dns-filter-allow` | Exceptions from AdGuard DNS Filter. | 208 | 0.8 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 430,067 | 54.1 | [OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,513 | 1.8 | [Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 12,973 | 3.6 | [SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 96,767 | 13.3 | [StevenBlack Hosts](https://cdn.jsdelivr.net/gh/StevenBlack/hosts@master/hosts) |
| `media-non-legal` | fmovies.to, sflix.to, lookmovie.sx, soap2day.rs, hianime.to, animepahe.com, aniwave.to, nyaa.si, tokyotosho.info, 1337x.to, thepiratebay.org, eztv.re, streamtape.com, doodstream.com, mixdrop.co, voe.sx, filemoon.sx, uqload.to, etc. | 16,865 | 3.6 | - |
| `media-non-legal-ru` | rezka.ag, hdrezka.ag, filmix.ac, kinozal.tv, kinogo.ec, lord.kim, seasonvar.ru, alloha.tv, kodik.cc, hdvb.cc, bazon.cc, anilibria.tv, animego.org, animevost.org, jut.su, mangalib.me, ranobelib.me, etc. | 12,639 | 3.3 | - |
| `regional-cis-noads-ru-hosts` | Domain rules from NoADS RU Hosts. | 187,076 | 24.3 | [NoADS RU Hosts](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blocker.txt) |
| `regional-cis-noads-ru-hosts-fl` | Domain rules from NoADS RU Hosts FL. | 777,315 | 108.2 | [NoADS RU Hosts FL](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blockerFL.txt) |
| `security-hagezi-threat-intelligence-feed` | Domain rules from HaGeZi Threat Intelligence Feed. | 54,444 | 8.0 | [HaGeZi Threat Intelligence Feed](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/tif.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 33,574 | 8.0 | [Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 364 | 0.9 | [URLHaus Online](https://urlhaus.abuse.ch/downloads/hostfile/) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 28,142 | 5.3 | - |
