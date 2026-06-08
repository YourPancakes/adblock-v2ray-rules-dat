# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 26 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-ads-plus` | Domain rules for ads, trackers, telemetry, and analytics. It excludes regional, malware, phishing, adult, gambling, and narrow specialized categories. | 847,489 | 111.3 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt)<br>[HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt)<br>[OISD Big](https://big.oisd.nl/domainswild2)<br>[Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)<br>[StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 500,256 | 60.4 | [BlockListProject Adult](https://raw.githubusercontent.com/blocklistproject/Lists/master/porn.txt) |
| `category-adult-hagezi` | Domain rules from HaGeZi Adult. | 93,911 | 14.1 | [HaGeZi Adult](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nsfw-onlydomains.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 119 | 1.0 | [NoADS RU AI](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,459 | 5.5 | [BlockListProject Facebook](https://blocklistproject.github.io/Lists/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 2,500 | 0.9 | [BlockListProject Gambling](https://blocklistproject.github.io/Lists/gambling.txt) |
| `category-gambling-hagezi-medium` | Domain rules from HaGeZi Gambling Medium. | 110,290 | 15.7 | [HaGeZi Gambling Medium](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling.medium-onlydomains.txt) |
| `category-social-hagezi` | Domain rules from HaGeZi Social. | 890 | 0.8 | [HaGeZi Social](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/social-onlydomains.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,699 | 1.8 | [BlockListProject TikTok](https://raw.githubusercontent.com/blocklistproject/Lists/main/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 0.9 | [BlockListProject Twitter](https://blocklistproject.github.io/Lists/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 8.0 | [BlockListProject YouTube](https://blocklistproject.github.io/Lists/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 156,533 | 23.0 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-adguard-dns-filter-allow` | Exceptions from AdGuard DNS Filter. | 207 | 0.6 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-hagezi-multi-normal` | Domain rules from HaGeZi Multi Normal for ads, trackers, and telemetry. | 374,285 | 51.0 | [HaGeZi Multi Normal](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) |
| `core-hagezi-pro` | Domain rules from HaGeZi Pro for ads, trackers, and telemetry. | 484,517 | 68.7 | [HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 327,226 | 42.4 | [OISD Big](https://big.oisd.nl/domainswild2) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,508 | 1.3 | [Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 12,827 | 2.8 | [SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 83,497 | 15.8 | [StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `regional-cis-noads-ru-hosts` | Domain rules from NoADS RU Hosts. | 187,648 | 26.9 | [NoADS RU Hosts](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blocker.txt) |
| `regional-cis-noads-ru-hosts-fl` | Domain rules from NoADS RU Hosts FL. | 680,290 | 101.5 | [NoADS RU Hosts FL](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blockerFL.txt) |
| `security-hagezi-newly-registered-domains-7d` | Domain rules from HaGeZi Newly Registered Domains 7d. | 2,490,752 | 286.4 | [HaGeZi Newly Registered Domains 7d](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/nrd7.txt) |
| `security-hagezi-threat-intelligence-feed` | Domain rules from HaGeZi Threat Intelligence Feed. | 1,530,231 | 170.3 | [HaGeZi Threat Intelligence Feed](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 31,629 | 8.5 | [Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 501 | 0.5 | [URLHaus Online](https://urlhaus.abuse.ch/downloads/hostfile/) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 28,205 | 5.5 | - |
