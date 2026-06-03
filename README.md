# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 26 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)
- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/tag/release`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/tag/release)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-ads-plus` | Tag for ads, trackers, telemetry, and analytics. It contains 562,473 rules vs 174,407 in official `category-ads-all` (+388,066). It excludes regional, malware, phishing, adult, gambling, and narrow specialized categories. | 562,473 | 66.0 | [Loyalsoldier geosite.dat](https://cdn.jsdelivr.net/gh/Loyalsoldier/v2ray-rules-dat@release/geosite.dat)<br>[Core HaGeZi Multi Normal](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)<br>[Core HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)<br>[Core OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild_big.txt)<br>[Core AdGuard DNS Filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)<br>[Core Peter Lowe](https://pgl.yoyo.org/as/serverlist.php?hostformat=domains&mimetype=plaintext)<br>[Core SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/hosts) |
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 500,256 | 50.2 | [Category Adult BlockListProject](https://blocklistproject.github.io/Lists/porn.txt) |
| `category-adult-hagezi` | Domain rules from HaGeZi Adult. | 85,356 | 8.4 | [Category Adult HaGeZi](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nsfw.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 119 | 0.5 | [Category AI NoADS RU](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,459 | 3.8 | [Category Facebook BlockListProject](https://blocklistproject.github.io/Lists/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 2,500 | 0.6 | [Category Gambling BlockListProject](https://blocklistproject.github.io/Lists/gambling.txt) |
| `category-gambling-hagezi-medium` | Domain rules from HaGeZi Gambling Medium. | 79,266 | 8.3 | [Category Gambling HaGeZi Medium](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/gambling.medium.txt) |
| `category-social-hagezi` | Domain rules from HaGeZi Social. | 890 | 0.4 | [Category Social HaGeZi](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/social.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,699 | 0.4 | [Category TikTok BlockListProject](https://blocklistproject.github.io/Lists/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 0.1 | [Category Twitter BlockListProject](https://blocklistproject.github.io/Lists/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 4.2 | [Category YouTube BlockListProject](https://blocklistproject.github.io/Lists/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 159,883 | 19.3 | [Core AdGuard DNS Filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) |
| `core-adguard-dns-filter-allow` | Exceptions from AdGuard DNS Filter. | 207 | 0.6 | [Core AdGuard DNS Filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) |
| `core-hagezi-multi-normal` | Domain rules from HaGeZi Multi Normal for ads, trackers, and telemetry. | 158,040 | 17.2 | [Core HaGeZi Multi Normal](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) |
| `core-hagezi-pro` | Domain rules from HaGeZi Pro for ads, trackers, and telemetry. | 209,470 | 21.4 | [Core HaGeZi Pro](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 347,143 | 35.7 | [Core OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild_big.txt) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,508 | 1.7 | [Core Peter Lowe](https://pgl.yoyo.org/as/serverlist.php?hostformat=domains&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 12,804 | 1.8 | [Core SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 81,382 | 8.7 | [Core StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `regional-cis-noads-ru-hosts` | Domain rules from NoADS RU Hosts. | 192,410 | 20.4 | [Regional CIS NoADS RU Hosts](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blocker.txt) |
| `regional-cis-noads-ru-hosts-fl` | Domain rules from NoADS RU Hosts FL. | 718,662 | 88.7 | [Regional CIS NoADS RU Hosts FL](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/hosts/blockerFL.txt) |
| `security-hagezi-newly-registered-domains-7d` | Domain rules from HaGeZi Newly Registered Domains 7d. | 2,511,190 | 247.4 | [Security HaGeZi Newly Registered Domains 7d](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nrd7.txt) |
| `security-hagezi-threat-intelligence-feed` | Domain rules from HaGeZi Threat Intelligence Feed. | 1,345,454 | 125.6 | [Security HaGeZi Threat Intelligence Feed](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 30,638 | 4.4 | [Security Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 1,241 | 0.4 | [Security URLHaus Online](https://gitlab.com/malware-filter/urlhaus-filter/-/raw/master/urlhaus-filter-hosts-online.txt) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 551 | 0.1 | - |
