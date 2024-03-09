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
9. [Threat Intelligence Feeds](#tif) - *Increases security significantly! (Recommended)* : [Full](#tif) - [Medium](#tifmedium) - [IPs](#tifips)
10. [DoH/VPN/TOR/Proxy Bypass](#bypass) - *Prevent methods to bypass your DNS!* : [Full](#bypass_all) - [DoH only](#bypass_dns)
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
| :green_book:[Light](#light)             | light_dh<br>light_cp     |  |   |   |  |  | :yellow_square: |  :yellow_square: | | |
| :blue_book:[Normal](#normal)       | multi_dh<br>multi_cp     |  |   |  | :green_circle: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: | |
| :ledger:[Pro](#pro)              | pro_dh<br>pro_cp         |  |  | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :orange_book:[Pro++](#proplus)    | proplus_dh<br>proplus_cp |  | :green_circle: | :green_circle: | :green_circle: | :green_circle: |:yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :closed_book:[Ultimate](#ultimate)    | ultimate_dh<br>ultimate_cp | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |
           
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
		  
**Entries:** *light_dh domains/hosts - light_cp compressed domains*                    
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/light.txt) [Mirror](lnkgl_d/light.txt) [jsDelivr](lnkjd_d/light.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/light.txt) [Mirror](lnkgl_h/light.txt) [jsDelivr](lnkjd_h/light.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/light.txt) [Mirror](lnkgl_a/light.txt) [jsDelivr](lnkjd_a/light.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/light.blacklist.conf) [Mirror](lnkgl_u/light.blacklist.conf) [jsDelivr](lnkjd_u/light.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/light-old.txt) [Mirror](lnkgl_m/light-old.txt) [jsDelivr](lnkjd_m/light-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/light.txt) [Mirror](lnkgl_m/light.txt) [jsDelivr](lnkjd_m/light.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/light.txt) [Mirror](lnkgl_w/light.txt) [jsDelivr](lnkjd_w/light.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/light-onlydomains.txt) [Mirror](lnkgl_w/light-onlydomains.txt) [jsDelivr](lnkjd_w/light-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/light.txt) [Mirror](lnkgl_r/light.txt) [jsDelivr](lnkjd_r/light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| PAC | [Link](lnkgh_p/light.pac) [Mirror](lnkgl_p/light.pac) [jsDelivr](lnkjd_p/light.pac) | Proxy Auto Configuration |

### :blue_book: ***Multi NORMAL*** - **All-round protection** <a name="normal"></a>
      
*Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
***NOTE:*** *Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.*
		  
**Entries:** *multi_dh domains/hosts - multi_cp compressed domains*                   
          
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/multi.txt) [Mirror](lnkgl_d/multi.txt) [jsDelivr](lnkjd_d/multi.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/multi.txt) [Mirror](lnkgl_h/multi.txt) [jsDelivr](lnkjd_h/multi.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/multi.txt) [Mirror](lnkgl_a/multi.txt) [jsDelivr](lnkjd_a/multi.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/multi.blacklist.conf) [Mirror](lnkgl_u/multi.blacklist.conf) [jsDelivr](lnkjd_u/multi.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/multi-old.txt) [Mirror](lnkgl_m/multi-old.txt) [jsDelivr](lnkjd_m/multi-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/multi.txt) [Mirror](lnkgl_m/multi.txt) [jsDelivr](lnkjd_m/multi.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/multi.txt) [Mirror](lnkgl_w/multi.txt) [jsDelivr](lnkjd_w/multi.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/multi-onlydomains.txt) [Mirror](lnkgl_w/multi-onlydomains.txt) [jsDelivr](lnkjd_w/multi-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/multi.txt) [Mirror](lnkgl_r/multi.txt) [jsDelivr](lnkjd_r/multi.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :ledger: ***Multi PRO*** - **Extended protection (Recommended)** <a name="pro"></a>
      
*Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *pro_dh domains/hosts - pro_cp compressed domains*                   
           
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/pro.txt) [Mirror](lnkgl_d/pro.txt) [jsDelivr](lnkjd_d/pro.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/pro.txt) [Mirror](lnkgl_h/pro.txt) [jsDelivr](lnkjd_h/pro.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/pro.txt) [Mirror](lnkgl_a/pro.txt) [jsDelivr](lnkjd_a/pro.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/pro.blacklist.conf) [Mirror](lnkgl_u/pro.blacklist.conf) [jsDelivr](lnkjd_u/pro.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/pro-old.txt) [Mirror](lnkgl_m/pro-old.txt) [jsDelivr](lnkjd_m/pro-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/pro.txt) [Mirror](lnkgl_m/pro.txt) [jsDelivr](lnkjd_m/pro.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.txt) [Mirror](lnkgl_w/pro.txt) [jsDelivr](lnkjd_w/pro.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro-onlydomains.txt) [Mirror](lnkgl_w/pro-onlydomains.txt) [jsDelivr](lnkjd_w/pro-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.txt) [Mirror](lnkgl_r/pro.txt) [jsDelivr](lnkjd_r/pro.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :orange_book: ***Multi PRO++*** - **Maximum protection** <a name="proplus"></a>

*Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
*More aggressive version of the Multi PRO blocklist. It may contain few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *proplus_dh domains/hosts - proplus_cp compressed domains*               
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/pro.plus.txt) [Mirror](lnkgl_d/pro.plus.txt) [jsDelivr](lnkjd_d/pro.plus.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/pro.plus.txt) [Mirror](lnkgl_h/pro.plus.txt) [jsDelivr](lnkjd_h/pro.plus.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/pro.plus.txt) [Mirror](lnkgl_a/pro.plus.txt) [jsDelivr](lnkjd_a/pro.plus.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/pro.plus.blacklist.conf) [Mirror](lnkgl_u/pro.plus.blacklist.conf) [jsDelivr](lnkjd_u/pro.plus.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/pro.plus-old.txt) [Mirror](lnkgl_m/pro.plus-old.txt) [jsDelivr](lnkjd_m/pro.plus-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/pro.plus.txt) [Mirror](lnkgl_m/pro.plus.txt) [jsDelivr](lnkjd_m/pro.plus.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/pro.plus.txt) [Mirror](lnkgl_w/pro.plus.txt) [jsDelivr](lnkjd_w/pro.plus.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/pro.plus-onlydomains.txt) [Mirror](lnkgl_w/pro.plus-onlydomains.txt) [jsDelivr](lnkjd_w/pro.plus-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/pro.plus.txt) [Mirror](lnkgl_r/pro.plus.txt) [jsDelivr](lnkjd_r/pro.plus.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                  
### :closed_book: ***Multi ULTIMATE*** - **Aggressive protection** <a name="ultimate"></a>

*Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Coins and other "Crap".*
         
*Stricter version of the Multi PRO++ blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*
         
***NOTE:*** *META trackers are blocked in Ultimate. This restricts the use of Facebook/Instagram and Facebook Messenger apps. To use Facebook/Instagram apps with Ultimate, unblock the following domains: [META Tracker](share/facebook.txt)*
       
**Entries:** *ultimate_dh domains/hosts - ultimate_cp compressed domains*               
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/ultimate.txt) [Mirror](lnkgl_d/ultimate.txt) [jsDelivr](lnkjd_d/ultimate.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/ultimate.txt) [Mirror](lnkgl_h/ultimate.txt) [jsDelivr](lnkjd_h/ultimate.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/ultimate.txt) [Mirror](lnkgl_a/ultimate.txt) [jsDelivr](lnkjd_a/ultimate.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/ultimate.blacklist.conf) [Mirror](lnkgl_u/ultimate.blacklist.conf) [jsDelivr](lnkjd_u/ultimate.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/ultimate-old.txt) [Mirror](lnkgl_m/ultimate-old.txt) [jsDelivr](lnkjd_m/ultimate-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/ultimate.txt) [Mirror](lnkgl_m/ultimate.txt) [jsDelivr](lnkjd_m/ultimate.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/ultimate.txt) [Mirror](lnkgl_w/ultimate.txt) [jsDelivr](lnkjd_w/ultimate.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/ultimate-onlydomains.txt) [Mirror](lnkgl_w/ultimate-onlydomains.txt) [jsDelivr](lnkjd_w/ultimate-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/ultimate.txt) [Mirror](lnkgl_r/ultimate.txt) [jsDelivr](lnkjd_r/ultimate.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                         
**Expires:** *24 hours (update frequency)*

---

### :trollface: ***Fake - Protects against internet scams, traps & fakes!*** <a name="fake"></a>
*A blocklist for blocking fake stores, -streaming, rip-offs, cost traps and co.*         
        
|             | Light | Normal          | Pro            | Pro++          | Ultimate       | TIF            |
|:-----------:|:-----:|:---------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x:   | :yellow_square: | :green_circle: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *fake_cp compressed domains*           
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/fake.txt) [Mirror](lnkgl_a/fake.txt) [jsDelivr](lnkjd_a/fake.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/fake.blacklist.conf) [Mirror](lnkgl_u/fake.blacklist.conf) [jsDelivr](lnkjd_u/fake.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/fake-old.txt) [Mirror](lnkgl_m/fake-old.txt) [jsDelivr](lnkjd_m/fake-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/fake.txt) [Mirror](lnkgl_m/fake.txt) [jsDelivr](lnkjd_m/fake.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/fake.txt) [Mirror](lnkgl_w/fake.txt) [jsDelivr](lnkjd_w/fake.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/fake-onlydomains.txt) [Mirror](lnkgl_w/fake-onlydomains.txt) [jsDelivr](lnkjd_w/fake-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/fake.txt) [Mirror](lnkgl_r/fake.txt) [jsDelivr](lnkjd_r/fake.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :tada: ***Pop-Up Ads - Protects against annoying pop-up ads!*** <a name="popupads"></a>
*A blocklist for blocking pop-up ads.*         
        
|             | Light          | Normal         | Pro            | Pro++          | Ultimate       |
|:-----------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *popupads_cp compressed domains*           
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/popupads.txt) [Mirror](lnkgl_a/popupads.txt) [jsDelivr](lnkjd_a/popupads.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/popupads.blacklist.conf) [Mirror](lnkgl_u/popupads.blacklist.conf) [jsDelivr](lnkjd_u/popupads.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/popupads-old.txt) [Mirror](lnkgl_m/popupads-old.txt) [jsDelivr](lnkjd_m/popupads-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/popupads.txt) [Mirror](lnkgl_m/popupads.txt) [jsDelivr](lnkjd_m/popupads.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/popupads.txt) [Mirror](lnkgl_w/popupads.txt) [jsDelivr](lnkjd_w/popupads.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/popupads-onlydomains.txt) [Mirror](lnkgl_w/popupads-onlydomains.txt) [jsDelivr](lnkjd_w/popupads-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/popupads.txt) [Mirror](lnkgl_r/popupads.txt) [jsDelivr](lnkjd_r/popupads.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *24 hours (update frequency)*

---

### :closed_lock_with_key: ***Threat Intelligence Feeds - Increases security significantly! (Recommended)*** <a name="tif"></a>
*A blocklist for blocking malware, cryptojacking, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no
              		
**Entries:** *tif_dh domains/hosts - tif_cp compressed domains*           
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/tif.txt) [Mirror](lnkgl_d/tif.txt) [jsDelivr](lnkjd_d/tif.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/tif.txt) [Mirror](lnkgl_h/tif.txt) [jsDelivr](lnkjd_h/tif.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/tif.txt) [Mirror](lnkgl_a/tif.txt) [jsDelivr](lnkjd_a/tif.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/tif.blacklist.conf) [Mirror](lnkgl_u/tif.blacklist.conf) [jsDelivr](lnkjd_u/tif.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/tif-old.txt) [Mirror](lnkgl_m/tif-old.txt) [jsDelivr](lnkjd_m/tif-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/tif.txt) [Mirror](lnkgl_m/tif.txt) [jsDelivr](lnkjd_m/tif.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/tif.txt) [Mirror](lnkgl_w/tif.txt) [jsDelivr](lnkjd_w/tif.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/tif-onlydomains.txt) [Mirror](lnkgl_w/tif-onlydomains.txt) [jsDelivr](lnkjd_w/tif-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/tif.txt) [Mirror](lnkgl_r/tif.txt) [jsDelivr](lnkjd_r/tif.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: ***Threat Intelligence Feeds - Medium version*** <a name="tifmedium"></a>
*A medium version of the Threat Intelligence Feeds list. Designed for Adblockers that have problems with the size of the full TIF list. Contains only important feeds.*         
         
**Entries:** *tif_m_cp compressed domains*           
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/tif.medium.txt) [Mirror](lnkgl_a/tif.medium.txt) [jsDelivr](lnkjd_a/tif.medium.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/tif.medium.blacklist.conf) [Mirror](lnkgl_u/tif.medium.blacklist.conf) [jsDelivr](lnkjd_u/tif.medium.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/tif.medium-old.txt) [Mirror](lnkgl_m/tif.medium-old.txt) [jsDelivr](lnkjd_m/tif.medium-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/tif.medium.txt) [Mirror](lnkgl_m/tif.medium.txt) [jsDelivr](lnkjd_m/tif.medium.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/tif.medium.txt) [Mirror](lnkgl_w/tif.medium.txt) [jsDelivr](lnkjd_w/tif.medium.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/tif.medium-onlydomains.txt) [Mirror](lnkgl_w/tif.medium-onlydomains.txt) [jsDelivr](lnkjd_w/tif.medium-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/tif.medium.txt) [Mirror](lnkgl_r/tif.medium.txt) [jsDelivr](lnkjd_r/tif.medium.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: ***Threat Intelligence Feeds - IPs*** <a name="tifips"></a>
      
**An IPv4 list in [plain IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/tif.txt) and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif-ips.txt) are also available as an extension to the TIF list.**
               
**Expires:** *24 hours (update frequency)*
      
---

### :outbox_tray: ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!*** <a name="bypass"></a>

*Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS (TCP 853) outbound.*
          
***The block list exists in two versions:***

#### ***Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies*** <a name="bypass_all"></a>
       
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *bypass_cp compressed domains*           
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_a/doh-vpn-proxy-bypass.txt) [jsDelivr](lnkjd_a/doh-vpn-proxy-bypass.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/doh-vpn-proxy-bypass.blacklist.conf) [Mirror](lnkgl_u/doh-vpn-proxy-bypass.blacklist.conf) [jsDelivr](lnkjd_u/doh-vpn-proxy-bypass.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/doh-vpn-proxy-bypass-old.txt) [Mirror](lnkgl_m/doh-vpn-proxy-bypass-old.txt) [jsDelivr](lnkjd_m/doh-vpn-proxy-bypass-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_m/doh-vpn-proxy-bypass.txt) [jsDelivr](lnkjd_m/doh-vpn-proxy-bypass.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_w/doh-vpn-proxy-bypass.txt) [jsDelivr](lnkjd_w/doh-vpn-proxy-bypass.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/doh-vpn-proxy-bypass-onlydomains.txt) [Mirror](lnkgl_w/doh-vpn-proxy-bypass-onlydomains.txt) [jsDelivr](lnkjd_w/doh-vpn-proxy-bypass-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/doh-vpn-proxy-bypass.txt) [Mirror](lnkgl_r/doh-vpn-proxy-bypass.txt) [jsDelivr](lnkjd_r/doh-vpn-proxy-bypass.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

#### :outbox_tray: ***Encrypted DNS Servers only*** <a name="bypass_dns"></a>
       
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *bypassdns_dh domains/hosts - bypassdns_cp compressed domains*           
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [Link](lnkgh_d/doh.txt) [Mirror](lnkgl_d/doh.txt) [jsDelivr](lnkjd_d/doh.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [Link](lnkgh_h/doh.txt) [Mirror](lnkgl_h/doh.txt) [jsDelivr](lnkjd_h/doh.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard, Hostfile |
| Adblock | [Link](lnkgh_a/doh.txt) [Mirror](lnkgl_a/doh.txt) [jsDelivr](lnkjd_a/doh.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/doh.blacklist.conf) [Mirror](lnkgl_u/doh.blacklist.conf) [jsDelivr](lnkjd_u/doh.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/doh-old.txt) [Mirror](lnkgl_m/doh-old.txt) [jsDelivr](lnkjd_m/doh-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/doh.txt) [Mirror](lnkgl_m/doh.txt) [jsDelivr](lnkjd_m/doh.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/doh.txt) [Mirror](lnkgl_w/doh.txt) [jsDelivr](lnkjd_w/doh.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/doh-onlydomains.txt) [Mirror](lnkgl_w/doh-onlydomains.txt) [jsDelivr](lnkjd_w/doh-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/doh.txt) [Mirror](lnkgl_r/doh.txt) [jsDelivr](lnkjd_r/doh.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :mag: ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!*** <a name="safesearch"></a>
*A blocklist for blocking search engines that do not support safesearch.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *nosafe_cp compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/nosafesearch.txt) [Mirror](lnkgl_a/nosafesearch.txt) [jsDelivr](lnkjd_a/nosafesearch.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/nosafesearch.blacklist.conf) [Mirror](lnkgl_u/nosafesearch.blacklist.conf) [jsDelivr](lnkjd_u/nosafesearch.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/nosafesearch-old.txt) [Mirror](lnkgl_m/nosafesearch-old.txt) [jsDelivr](lnkjd_m/nosafesearch-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/nosafesearch.txt) [Mirror](lnkgl_m/nosafesearch.txt) [jsDelivr](lnkjd_m/nosafesearch.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/nosafesearch.txt) [Mirror](lnkgl_w/nosafesearch.txt) [jsDelivr](lnkjd_w/nosafesearch.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/nosafesearch-onlydomains.txt) [Mirror](lnkgl_w/nosafesearch-onlydomains.txt) [jsDelivr](lnkjd_w/nosafesearch-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/nosafesearch.txt) [Mirror](lnkgl_r/nosafesearch.txt) [jsDelivr](lnkjd_r/nosafesearch.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :lock_with_ink_pen: ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!*** <a name="dyndns"></a>
*A blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *dyndns_cp compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/dyndns.txt) [Mirror](lnkgl_a/dyndns.txt) [jsDelivr](lnkjd_a/dyndns.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/dyndns.blacklist.conf) [Mirror](lnkgl_u/dyndns.blacklist.conf) [jsDelivr](lnkjd_u/dyndns.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/dyndns-old.txt) [Mirror](lnkgl_m/dyndns-old.txt) [jsDelivr](lnkjd_m/dyndns-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/dyndns.txt) [Mirror](lnkgl_m/dyndns.txt) [jsDelivr](lnkjd_m/dyndns.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/dyndns.txt) [Mirror](lnkgl_w/dyndns.txt) [jsDelivr](lnkjd_w/dyndns.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/dyndns-onlydomains.txt) [Mirror](lnkgl_w/dyndns-onlydomains.txt) [jsDelivr](lnkjd_w/dyndns-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/dyndns.txt) [Mirror](lnkgl_r/dyndns.txt) [jsDelivr](lnkjd_r/dyndns.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :computer: ***Badware Hoster blocking - Protects against the malicious use of free host services!*** <a name="hoster"></a>
*A blocklist for blocking known free hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.*         
                      
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *hoster_cp compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/hoster.txt) [Mirror](lnkgl_a/hoster.txt) [jsDelivr](lnkjd_a/hoster.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/hoster.blacklist.conf) [Mirror](lnkgl_u/hoster.blacklist.conf) [jsDelivr](lnkjd_u/hoster.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/hoster-old.txt) [Mirror](lnkgl_m/hoster-old.txt) [jsDelivr](lnkjd_m/hoster-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/hoster.txt) [Mirror](lnkgl_m/hoster.txt) [jsDelivr](lnkjd_m/hoster.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/hoster.txt) [Mirror](lnkgl_w/hoster.txt) [jsDelivr](lnkjd_w/hoster.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/hoster-onlydomains.txt) [Mirror](lnkgl_w/hoster-onlydomains.txt) [jsDelivr](lnkjd_w/hoster-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/hoster.txt) [Mirror](lnkgl_r/hoster.txt) [jsDelivr](lnkjd_r/hoster.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

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
| AdGuard | [Link](lnkgh_a/spam-tlds.txt) [Mirror](lnkgl_a/spam-tlds.txt) [jsDelivr](lnkjd_a/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock  | [Link](lnkgh_a/spam-tlds-ublock.txt) [Mirror](lnkgl_a/spam-tlds-ublock.txt) [jsDelivr](lnkjd_a/spam-tlds-ublock.txt) | uBlock |
| AdBlock  | [Link](lnkgh_a/spam-tlds-adblock.txt) [Mirror](lnkgl_a/spam-tlds-adblock.txt) [jsDelivr](lnkjd_a/spam-tlds-adblock.txt) | Pi-hole, AdBlock, TechnitiumDNS<br>*Only TLDs that do not have any exclusions!* |
| RPZ | [Link](lnkgh_r/spam-tlds-rpz.txt) [Mirror](lnkgl_r/spam-tlds-rpz.txt) [jsDelivr](lnkjd_r/spam-tlds-rpz.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :skull: ***Anti Piracy - Protects against piracy!*** <a name="piracy"></a>
*Blocks websites and services that are mainly used for illegal distribution of copyrighted content.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *piracy_cp compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/anti.piracy.txt) [Mirror](lnkgl_a/anti.piracy.txt) [jsDelivr](lnkjd_a/anti.piracy.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/anti.piracy.blacklist.conf) [Mirror](lnkgl_u/anti.piracy.blacklist.conf) [jsDelivr](lnkjd_u/anti.piracy.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/anti.piracy-old.txt) [Mirror](lnkgl_m/anti.piracy-old.txt) [jsDelivr](lnkjd_m/anti.piracy-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/anti.piracy.txt) [Mirror](lnkgl_m/anti.piracy.txt) [jsDelivr](lnkjd_m/anti.piracy.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/anti.piracy.txt) [Mirror](lnkgl_w/anti.piracy.txt) [jsDelivr](lnkjd_w/anti.piracy.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/anti.piracy-onlydomains.txt) [Mirror](lnkgl_w/anti.piracy-onlydomains.txt) [jsDelivr](lnkjd_w/anti.piracy-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/anti.piracy.txt) [Mirror](lnkgl_r/anti.piracy.txt) [jsDelivr](lnkjd_r/anti.piracy.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### :slot_machine: ***Gambling - Protects against gambling content!*** <a name="gambling"></a>
*Blocks gambling content.*         
        
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no
		
**Entries:** *gambling_cp compressed domains*                     
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock | [Link](lnkgh_a/gambling.txt) [Mirror](lnkgl_a/gambling.txt) [jsDelivr](lnkjd_a/gambling.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam, Little Snitch Mini |
| Unbound | [Link](lnkgh_u/gambling.blacklist.conf) [Mirror](lnkgl_u/gambling.blacklist.conf) [jsDelivr](lnkjd_u/gambling.blacklist.conf) | Unbound |
| DNSMasq<br>v2.85- | [Link](lnkgh_m/gambling-old.txt) [Mirror](lnkgl_m/gambling-old.txt) [jsDelivr](lnkjd_m/gambling-old.txt) | DNSMasq (v2.85 or older) |
| DNSMasq<br>v2.86+ | [Link](lnkgh_m/gambling.txt) [Mirror](lnkgl_m/gambling.txt) [jsDelivr](lnkjd_m/gambling.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [Link](lnkgh_w/gambling.txt) [Mirror](lnkgl_w/gambling.txt) [jsDelivr](lnkjd_w/gambling.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [Link](lnkgh_w/gambling-onlydomains.txt) [Mirror](lnkgl_w/gambling-onlydomains.txt) [jsDelivr](lnkjd_w/gambling-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](lnkgh_r/gambling.txt) [Mirror](lnkgl_r/gambling.txt) [jsDelivr](lnkjd_r/gambling.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

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
| Amazon (Devices, Shopping, Video) | [Link](lnkgh_d/native.amazon.txt) [Mirror](lnkgl_d/native.amazon.txt) [jsDelivr](lnkjd_d/native.amazon.txt) | [Link](lnkgh_h/native.amazon.txt) [Mirror](lnkgl_h/native.amazon.txt) [jsDelivr](lnkjd_h/native.amazon.txt) | [Link](lnkgh_a/native.amazon.txt) [Mirror](lnkgl_a/native.amazon.txt) [jsDelivr](lnkjd_a/native.amazon.txt) | [Link](lnkgh_u/native.amazon.blacklist.conf) [Mirror](lnkgl_u/native.amazon.blacklist.conf) [jsDelivr](lnkjd_u/native.amazon.blacklist.conf) | [Link](lnkgh_m/native.amazon.txt) [Mirror](lnkgl_m/native.amazon.txt) [jsDelivr](lnkjd_m/native.amazon.txt) | [Link](lnkgh_m/native.amazon-old.txt) [Mirror](lnkgl_m/native.amazon-old.txt) [jsDelivr](lnkjd_m/native.amazon-old.txt) | [Link](lnkgh_w/native.amazon.txt) [Mirror](lnkgl_w/native.amazon.txt) [jsDelivr](lnkjd_w/native.amazon.txt) | [Link](lnkgh_w/native.amazon-onlydomains.txt) [Mirror](lnkgl_w/native.amazon-onlydomains.txt) [jsDelivr](lnkjd_w/native.amazon-onlydomains.txt) | [Link](lnkgh_r/native.amazon.txt) [Mirror](lnkgl_r/native.amazon.txt) [jsDelivr](lnkjd_r/native.amazon.txt) |
| Apple (iOS, macOS, tvOS) | [Link](lnkgh_d/native.apple.txt) [Mirror](lnkgl_d/native.apple.txt) [jsDelivr](lnkjd_d/native.apple.txt) | [Link](lnkgh_h/native.apple.txt) [Mirror](lnkgl_h/native.apple.txt) [jsDelivr](lnkjd_h/native.apple.txt) | [Link](lnkgh_a/native.apple.txt) [Mirror](lnkgl_a/native.apple.txt) [jsDelivr](lnkjd_a/native.apple.txt) | [Link](lnkgh_u/native.apple.blacklist.conf) [Mirror](lnkgl_u/native.apple.blacklist.conf) [jsDelivr](lnkjd_u/native.apple.blacklist.conf) | [Link](lnkgh_m/native.apple.txt) [Mirror](lnkgl_m/native.apple.txt) [jsDelivr](lnkjd_m/native.apple.txt) | [Link](lnkgh_m/native.apple-old.txt) [Mirror](lnkgl_m/native.apple-old.txt) [jsDelivr](lnkjd_m/native.apple-old.txt) | [Link](lnkgh_w/native.apple.txt) [Mirror](lnkgl_w/native.apple.txt) [jsDelivr](lnkjd_w/native.apple.txt) | [Link](lnkgh_w/native.apple-onlydomains.txt) [Mirror](lnkgl_w/native.apple-onlydomains.txt) [jsDelivr](lnkjd_w/native.apple-onlydomains.txt) | [Link](lnkgh_r/native.apple.txt) [Mirror](lnkgl_r/native.apple.txt) [jsDelivr](lnkjd_r/native.apple.txt) |
| Huawei (Devices) | [Link](lnkgh_d/native.huawei.txt) [Mirror](lnkgl_d/native.huawei.txt) [jsDelivr](lnkjd_d/native.huawei.txt) | [Link](lnkgh_h/native.huawei.txt) [Mirror](lnkgl_h/native.huawei.txt) [jsDelivr](lnkjd_h/native.huawei.txt) | [Link](lnkgh_a/native.huawei.txt) [Mirror](lnkgl_a/native.huawei.txt) [jsDelivr](lnkjd_a/native.huawei.txt) | [Link](lnkgh_u/native.huawei.blacklist.conf) [Mirror](lnkgl_u/native.huawei.blacklist.conf) [jsDelivr](lnkjd_u/native.huawei.blacklist.conf) | [Link](lnkgh_m/native.huawei.txt) [Mirror](lnkgl_m/native.huawei.txt) [jsDelivr](lnkjd_m/native.huawei.txt) | [Link](lnkgh_m/native.huawei-old.txt) [Mirror](lnkgl_m/native.huawei-old.txt) [jsDelivr](lnkjd_m/native.huawei-old.txt) | [Link](lnkgh_w/native.huawei.txt) [Mirror](lnkgl_w/native.huawei.txt) [jsDelivr](lnkjd_w/native.huawei.txt) | [Link](lnkgh_w/native.huawei-onlydomains.txt) [Mirror](lnkgl_w/native.huawei-onlydomains.txt) [jsDelivr](lnkjd_w/native.huawei-onlydomains.txt) | [Link](lnkgh_r/native.huawei.txt) [Mirror](lnkgl_r/native.huawei.txt) [jsDelivr](lnkjd_r/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [Link](lnkgh_d/native.winoffice.txt) [Mirror](lnkgl_d/native.winoffice.txt) [jsDelivr](lnkjd_d/native.winoffice.txt) | [Link](lnkgh_h/native.winoffice.txt) [Mirror](lnkgl_h/native.winoffice.txt) [jsDelivr](lnkjd_h/native.winoffice.txt) | [Link](lnkgh_a/native.winoffice.txt) [Mirror](lnkgl_a/native.winoffice.txt) [jsDelivr](lnkjd_a/native.winoffice.txt) | [Link](lnkgh_u/native.winoffice.blacklist.conf) [Mirror](lnkgl_u/native.winoffice.blacklist.conf) [jsDelivr](lnkjd_u/native.winoffice.blacklist.conf) | [Link](lnkgh_m/native.winoffice.txt) [Mirror](lnkgl_m/native.winoffice.txt) [jsDelivr](lnkjd_m/native.winoffice.txt) | [Link](lnkgh_m/native.winoffice-old.txt) [Mirror](lnkgl_m/native.winoffice-old.txt) [jsDelivr](lnkjd_m/native.winoffice-old.txt) | [Link](lnkgh_w/native.winoffice.txt) [Mirror](lnkgl_w/native.winoffice.txt) [jsDelivr](lnkjd_w/native.winoffice.txt) | [Link](lnkgh_w/native.winoffice-onlydomains.txt) [Mirror](lnkgl_w/native.winoffice-onlydomains.txt) [jsDelivr](lnkjd_w/native.winoffice-onlydomains.txt) | [Link](lnkgh_r/native.winoffice.txt) [Mirror](lnkgl_r/native.winoffice.txt) [jsDelivr](lnkjd_r/native.winoffice.txt) |
| TikTok (Fingerprinting) | [Link](lnkgh_d/native.tiktok.txt) [Mirror](lnkgl_d/native.tiktok.txt) [jsDelivr](lnkjd_d/native.tiktok.txt) | [Link](lnkgh_h/native.tiktok.txt) [Mirror](lnkgl_h/native.tiktok.txt) [jsDelivr](lnkjd_h/native.tiktok.txt) | [Link](lnkgh_a/native.tiktok.txt) [Mirror](lnkgl_a/native.tiktok.txt) [jsDelivr](lnkjd_a/native.tiktok.txt) | [Link](lnkgh_u/native.tiktok.blacklist.conf) [Mirror](lnkgl_u/native.tiktok.blacklist.conf) [jsDelivr](lnkjd_u/native.tiktok.blacklist.conf) | [Link](lnkgh_m/native.tiktok.txt) [Mirror](lnkgl_m/native.tiktok.txt) [jsDelivr](lnkjd_m/native.tiktok.txt) | [Link](lnkgh_m/native.tiktok-old.txt) [Mirror](lnkgl_m/native.tiktok-old.txt) [jsDelivr](lnkjd_m/native.tiktok-old.txt) | [Link](lnkgh_w/native.tiktok.txt) [Mirror](lnkgl_w/native.tiktok.txt) [jsDelivr](lnkjd_w/native.tiktok.txt) | [Link](lnkgh_w/native.tiktok-onlydomains.txt) [Mirror](lnkgl_w/native.tiktok-onlydomains.txt) [jsDelivr](lnkjd_w/native.tiktok-onlydomains.txt) | [Link](lnkgh_r/native.tiktok.txt) [Mirror](lnkgl_r/native.tiktok.txt) [jsDelivr](lnkjd_r/native.tiktok.txt) |
| TikTok (Fingerprinting) Aggressive | [Link](lnkgh_d/native.tiktok.extended.txt) [Mirror](lnkgl_d/native.tiktok.extended.txt) [jsDelivr](lnkjd_d/native.tiktok.extended.txt) | [Link](lnkgh_h/native.tiktok.extended.txt) [Mirror](lnkgl_h/native.tiktok.extended.txt) [jsDelivr](lnkjd_h/native.tiktok.extended.txt) | [Link](lnkgh_a/native.tiktok.extended.txt) [Mirror](lnkgl_a/native.tiktok.extended.txt) [jsDelivr](lnkjd_a/native.tiktok.extended.txt) | [Link](lnkgh_u/native.tiktok.extended.blacklist.conf) [Mirror](lnkgl_u/native.tiktok.extended.blacklist.conf) [jsDelivr](lnkjd_u/native.tiktok.extended.blacklist.conf) | [Link](lnkgh_m/native.tiktok.extended.txt) [Mirror](lnkgl_m/native.tiktok.extended.txt) [jsDelivr](lnkjd_m/native.tiktok.extended.txt) | [Link](lnkgh_m/native.tiktok.extended-old.txt) [Mirror](lnkgl_m/native.tiktok.extended-old.txt) [jsDelivr](lnkjd_m/native.tiktok.extended-old.txt) | [Link](lnkgh_w/native.tiktok.extended.txt) [Mirror](lnkgl_w/native.tiktok.extended.txt) [jsDelivr](lnkjd_w/native.tiktok.extended.txt) | [Link](lnkgh_w/native.tiktok.extended-onlydomains.txt) [Mirror](lnkgl_w/native.tiktok.extended-onlydomains.txt) [jsDelivr](lnkjd_w/native.tiktok.extended-onlydomains.txt) | [Link](lnkgh_r/native.tiktok.extended.txt) [Mirror](lnkgl_r/native.tiktok.extended.txt) [jsDelivr](lnkjd_r/native.tiktok.extended.txt) |
| LG webOS | [Link](lnkgh_d/native.lgwebos.txt) [Mirror](lnkgl_d/native.lgwebos.txt) [jsDelivr](lnkjd_d/native.lgwebos.txt) | [Link](lnkgh_h/native.lgwebos.txt) [Mirror](lnkgl_h/native.lgwebos.txt) [jsDelivr](lnkjd_h/native.lgwebos.txt) | [Link](lnkgh_a/native.lgwebos.txt) [Mirror](lnkgl_a/native.lgwebos.txt) [jsDelivr](lnkjd_a/native.lgwebos.txt) | [Link](lnkgh_u/native.lgwebos.blacklist.conf) [Mirror](lnkgl_u/native.lgwebos.blacklist.conf) [jsDelivr](lnkjd_u/native.lgwebos.blacklist.conf) | [Link](lnkgh_m/native.lgwebos.txt) [Mirror](lnkgl_m/native.lgwebos.txt) [jsDelivr](lnkjd_m/native.lgwebos.txt) | [Link](lnkgh_m/native.lgwebos-old.txt) [Mirror](lnkgl_m/native.lgwebos-old.txt) [jsDelivr](lnkjd_m/native.lgwebos-old.txt) | [Link](lnkgh_w/native.lgwebos.txt) [Mirror](lnkgl_w/native.lgwebos.txt) [jsDelivr](lnkjd_w/native.lgwebos.txt) | [Link](lnkgh_w/native.lgwebos-onlydomains.txt) [Mirror](lnkgl_w/native.lgwebos-onlydomains.txt) [jsDelivr](lnkjd_w/native.lgwebos-onlydomains.txt) | [Link](lnkgh_r/native.lgwebos.txt) [Mirror](lnkgl_r/native.lgwebos.txt) [jsDelivr](lnkjd_r/native.lgwebos.txt) |
| Vivo (BETA) | [Link](lnkgh_d/native.vivo.txt) [Mirror](lnkgl_d/native.vivo.txt) [jsDelivr](lnkjd_d/native.vivo.txt) | [Link](lnkgh_h/native.vivo.txt) [Mirror](lnkgl_h/native.vivo.txt) [jsDelivr](lnkjd_h/native.vivo.txt) | [Link](lnkgh_a/native.vivo.txt) [Mirror](lnkgl_a/native.vivo.txt) [jsDelivr](lnkjd_a/native.vivo.txt) | [Link](lnkgh_u/native.vivo.blacklist.conf) [Mirror](lnkgl_u/native.vivo.blacklist.conf) [jsDelivr](lnkjd_u/native.vivo.blacklist.conf) | [Link](lnkgh_m/native.vivo.txt) [Mirror](lnkgl_m/native.vivo.txt) [jsDelivr](lnkjd_m/native.vivo.txt) | [Link](lnkgh_m/native.vivo-old.txt) [Mirror](lnkgl_m/native.vivo-old.txt) [jsDelivr](lnkjd_m/native.vivo-old.txt) | [Link](lnkgh_w/native.vivo.txt) [Mirror](lnkgl_w/native.vivo.txt) [jsDelivr](lnkjd_w/native.vivo.txt) | [Link](lnkgh_w/native.vivo-onlydomains.txt) [Mirror](lnkgl_w/native.vivo-onlydomains.txt) [jsDelivr](lnkjd_w/native.vivo-onlydomains.txt) | [Link](lnkgh_r/native.vivo.txt) [Mirror](lnkgl_r/native.vivo.txt) [jsDelivr](lnkjd_r/native.vivo.txt) |
| OPPO/Realme (BETA) | [Link](lnkgh_d/native.oppo-realme.txt) [Mirror](lnkgl_d/native.oppo-realme.txt) [jsDelivr](lnkjd_d/native.oppo-realme.txt) | [Link](lnkgh_h/native.oppo-realme.txt) [Mirror](lnkgl_h/native.oppo-realme.txt) [jsDelivr](lnkjd_h/native.oppo-realme.txt) | [Link](lnkgh_a/native.oppo-realme.txt) [Mirror](lnkgl_a/native.oppo-realme.txt) [jsDelivr](lnkjd_a/native.oppo-realme.txt) | [Link](lnkgh_u/native.oppo-realme.blacklist.conf) [Mirror](lnkgl_u/native.oppo-realme.blacklist.conf) [jsDelivr](lnkjd_u/native.oppo-realme.blacklist.conf) | [Link](lnkgh_m/native.oppo-realme.txt) [Mirror](lnkgl_m/native.oppo-realme.txt) [jsDelivr](lnkjd_m/native.oppo-realme.txt) | [Link](lnkgh_m/native.oppo-realme-old.txt) [Mirror](lnkgl_m/native.oppo-realme-old.txt) [jsDelivr](lnkjd_m/native.oppo-realme-old.txt) | [Link](lnkgh_w/native.oppo-realme.txt) [Mirror](lnkgl_w/native.oppo-realme.txt) [jsDelivr](lnkjd_w/native.oppo-realme.txt) | [Link](lnkgh_w/native.oppo-realme-onlydomains.txt) [Mirror](lnkgl_w/native.oppo-realme-onlydomains.txt) [jsDelivr](lnkjd_w/native.oppo-realme-onlydomains.txt) | [Link](lnkgh_r/native.oppo-realme.txt) [Mirror](lnkgl_r/native.oppo-realme.txt) [jsDelivr](lnkjd_r/native.oppo-realme.txt) |

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

*:bulb: Another recommendation is to combine the main lists with the [Threat Intelligence Feeds](#tif) list if possible. For Adblockers that have problems with the size of the full TIF list there is a smaller [medium](#tifmedium) version. There is also an [IPv4 list](#tifips) that can be used additionally to the TIF or TIF medium list.*

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