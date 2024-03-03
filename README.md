![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)![GitHub repo size](https://img.shields.io/github/repo-size/hagezi/dns-blocklists)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhagezi%2Fdns-blocklists&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
## :zap: DNS Blocklists - *For a better internet!*
           
### *Made with :heartbeat: for a safer and cleaner internet! It always seems impossible until it’s done.*
*Privacy is not a crime, protect yourself. Privacy matters. Privacy is what allows us to determine who we are and who we want to be :bangbang:*     
            
*If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)! Thanks for your support!*            

---	 

### :bookmark_tabs: Table of Contents
1. [Overview](#overview)
2. [Multi light](#light) - *Hand brush: Light protection*
3. [Multi normal](#normal) - *Broom: All-round protection*
4. [Multi pro](#pro) - *Big broom: Extended protection (Recommended)*
5. [Multi pro++](#proplus) - *Sweeper: Maximum protection (more aggressive)*
6. [Multi ultimate](#ultimate) - *Ultimate Sweeper: Aggressive protection*
7. [Fake](#fake) - *Protects against internet scams, traps & fakes!*
8. [Pop-Up Ads](#popupads) - *Protects against annoying pop-up ads!*
9. [Threat Intelligence Feeds](#tif) - *Increases security significantly! (Recommended)*
10. [DoH/VPN/TOR/Proxy Bypass](#bypass) - *Prevent methods to bypass your DNS!*
11. [Safesearch not supported](#safesearch) - *Prevent the use of search engines that do not support safesearch!*
12. [Dynamic DNS](#dyndns) - *Protects against the malicious use of dynamic DNS services!*
13. [Badware Hoster](#hoster) - *Protects against the malicious use of free host services!*
14. [Most Abused TLDs](#tlds) - *Protects against known malicious Top Level Domains!*
15. [Anti Piracy](#piracy) - *Protects against piracy!*
16. [Gambling](#gambling) - *Protects against gambling content!*
17. [Native Tracker](#native) - *Broadband tracker of devices, services and operating systems*
18. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - *Leave a star (top right)!*
19. [Recommendation](#recommendation) - [Which version of the lists should I use?](#whatshouldiuse)
20. [Online DNS Services](#dnsservices) : [AdGuardDNS](#adguarddns) - [ControlD](#controld) - [NextDNS](#nextdns) - [RethinkDNS](#rethinkdns) - [DNSwarden](#dnswarden) - [DNSforge](#dnsforge) - [OpenBLD.net](#openbld)
21. [About](#about) : [Contact](#contact) - [Groups](#groups) - [Repository](#repository) - [Referral Domains](#referral) - [Support Me](#support)
22. [Statistics](statistics.md) - [Sources](sources.md) 
23. [FAQ](https://github.com/hagezi/dns-blocklists/wiki/FAQ) - Frequently Asked Questions
24. [Mirror](https://gitlab.com/hagezi/mirror/-/tree/main/dns-blocklists) - *Mirrored files of the block lists on GitLab*

### :books: ***Multi - Cleans the Internet and protects your privacy!*** <a name="overview"></a>
*An all in one DNS blocklist in **various versions (light, normal, pro, pro++ and ultimate)**. It can be used as a stand alone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various blocklists](sources.md). No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas.*

#### ***Blocklist version and size overview:***
| Version | Entries | Pro++ | Pro | Nor<br>mal | Light | [Fake](#fake) | [TIF](#tif) | [Nat<br>ive](#native) | [PopUp<br>Ads](#popupads) | Bug<br>Tracker |
|:--------|---:|:------:|:-----:|:----:|:----:|:---:|:------:|:----------:|:----:|:----:|
| :green_book:[Light](#light)             | 237434<br>68967     |  |   |   |  |  | :yellow_square: |  :yellow_square: | | |
| :blue_book:[Normal](#normal)       | 766838<br>135457     |  |   |  | :green_circle: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: | |
| :ledger:[Pro](#pro)              | 1016063<br>219366         |  |  | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :orange_book:[Pro++](#proplus)    | 1243297<br>256308 |  | :green_circle: | :green_circle: | :green_circle: | :green_circle: |:yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :closed_book:[Ultimate](#ultimate)    | 1342108<br>316007 | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |
           
:green_circle: contains the list named in the column caption       
:yellow_square: partially contains the list named in the column caption       
    
#### ***Blocking level:***
| Version | Blocking<br>level | Blocking<br>type |
|:--------|:---------------|:--------------|
| :green_book:[Light](#light)        | :green_book::green_book:                                                                    | Relaxed             |
| :blue_book:[Normal](#normal)       | :blue_book::blue_book::blue_book:                                                           | Relaxed/Balanced    |
| :ledger:[Pro](#pro)                | :ledger::ledger::ledger::ledger:                                                            | Balanced            |
| :orange_book:[Pro++](#proplus)     | :orange_book::orange_book::orange_book::orange_book::orange_book::orange_book:              | Balanced/Aggressive |
| :closed_book:[Ultimate](#ultimate) | :closed_book::closed_book::closed_book::closed_book::closed_book::closed_book::closed_book: | Aggressive |
	
### :bulb: ***For a recommendation, see:*** *[Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)*

---
         
### :green_book: ***Multi LIGHT*** - **Basic protection** <a name="light"></a>
      
*Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics, some Malware and Fake.*
          
***NOTE:*** *Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.*
		  
**Entries:** *237434 domains/hosts - 68967 compressed domains*                    
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/light.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/light.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/light.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/light.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/light.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/light.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/light-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/light-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/light.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/light.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/light-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/light.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/light.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| PAC | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/pac/light.pac) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/pac/light.pac) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/pac/light.pac) | Proxy Auto Configuration |

### :blue_book: ***Multi NORMAL*** - **All-round protection** <a name="normal"></a>
      
*Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
***NOTE:*** *Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.*
		  
**Entries:** *766838 domains/hosts - 135457 compressed domains*                   
          
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/multi.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/multi.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/multi.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/multi.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/multi.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/multi.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/multi-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/multi-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/multi.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/multi.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/multi-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/multi.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/multi.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/multi.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :ledger: ***Multi PRO*** - **Extended protection (Recommended)** <a name="pro"></a>
      
*Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1016063 domains/hosts - 219366 compressed domains*                   
           
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/pro.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/pro.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/pro.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/pro.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/pro.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/pro-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/pro.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/pro.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/pro-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/pro.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/pro.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :orange_book: ***Multi PRO++*** - **Maximum protection** <a name="proplus"></a>

*Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
*More aggressive version of the Multi PRO blocklist. It may contain few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *1243297 domains/hosts - 256308 compressed domains*               
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/pro.plus.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/pro.plus.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/pro.plus.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.plus.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/pro.plus.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/pro.plus.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.plus-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/pro.plus-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/pro.plus.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/pro.plus.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/pro.plus-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/pro.plus.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.plus.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/pro.plus.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                  
### :closed_book: ***Multi ULTIMATE*** - **Aggressive protection** <a name="ultimate"></a>

*Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Coins and other "Crap".*
         
*Stricter version of the Multi PRO++ blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*
         
***NOTE:*** *META trackers are blocked in Ultimate. This restricts the use of Facebook/Instagram and Facebook Messenger apps. To use Facebook/Instagram apps with Ultimate, unblock the following domains: [META Tracker](share/facebook.txt)*
       
**Entries:** *1342108 domains/hosts - 316007 compressed domains*               
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/ultimate.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/ultimate.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/ultimate.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/ultimate.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/ultimate.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/ultimate.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/ultimate-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/ultimate-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/ultimate-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/ultimate.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/ultimate.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/ultimate-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/ultimate-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/ultimate.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/ultimate.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/ultimate.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                         
**Expires:** *24 hours (update frequency)*

---

### :trollface: ***Fake - Protects against internet scams, traps & fakes!*** <a name="fake"></a>
*A blocklist for blocking fake stores, -streaming, rip-offs, cost traps and co.*         
        
|             | Light | Normal          | Pro            | Pro++          | Ultimate       | TIF            |
|:-----------:|:-----:|:---------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x:   | :yellow_square: | :green_circle: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *15433 compressed domains*           
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/fake.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/fake.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/fake.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/fake.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/fake.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/fake-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/fake-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/fake.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/fake.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/fake.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/fake-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/fake.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/fake.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/fake.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :tada: ***Pop-Up Ads - Protects against annoying pop-up ads!*** <a name="popupads"></a>
*A blocklist for blocking pop-up ads.*         
        
|             | Light          | Normal         | Pro            | Pro++          | Ultimate       |
|:-----------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *76309 compressed domains*           
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/popupads.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/popupads.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/popupads.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/popupads.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/popupads.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/popupads.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/popupads-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/popupads-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/popupads-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/popupads.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/popupads.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/popupads.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/popupads.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/popupads.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/popupads.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/popupads-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/popupads-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/popupads-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/popupads.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/popupads.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/popupads.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *24 hours (update frequency)*

---

### :closed_lock_with_key: ***Threat Intelligence Feeds - Increases security significantly! (Recommended)*** <a name="tif"></a>
*A blocklist for blocking malware, cryptojacking, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no
              		
**Entries:** *855532 domains/hosts - 530126 compressed domains*           
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/tif.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/tif.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/tif.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/tif.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/tif.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/tif-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/tif.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/tif.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/tif-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/tif.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/tif.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *24 hours (update frequency)*
      
**An IPv4 list in [IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/tif.txt) and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif-ips.txt) are also available as an extension to the TIF list.**
      
---

### :outbox_tray: ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!*** <a name="bypass"></a>

*Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS (TCP 853) outbound.*
          
***The block list exists in two versions:***

#### ***Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies*** <a name="bypass_all"></a>
       
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *2910 compressed domains*           
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh-vpn-proxy-bypass.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/doh-vpn-proxy-bypass.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh-vpn-proxy-bypass.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/doh-vpn-proxy-bypass.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/doh-vpn-proxy-bypass.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh-vpn-proxy-bypass-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/doh-vpn-proxy-bypass-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh-vpn-proxy-bypass.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/doh-vpn-proxy-bypass.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/doh-vpn-proxy-bypass.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh-vpn-proxy-bypass.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/doh-vpn-proxy-bypass.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

#### ***Encrypted DNS Servers only*** <a name="bypass_dns"></a>
       
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *1129 domains/hosts - 976 compressed domains*           
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/doh.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/doh.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/doh.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/doh.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/doh.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/doh-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/doh.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/doh.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/doh-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/doh.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/doh.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :mag: ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!*** <a name="safesearch"></a>
*A blocklist for blocking search engines that do not support safesearch.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *242 compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nosafesearch.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/nosafesearch.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/nosafesearch.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/nosafesearch.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/nosafesearch.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/nosafesearch-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/nosafesearch-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/nosafesearch.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/nosafesearch.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/nosafesearch.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/nosafesearch-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/nosafesearch.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/nosafesearch.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/nosafesearch.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :lock_with_ink_pen: ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!*** <a name="dyndns"></a>
*A blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *1491 compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/dyndns.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/dyndns.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/dyndns.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/dyndns.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/dyndns.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/dyndns.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/dyndns-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/dyndns-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/dyndns.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/dyndns.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/dyndns.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/dyndns-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/dyndns.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/dyndns.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/dyndns.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :computer: ***Badware Hoster blocking - Protects against the malicious use of free host services!*** <a name="hoster"></a>
*A blocklist for blocking known free hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.*         
                      
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *1983 compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/hoster.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/hoster.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/hoster.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/hoster.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/hoster.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/hoster.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/hoster-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/hoster-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/hoster-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/hoster.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/hoster.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/hoster.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/hoster.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/hoster.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/hoster-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/hoster-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/hoster.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/hoster.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/hoster.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :crystal_ball: ***Most Abused TLDs - Protects against known malicious Top Level Domains!*** <a name="tlds"></a>
*A blocklist for blocking Top Most Abused Top Level Domains, merged from @Yokoffing, @DandelionSprout, @LennyFox and SpamHaus.*         
            
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| AdGuard | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-ublock.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/spam-tlds-ublock.txt) | uBlock |
| AdBlock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-adblock.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-adblock.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/spam-tlds-adblock.txt) | Pi-hole, AdBlock, TechnitiumDNS<br>*Only TLDs that do not have any exclusions!* |

**Expires:** *Updated regularly*

---

### :skull: ***Anti Piracy - Protects against piracy!*** <a name="piracy"></a>
*Blocks websites and services that are mainly used for illegal distribution of copyrighted content.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *10207 compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/anti.piracy.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/anti.piracy.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/anti.piracy.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/anti.piracy.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/anti.piracy.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/anti.piracy.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/anti.piracy-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/anti.piracy-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/anti.piracy-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/anti.piracy.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/anti.piracy.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/anti.piracy.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/anti.piracy.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/anti.piracy.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/anti.piracy-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/anti.piracy-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/anti.piracy.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/anti.piracy.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/anti.piracy.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :slot_machine: ***Gambling - Protects against gambling content!*** <a name="gambling"></a>
*Blocks gambling content.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *193098 compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/gambling.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/gambling.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/gambling.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/gambling.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/gambling.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/gambling.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/gambling-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/gambling-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/gambling.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/gambling.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/gambling.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/gambling-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/gambling.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/gambling.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/gambling.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :calling: ***Native Tracker - Broadband tracker of devices, services and operating systems*** <a name="native"></a>
*Blocks native broadband tracker from devices, services and operating systems that track your activity.*         
                         
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :yellow_square:   | :yellow_square:    | :yellow_square: | :yellow_square:  | :green_circle:      |

:green_circle: yes :yellow_square: partially :x: no
		
| Device/Service | Domains | Hosts | Adblock | Unbound | DNSMasq<br>v2.86+ | DNSMasq<br>v2.85- | Wildcard<br>Asterisk | Wildcard<br>Domains | RPZ |
|:-------|:--------:|:------:|:--------:|:--------:|:--------:|:---------:|:--------:|:--------:|:--------:|
| Amazon (Devices, Shopping, Video) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.amazon.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.amazon.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.amazon.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.amazon.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.amazon.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.amazon.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.amazon.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.amazon-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.amazon-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.amazon-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.amazon.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.amazon-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.amazon-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.amazon-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.amazon.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.amazon.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.amazon.txt) |
| Apple (iOS, macOS, tvOS) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.apple.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.apple.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.apple.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.apple-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.apple-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.apple-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.apple-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.apple-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.apple.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.apple.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.apple.txt) |
| Huawei (Devices) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.huawei.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.huawei.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.huawei.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.huawei-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.huawei-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.huawei-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.huawei-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.huawei-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.huawei-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.huawei.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.huawei.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.winoffice.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.winoffice.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.winoffice.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.winoffice-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.winoffice-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.winoffice-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.winoffice-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.winoffice-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.winoffice.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.winoffice.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.winoffice.txt) |
| TikTok (Fingerprinting) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.tiktok.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.tiktok.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.tiktok.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.tiktok-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.tiktok-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.tiktok.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.tiktok.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.tiktok.txt) |
| TikTok (Fingerprinting) Aggressive | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.tiktok.extended.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.tiktok.extended.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.tiktok.extended.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.tiktok.extended.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.tiktok.extended.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.tiktok.extended.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.tiktok.extended.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok.extended-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok.extended-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.tiktok.extended-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.tiktok.extended.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok.extended-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.extended-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.tiktok.extended-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.tiktok.extended.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.tiktok.extended.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.tiktok.extended.txt) |
| LG webOS | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.lgwebos.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.lgwebos.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.lgwebos.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.lgwebos-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.lgwebos-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.lgwebos-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.lgwebos-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.lgwebos-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.lgwebos-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.lgwebos.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.lgwebos.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.lgwebos.txt) |
| Vivo (BETA) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.vivo.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.vivo.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.vivo.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.vivo.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.vivo.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.vivo.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.vivo.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.vivo-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.vivo-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.vivo-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.vivo.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.vivo-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.vivo-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.vivo-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.vivo.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.vivo.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.vivo.txt) |
| OPPO/Realme (BETA) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/domains/native.oppo-realme.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/hosts/native.oppo-realme.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/adblock/native.oppo-realme.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.oppo-realme.blacklist.conf) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/native.oppo-realme.blacklist.conf) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/unbound/native.oppo-realme.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.oppo-realme.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.oppo-realme-old.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.oppo-realme-old.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/dnsmasq/native.oppo-realme-old.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.oppo-realme.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.oppo-realme-onlydomains.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.oppo-realme-onlydomains.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/wildcard/native.oppo-realme-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.oppo-realme.txt) [Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.oppo-realme.txt) [jsDelivr](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@main/rpz/native.oppo-realme.txt) |

**Expires:** *Updated regularly*

---

### :bulb: ***Recommendation*** <a name="recommendation"></a>

*As a network-wide DNS blocker, I recommend using [Adguard Home](https://adguard.com), [Pi-hole](https://pi-hole.net/), [TechnitiumDNS](https://technitium.com/dns/), [Blocky](https://github.com/0xERR0R/blocky) (advanced users), [adblock-lean](https://github.com/lynxthecat/adblock-lean) (OpenWrt) or [eBlocker](https://eblocker.org/).*
            
*DNS blocker offer a good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!         
Therefore, I* ***additionally*** *recommend the use of a browser content blocker such as [AdGuard](https://adguard.com), [uBlock](https://ublockorigin.com) or [Ghostery](https://www.ghostery.com/).*
                     
*Check out yokoffing's [Recommended Filters for uBlock Origin](https://github.com/yokoffing/filterlists) for content blocker filter lists.*
*For a browser recommendation see also yokoffing's [I need a browser with ad blocking. Which one should I choose?](https://github.com/yokoffing/NextDNS-Config#i-need-a-browser-with-ad-blocking-which-one-should-i-choose)*

#### :information_desk_person: Which version of the lists should I use? <a name="whatshouldiuse"></a>

- *Use [Light](#light) if you have to pay attention to the size of the list, because the AdBlocker does not support large lists, or light protection is sufficient for you.*
- *Use [Normal](#normal) if there is no admin nearby who can unblock something from time to time. E.g. for grandma and grandpa or the whole home or family network.*
- *Use [Pro](#pro) if an admin is available who could unblock something if necessary. My personal recommendation for almost problem-free adblocking.*
- *Use [Pro++](#proplus) if you are an experienced user, know what you are doing and privacy is important to you. This is an aggressive list and you may need to unblock things more often.*
- *Use [Ultimate](#ultimate) if Pro++ is not enough for you.*
- *Use [Ultimate](#ultimate) with [1Hosts Pro*](https://github.com/badmojr/1Hosts#1hosts-pro) if Ultimate alone is not enough. You will have to unblock a lot yourself.*
- *Is [Ultimate](#ultimate) + [1Hosts Pro*](https://github.com/badmojr/1Hosts#1hosts-pro) still not enough for you? You are crazy Sir UnblockALot, well then combine Ultimate with [1Hosts Xtra*](https://github.com/badmojr/1Hosts#1hosts-xtra). But you should schedule enough time for unblocking, or better hire a full-time admin.*

\* *NOTE: The [1Hosts](https://github.com/badmojr/1Hosts) lists are currently only maintained irregularly, see also: [Competing Demands Causing Maintenance Slowdown](https://github.com/badmojr/1Hosts/issues/1307)*

*Another recommendation is to combine the main lists with the [Threat Intelligence Feeds](#tif) list if possible.*

***Further additional options to the main lists depending on the use case are:***
      
- ***Security:*** *In addition to the [Threat Intelligence Feeds](#tif) list, use the [Dynamic DNS](#dyndns), [Badware Hoster](#hoster) and [Most Abused TLDs](#tlds) list to further protect yourself from malicious things.*
- ***Protection of children:*** *Use the [Gambling](#gambling), [Anti Piracy](#piracy), [Safesearch](#safesearch), [DoH/VPN/TOR/Proxy Bypass](#bypass) and [oisd NSFW](https://oisd.nl/setup) lists in addition to block gambling, piracy, no safesearch engines, DNS bypassing, porn, shock and adult sites.*

---

### :department_store: ***Online DNS Services*** <a name="dnsservices"></a>        

*If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then I recommend one of the following DNS services:*

### :round_pushpin: ***AdGuardDNS - limited free/paid*** <a name="adguarddns"></a>        
          
*In [AdGuardDNS](https://adguard-dns.io) you can use my Multi Normal, Pro, Pro++, Ultimate, TIF, Gambling, Anti Piracy, DoH/VPN/TOR/Proxy Bypass, DynDNS list and the Allowlist Referral.*

### :round_pushpin: ***ControlD - free/paid*** <a name="controld"></a>

*In [ControlD](https://controld.com/free-dns) you can use [my blocklists](https://docs.controld.com/docs/free-dns):*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:-------------|
| Light | `https://freedns.controld.com/x-hagezi-light` | `x-hagezi-light.freedns.controld.com` |
| Normal | `https://freedns.controld.com/x-hagezi-normal` | `x-hagezi-normal.freedns.controld.com` |
| Pro | `https://freedns.controld.com/x-hagezi-pro` | `x-hagezi-pro.freedns.controld.com` |
| Pro Plus | `https://freedns.controld.com/x-hagezi-proplus` | `x-hagezi-proplus.freedns.controld.com` |
| Ultimate | `https://freedns.controld.com/x-hagezi-ultimate` | `x-hagezi-ultimate.freedns.controld.com` |
| TIF | `https://freedns.controld.com/x-hagezi-tif` | `x-hagezi-tif.freedns.controld.com` |

### :round_pushpin: ***NextDNS - limited free/paid*** <a name="nextdns"></a>        

*In [NextDNS](https://nextdns.io) you can use my Light, Normal, Pro, Pro++ and Ultimate list.*
               
*Check out Yokoffing [NextDNS Config Guide](https://github.com/yokoffing/NextDNS-Config) and Techlore Video [The ULTIMATE Guide to Mastering NextDNS!](https://youtu.be/WUG57ynLb8I) for recommended [NextDNS](https://nextdns.io) configuration settings.*

### :round_pushpin: ***RethinkDNS - free*** <a name="rethinkdns"></a>

*In [RethinkDNS](https://rethinkdns.com) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF list.*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC | Apple Mobileconfig |
|:-----------|:---------------|:-------------|:-------------------|
| Light + TIF | `https://sky.rethinkdns.com/1:AAkACAQA` | `1-aaeqacaeaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAkACAQA) and click on the red apple  |
| Normal + TIF | `https://sky.rethinkdns.com/1:AAkACAgA` | `1-aaeqacaiaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAkACAgA) and click on the red apple  |
| Pro + TIF  | `https://sky.rethinkdns.com/1:AAoACBAA` | `1-aafaacaqaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACBAA) and click on the red apple  |
| Pro plus + TIF | `https://sky.rethinkdns.com/1:AAoACAgA` | `1-aafaacaiaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACAgA) and click on the red apple |
| Ultimate + TIF | `https://sky.rethinkdns.com/1:gAgACABA` | `1-qaeaacaaia.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:gAgACABA) and click on the red apple |
            
### :round_pushpin: ***DNSwarden - free*** <a name="dnswarden"></a>

*In [DNSwarden](https://dnswarden.com/customfilter.html) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF list.*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:------------------|
| Light + TIF | `https://dns.dnswarden.com/00000000000000000000048` | `00000000000000000000048.dns.dnswarden.com` |
| Normal + TIF | `https://dns.dnswarden.com/00000000000000000000028` | `00000000000000000000028.dns.dnswarden.com` |
| Pro + TIF  | `https://dns.dnswarden.com/00000000000000000000018` | `00000000000000000000018.dns.dnswarden.com` |
| Pro plus + TIF | `https://dns.dnswarden.com/0000000000000000000000o` | `0000000000000000000000o.dns.dnswarden.com` |
| Ultimate + TIF | `https://dns.dnswarden.com/0000000000000000000000804` | `0000000000000000000000804.dns.dnswarden.com` |

### :round_pushpin: ***DNSforge (Germany) - free*** <a name="dnsforge"></a>

*[DNSforge](https://dnsforge.de/) use my Multi Light blocklist in addition to other blocklists.*
          
### :round_pushpin: ***OpenBLD.net - free*** <a name="openbld"></a>

*[OpenBLD.net](https://openbld.net) use my Multi Pro blocklist in addition to other blocklists.*

---

### :loudspeaker: ***About*** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists&max=1" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

*The blocklists are based on [various sources](sources.md) and my own denylists/extensions. They were designed to avoid false positive domains as much as possible without losing effectiveness and efficiency. Dead hosts are regularly removed from the lists to keep them as small as possible.            
Made with :heartbeat: for a safer and cleaner internet.*         
                  
*All lists were tested against 10000 websites from the Cisco Umbrella Top 1 million list. It was checked whether the pages load, the page content is displayed correctly, navigation links work, images load, videos start and much more.*                 
                      
*They are updated and maintained daily.*

*No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas. See also: [Which sources are used for the lists and how are the lists compiled on the basis of these sources?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#sources)*                   
     
*The results of a test against the 10000 [whotracks.me](https://whotracks.me/websites.html) pages. All pages were opened and fully loaded via batch in Edge with privacy features turned off. Cookies were all accepted. NextDNS was used as the DNS.*

| **List**     | Total queries | Blocked queries | % blocked | % gap to light |
|-------------:|--------------:|----------------:|----------:|---------------:|
| **Ultimate** | 299646        | 131093          | 43.75     | 12.85          |
| **Pro++**    | 299646        | 119681          | 39.94     | 9.05           |
| **Pro**      | 299646        | 97508           | 32.54     | 1.65           |
| **Normal**   | 299646        | 93258           | 31.12     | 0.23           |
| **Light**    | 299646        | 92576           | 30.90     |                |
| **----**     | 299646        | 67888           | 22.66     | -8.24          |
                 
*Test them, give feedback and [report blockable or incorrectly blocked](https://github.com/hagezi/dns-blocklists/issues) domains.*

#### :email: Contact <a name="contact"></a>

| Telegram | Discord | Reddit | Mail |
|:---------:|:--------:|:------:|:-----:|
| [@hagezi](https://t.me/hagezi) | hagezi | [u/hagezi](https://www.reddit.com/user/hagezi) | hagezi@protonmail.com |

#### :family: Groups <a name="groups"></a>

| Telegram | Discord |
|:---------:|:-----:|
[Link](https://t.me/hagezi_g) | [CipherOps' Pi-hole & AdGuard Home](https://discord.gg/jg9CKkhC7M) |

#### :octocat: Repository <a name="repository"></a>

*The repository is occasionally compressed (reinitialised) to reduce the overall size. Among other things, this invalidates forks and cleans up the commit history.*

#### :cyclone: Referral Domains <a name="referral"></a>

*Affiliate and tracking links (referral domains) that appear frequently on offer web pages like Slickdeals, in emails or in search results are allowed in my lists. These are mostly called only after manual clicking on a link and are not used to display advertising.
If these are blocked, the first hit links from search results, for example, no longer work. Furthermore, some of these domains are also used to unsubscribe from newsletters.* 
          
*See also: [Why are referral domains (affiliate and tracking links) not blocked in the lists?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)*
          
#### :dizzy: Support Me <a name="support"></a>
                                  
*If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!* 
                                
*Give feedback, show me your ideas, report domains to be blocked, report false positive domains and help to keep the internet safe and clean.*               
*Help and cooperation of any kind is welcome!*
         
***Thanks for your support!***

---

#### :stars: Stargazers <a name="stargazers"></a>

[![Star History Chart](https://api.star-history.com/svg?repos=hagezi/dns-blocklists&type=Date)](https://star-history.com/#hagezi/dns-blocklists&Date)

---

### ***Keep the internet clean!***

---

[![https://gafam.info](https://ptrace.gafam.info/unofficial/img/color/lqdn-gafam-poster-en-color-5x1-2560x.png)](https://gafam.info)

---