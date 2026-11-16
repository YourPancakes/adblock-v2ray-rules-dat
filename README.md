# Geosite AdBlock

## What is this?

This project automatically rebuilds a merged `geosite.dat` every 5 hours and adds tags on top of the original geosite.

It consists of the original `geosite.dat` from [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) and 24 additional tags.

## Download

- [`https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat`](https://github.com/YourPancakes/adblock-v2ray-rules-dat/releases/download/release/geosite.dat)

## Added tags

| Tag | Description | Rules | RAM MiB | Source |
|---|---|---:|---:|---|
| `category-ads-plus` | Built from `category-ads-all` + `core-hagezi-pro`, `core-adguard-dns-filter`, `core-oisd-big`, `core-peter-lowe`, `core-someonewhocares-hosts`, `core-stevenblack-hosts` with deduplication. Result: 168.2% more rules than `category-ads-all`. | 539,305 | 59.0 | [Loyalsoldier geosite.dat](https://cdn.jsdelivr.net/gh/Loyalsoldier/v2ray-rules-dat@release/geosite.dat)<br>[HaGeZi Multi Pro](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.txt)<br>[AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt)<br>[OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt)<br>[Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)<br>[SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts)<br>[StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `category-adult-blocklistproject` | Domain rules from BlockListProject Adult. | 953,393 | 601.8 | [BlockListProject Adult](https://raw.githubusercontent.com/blocklistproject/Lists/master/porn.txt) |
| `category-ai-noads-ru` | Domain rules from NoADS RU AI. | 120 | 1.1 | [NoADS RU AI](https://raw.githubusercontent.com/Zalexanninev15/NoADS_RU/main/filters/ai_slop_killer.txt) |
| `category-facebook-blocklistproject` | Domain rules from BlockListProject Facebook. | 22,362 | 5.5 | [BlockListProject Facebook](https://blocklistproject.github.io/Lists/facebook.txt) |
| `category-gambling-blocklistproject` | Domain rules from BlockListProject Gambling. | 342,623 | 31.8 | [BlockListProject Gambling](https://blocklistproject.github.io/Lists/gambling.txt) |
| `category-malware-blocklistproject` | Domain rules from BlockListProject Malware to block malware, trojans, and malicious domains. | 2,656,393 | 637.6 | [BlockListProject Malware](https://blocklistproject.github.io/Lists/malware.txt) |
| `category-tiktok-blocklistproject` | Domain rules from BlockListProject TikTok. | 3,725 | 1.3 | [BlockListProject TikTok](https://blocklistproject.github.io/Lists/tiktok.txt) |
| `category-twitter-blocklistproject` | Domain rules from BlockListProject Twitter. | 1,193 | 0.9 | [BlockListProject Twitter](https://blocklistproject.github.io/Lists/twitter.txt) |
| `category-youtube-blocklistproject` | Domain rules from BlockListProject YouTube. | 24,280 | 6.0 | [BlockListProject YouTube](https://blocklistproject.github.io/Lists/youtube.txt) |
| `core-adguard-dns-filter` | Domain rules from AdGuard DNS Filter for ads, trackers, and telemetry. | 190,164 | 24.5 | [AdGuard DNS Filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt) |
| `core-hagezi-pro` | HaGeZi Multi Pro: ads, trackers, analytics, telemetry, and related unwanted domains. | 241,180 | 25.7 | [HaGeZi Multi Pro](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.txt) |
| `core-hagezi-pro-plus` | HaGeZi Multi Pro++: a more aggressive standalone HaGeZi Multi tier. | 263,630 | 27.8 | [HaGeZi Multi Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt) |
| `core-hagezi-ultimate` | HaGeZi Ultimate: the strictest standalone HaGeZi Multi tier. | 295,260 | 30.6 | [HaGeZi Ultimate](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/ultimate.txt) |
| `core-oisd-big` | Domain rules from OISD Big for ads, trackers, and analytics. | 228,857 | 22.3 | [OISD Big](https://raw.githubusercontent.com/sjhgvr/oisd/main/domainswild2_big.txt) |
| `core-peter-lowe` | Domain rules from Peter Lowe. | 3,564 | 1.5 | [Peter Lowe](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext) |
| `core-someonewhocares-hosts` | Domain rules from SomeoneWhoCares Hosts. | 13,090 | 4.1 | [SomeoneWhoCares Hosts](https://someonewhocares.org/hosts/zero/hosts) |
| `core-stevenblack-hosts` | Domain rules from StevenBlack Hosts. | 76,105 | 10.7 | [StevenBlack Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) |
| `media-non-legal` | Final domains: 0123movies.com, 1.selfmanga.live, 123chill.co, 123movies.la, 123movieshub.cc, 1337x.gd, 1337x.org, 1337x.to, 1337x.unblocked.llc, 1337x.unblockit.nl, 1movies.tv, 1stream.eu, etc. | 1,228 | 0.4 | - |
| `media-non-legal-ru` | Final domains: 1.selfmanga.live, 3.readmanga.ru, 36.doramalive.co, 4k-hd.club, 4ksport.live, 4ksport.ru, a8cv.hardwarewallet-japan.com, ad.kinozal.website, ads-m.rustore.ru, advast.sibnet.ru, akniga.org, aksor.yani.tv, etc. | 334 | 0.8 | - |
| `security-hagezi-tif` | HaGeZi Threat Intelligence Feeds: malware, phishing, scams, cryptojacking, and C2 domains. | 1,464,000 | 779.8 | [HaGeZi Threat Intelligence Feeds](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) |
| `security-phishing-army` | Domain rules from Phishing Army Extended. | 144,352 | 16.2 | [Phishing Army Extended](https://phishing.army/download/phishing_army_blocklist_extended.txt) |
| `security-phishing-filter-agh` | Domain rules from Phishing Filter AGH. | 17,950 | 3.8 | [Phishing Filter AGH](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt) |
| `security-urlhaus-online` | Domain rules from URLHaus Online. | 574 | 1.1 | [URLHaus Online](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts-online.txt) |
| `social` | Domain rules for social networks and related domains. They include Facebook, Instagram, Messenger, WhatsApp, TikTok, X/Twitter, Reddit, Snapchat, Pinterest, LinkedIn, Twitch, WeChat, Bluesky, Badoo, Bumble, Hinge, Match, OkCupid, Plenty of Fish, Clubhouse, Myspace, Likee, Foursquare, Free Basics, and internet.org. | 27,280 | 4.9 | - |
