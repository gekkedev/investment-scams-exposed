# (Investment) Scam Websites Exposed

Investment scam websites are increasingly common, often promising impossibly high returns and involving cryptocurrency transfers to obscure their traces. Many of these sites are created by individuals or groups based in China. This document aims to expose these websites, analyze their key details, and present the necessary information to take them down.

## Key Data on Scam Websites

| Website URL          | Hoster         | DNS middleman | Domain Registrar | Invitation Code | Alleged Violations | Impersonations / brand infringements |
|----------------------|----------------|--------------------|------------------|-----------------|--------------------------------------|-------------------------------------------|
| [tunework.world](https://tunework.world) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [Alibaba](https://www.alibabacloud.com/domain) |  `HK3YNF` | redirects to tunework.live | - |
| [tunework.live](https://tunework.live) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [Alibaba](https://www.alibabacloud.com/domain) | `HK3YNF` | cryptocurrency investment scam advertised as a work opportunity | alleges to be partners with Google, Apple, Microsoft, Meta, TikTok, and |
| [ilpudse.pics](https://ilpudse.pics) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [Public Domain Registry](https://publicdomainregistry.com) | - | investment scam | pretends to be [Spiegel](https://www.spiegel.de) |
| [www.adjust6.com](www.adjust6.com) | N/A | [Gname](https://www.gname.com) | [Gname](https://www.gname.com) | - | forwards to [a WhatsApp number](https://api.whatsapp.com/send/?phone=447562167485&text&type=phone_number&app_absent=0) which tells you to visit [adjust-work.net](https://www.adjust-work.net) | [adjust.com](https://www.adjust.com) |
| [adjust-work.net](https://www.adjust-work.net) | N/A | [Gname](https://www.gname.com) | [Gname](https://www.gname.com) | `bWejuP` | Cryptocurrency investment scam involving the Telegram number +33745348532 | using the name and logo of [adjust.com](https://www.adjust.com) |
| [m.aocfx.com](https://m.aocfx.com) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [Gname](https://www.gname.com) | `BUOYGV` | cryptocurrency investment scam involving the Telegram username `BainCapitalDelia` | impersonates [BainCapital](https://www.baincapital.com) in WhatsApp & uses their logo |
| [inwinoo.com](https://inwinoo.com) | N/A | [Namecheap](http://www.namecheap.com) | [Namecheap](http://www.namecheap.com) | - | collecting contact data for an investment scam | [Tagesschau](https://www.tagesschau.de) |
| [sportsmentorshipprogram.org](http://sportsmentorshipprogram.org) | [Sav.com, LLC](http://sav.com) (suspected) | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [Sav.com, LLC](http://sav.com) | - | collecting contact data for an investment scam | [Tagesschau](https://www.tagesschau.de) |
| [app-sparkasse.info](https://app-sparkasse.info) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) | - | redirects to [reaktivierungs-sprks.xyz](https://reaktivierungs-sprks.xyz) for phishing | [Sparkasse](https://www.sparkasse.de) |
| [reaktivierungs-sprks.xyz](https://reaktivierungs-sprks.xyz) | N/A | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) | - | phishing | [Sparkasse](https://www.sparkasse.de) |
| [sid-check.com](https://sid-check.com) | N/A | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) | - | phishing | [Sparkasse](https://www.sparkasse.de) |
| [dacmcrypto.com](https://www.dacmcrypto.com/h5/#/pages/mine/register?invite_code=HFBHXR.) | N/A | [NameSilo, LLC](https://www.namesilo.com/report_abuse.php) | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | `HFBHXR` | cryptocurrency investment scam (presented as mining) | - |
| [msssetd.com](https://msssetd.com/#/login?type=register&yCode=88jo9762308) | N/A | [Cloudflare](https://www.cloudflare.com/trust-hub/reporting-abuse) | [CNO Bin / Ordertld](http://www.ordertld.com/support.html) | `88jo9762308` | cryptocurrency investment scam | - |
| https://wealthjourney.world | - | [GoDaddy.com, LLC](https://supportcenter.godaddy.com/AbuseReport) | [Wild West Domains, LLC](https://www.wildwestdomains.com) | - | gateway for a Whatsapp-based investment scam | impersonates [Martin Currie Limited](https://www.martincurrie.com) in Whatsapp |

## TODO domains
The following domains are shielded by [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) but their names give away that they're most likely phishing:
- bundesfinanz-ministerium.info
- finanzamt2024.online
- finanzamt2024.info
- bawag-autorisieren.com
- activer-bnpparibas.com
- connexion-bnpparibas.com
- etape-bnpparibas.com
- 20-bnpparibas.com
- 21-bnpparibas.com
- 29-bnpparibas.com
- mabanque-bnpparibas.com
- aktivierung-o2de.online
- derspk-aktualisierung369.xyz
- kvk2024.info

## Explanation

## Nameservers
DNS middleman services hide the IP addresses of servers. Whilst originally designed as a cybersecurity measure, those providers see no problem with being an enabler of crime and refuse to take action even when the scam report is very easy to validate. The nameservers indirectly reveal who the DNS middleman is, as their DNS servers listed in the whois query can be mapped to the middleman:
| DNS server              | Real middleman                                    |
|-------------------------|---------------------------------------------------|
| *.registrar-servers.com | [Namecheap](http://www.namecheap.com)             |
| *.ns.cloudflare.com     | [Cloudflare](https://www.cloudflare.com)          |
| *.managedns.org         | [OwnRegistrar, Inc.](https://ownregistrar.com/abuse) |

## Contributing
If you find any new domains, just open an issue with the domain or create a pull request with the amendments.

## Conclusion

These websites represent a significant threat to unsuspecting investors, primarily through the promise of high returns and the use of cryptocurrency to obscure their operations. By exposing these websites and detailing their operations, we aim to help authorities and internet service providers take action to shut them down and protect potential victims.

