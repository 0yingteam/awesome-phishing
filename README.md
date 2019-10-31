# awesome-phishing

Collection of useful resources for red teamers, pentesters, security reseachers and anyone interested in technical and non-technical aspects of phishing and related topics.

Idea, concept and some resources from [Awesome Red Teaming](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming/).

Feel free to contribute any resources that might help to improve this list.


## Table of contents

* [Email security](#-email-security)

* [OSINT for phishers](#-osint-for-phishers)

* [Phishing infrastructure](#-phishing-infrastructure)

* [Payloads and filter evasion](#-payloads-and-filter-evasion)

* [Tools and frameworks](#-tools-and-frameworks)

* [Books and ebooks](#-books-and-ebooks)

* [Campaign write-ups](#-campaign-write-ups)

* [Phishing prevention and detection](#-phishing-prevention-and-detection)

* [Phishing-related scientific research](#-phishing-related-scientific-research)

* [Miscellaneous](#-miscellaneous)

## [↑](#table-of-contents) Email security
### Encryption standards
* [SSL vs TLS vs STARTTLS](https://www.limilabs.com/blog/ssl-vs-tls-vs-starttls-stls)
* [Two-Factor Authentication for Beginners](https://medium.com/@mshelton/two-factor-authentication-for-beginners-b29b0eec07d7)
* [How to encrypt email (Gmail, Outlook iOS, OSX, Android, Webmail)](https://www.comparitech.com/blog/vpn-privacy/how-to-encrypt-email)

### Email authentication
* [Part 3: How to Set up SPF and DKIM with Postfix on Ubuntu Server](https://www.linuxbabe.com/mail-server/setting-up-dkim-and-spf)
* [How to Set Up DKIM in 3 Simple Steps](https://www.mailjet.com/blog/news/setting-up-dkim-step-by-step-a7d0a0ec-c4aa-4b5b-aeb5-a06361aa2e51/)
* [What is SPF & DKIM? 
And Why You Want to Have It Set Up (Updated)](https://blog.woodpecker.co/cold-email/spf-dkim/)
* [Authenticated Received Chain Overview](https://dmarc.org/presentations/ARC-Overview-2016Q3-v01.pdf)
* [The "iprev" Authentication Method](https://tools.ietf.org/html/rfc5451#section-3)
* [How To Set Up Your Author Domain Signing Practices (HISTORIC)](https://www.unlocktheinbox.com/resources/adsp/)

### Filtering techniques

* [Spamtrap 101: What they Are, Why You Hit Them, & What to Do About It](https://www.freshaddress.com/blog/spamtrap-101/)
* [Classify emails into ham and spam using Naive Bayes Classifier](https://medium.com/swlh/classify-emails-into-ham-and-spam-using-naive-bayes-classifier-ffddd7faa1ef)
* [Filtering Spam Using Naive Bayes](https://towardsdatascience.com/spam-filtering-using-naive-bayes-98a341224038)
* [Using SpamAssassin](https://sourcedaddy.com/networking/using-spamassassin.html)
* [Sieve Tutorial](https://p5r.uk/blog/2011/sieve-tutorial.html)
* [The CRM114 & Mailfilter HOWTO](http://crm114.sourceforge.net/docs/CRM114_Mailfilter_HOWTO.txt)
* [fdm/MANUAL](https://github.com/nicm/fdm/blob/master/MANUAL)
* [Nolisting: Poor Man's Greylisting](http://nolisting.org/)
* [Setting up an email honeypot spamtrap, malware, malspam trap.](https://myonlinesecurity.co.uk/setting-up-an-email-honeypot-spamtrap-malware-malspam-trap/)
* [How to Add Antivirus and Spam Protection to Postfix Mail Server with ClamAV and SpamAssassin – Part 3](https://www.tecmint.com/integrate-clamav-and-spamassassin-to-protect-postfix-mails-from-viruses/)
* [Email Greylisting. How does greylisting work?](https://www.interserver.net/tips/kb/email-greylisting-greylisting-work/)
* [DNSBL (DNS Black List)](http://www.zytrax.com/books/dns/ch9/dnsbl.html)

## [↑](#table-of-contents) OSINT for phishers
* [OSINT: How to find information on anyone](https://medium.com/@Peter_UXer/osint-how-to-find-information-on-anyone-5029a3c7fd56)
* [Use buscador osint vm for conducting online investigations](https://null-byte.wonderhowto.com/how-to/use-buscador-osint-vm-for-conducting-online-investigations-0186611/)
* [Open-Source Intelligence (OSINT) Reconnaissance](https://medium.com/@z3roTrust/open-source-intelligence-osint-reconnaissance-75edd7f7dada)
* [A Guide to Open Source Intelligence Gathering (OSINT)](https://medium.com/bugbountywriteup/a-guide-to-open-source-intelligence-gathering-osint-ca831e13f29c)
* [OSINT Resources for 2019](https://medium.com/@micallst/osint-resources-for-2019-b15d55187c3f)


## [↑](#table-of-contents) Phishing infrastructure
* [Going phishing with terraform](https://bestestredteam.com/2019/03/22/going-phishing-with-terraform/)
* [Building resilient phishing campaign infrastructure](https://godlikesecurity.com/index.php/2017/12/14/building-resilient-phishing-campaigns/)
* [Red Team Infrastructure Wiki](https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki)
* [Complete guide creating and hosting phishing page for beginners](https://null-byte.wonderhowto.com/forum/complete-guide-creating-and-hosting-phishing-page-for-beginners-0187744/)
* [Automating gophish releases](https://jordan-wright.com/blog/post/2018-02-04-automating-gophish-releases/)
* [Mail Server Setup](https://blog.inspired-sec.com/archive/2017/02/14/Mail-Server-Setup.html)
* [Safe red team infrastructure](https://medium.com/@malcomvetter/safe-red-team-infrastructure-c5d6a0f13fac)
* [Automated red team infrastructure deployment with terraform - part 1](https://rastamouse.me/2017/08/automated-red-team-infrastructure-deployment-with-terraform---part-1/)
* [Automated red team infrastructure deployment with terraform - part 2](https://rastamouse.me/2017/09/automated-red-team-infrastructure-deployment-with-terraform---part-2/)
* [Infrastructure for ongoing red team operations](https://blog.cobaltstrike.com/2014/09/09/infrastructure-for-ongoing-red-team-operations/)

## [↑](#table-of-contents) Payloads and filter evasion
* [Evilginx - Advanced Phishing with Two-factor Authentication Bypass](https://breakdev.org/evilginx-advanced-phishing-with-two-factor-authentication-bypass/)
* [Evilginx 2 - Next Generation of Phishing 2FA Tokens](https://breakdev.org/evilginx-2-next-generation-of-phishing-2fa-tokens/)
* [Luckystrike a database backed evil macro generator](https://www.shellntel.com/blog/2016/9/13/luckystrike-a-database-backed-evil-macro-generator)
* [Powershell empire stagers 1 phishing with an office macro and evading avs](https://fzuckerman.wordpress.com/2016/10/06/powershell-empire-stagers-1-phishing-with-an-office-macro-and-evading-avs)
* [Executing metasploit empire payloads from ms office documemt properties part 1 of 2](https://stealingthe.network/executing-metasploit-empire-payloads-from-ms-office-document-properties-part-1-of-2)
* [Executing metasploit empire payloads from ms office documemt properties part 2 of 2](https://stealingthe.network/executing-metasploit-empire-payloads-from-ms-office-document-properties-part-2-of-2)
* [Phishing against protected view]( https://enigma0x3.net/2017/07/13/phishing-against-protected-view/)
* [Phishing with powerpoint](https://www.blackhillsinfosec.com/phishing-with-powerpoint/)
* [Phishing with empire](https://enigma0x3.net/2016/03/15/phishing-with-empire/)
* [Abusing microsoft word features phishing subdoc](https://rhinosecuritylabs.com/research/abusing-microsoft-word-features-phishing-subdoc/)
* [Phishing against protected view](https://enigma0x3.net/2017/07/13/phishing-against-protected-view/)
* [csv injection](http://georgemauer.net/2017/10/07/csv-injection.html)
* [Excel macros with powershell](https://4sysops.com/archives/excel-macros-with-powershell/)
* [Powerpoint and custom actions](https://phishme.com/powerpoint-and-custom-actions/)
* [Macroless malware that avoids detection with yara rule)](https://furoner.wordpress.com/2017/10/17/macroless-malware-that-avoids-detection-with-yara-rule/amp/)
* [Hacking into whatsapp series part 2 phishing](https://null-byte.wonderhowto.com/forum/hacking-into-whatsapp-series-part-2-phishing-0179508/)
* [Macro-less code exec in msword](https://sensepost.com/blog/2017/macro-less-code-exec-in-msword/)
* [Multi-platform macro phishing payload](https://medium.com/@malcomvetter/multi-platform-macro-phishing-payloads-3b688e8eff68)

## [↑](#table-of-contents) Tools and frameworks
### OSINT tools
* [Kali tools list](https://tools.kali.org/tools-listing)
* [OSINT framework](https://osintframework.com/)
* [Whois](http://whois.domaintools.com/)
* [HaveIBeenPwnd](https://haveibeenpwned.com/)
* [Creepy](https://github.com/ilektrojohn/creepy)
* [Maltego](https://www.paterva.com/buy/maltego-clients/maltego-ce.php)
* [Shodan](https://www.shodan.io/)
* [Censys](https://censys.io/)
* [TheHarvester](https://github.com/laramies/theHarvester)
* [Recon-ng](https://github.com/lanmaster53/recon-ng)
* [TinEye](https://www.tineye.com/)
* [SearX](https://searx.me/)

### Phishing campaign tools
* [Evilginx2](https://github.com/kgretzky/evilginx2)
* [Social Engineering Toolkit](https://github.com/trustedsec/social-engineer-toolkit/)
* [King Phisher](https://github.com/securestate/king-phisher)
* [FiercePhish](https://github.com/Raikia/FiercePhish)
* [ReelPhish](https://github.com/fireeye/ReelPhish/)
* [Fishing Cat Server](https://github.com/fishing-cat/fishing-cat-server)
* [GoPhish](https://github.com/gophish/gophish)
* [LUCY](https://lucysecurity.com/)
* [CredSniper](https://github.com/ustayready/CredSniper)
* [PwnAuth](https://github.com/fireeye/PwnAuth)
* [sptoolkit](https://github.com/chris-short/sptoolkit)
* [SpearPhisher](https://github.com/kevthehermit/SpearPhisher)
* [Wifiphisher](https://wifiphisher.org/)
* [Ares](https://github.com/dutchcoders/ares)
* [Phishing-frenzy](https://github.com/pentestgeek/phishing-frenzy)
* [SPF](https://github.com/tatanus/SPF)
* [Phishing pretexts](https://github.com/L4bF0x/PhishingPretexts)
* [Mercure](https://github.com/atexio/mercure)
* [Metasploit](https://github.com/rapid7/metasploit-framework)
* [Cobalt strike](https://www.cobaltstrike.com/help-spear-phish)

### Payload tools
* [The Browser Exploitation Framework](https://github.com/beefproject/beef)
* [LuckyStrike](https://github.com/curi0usJack/luckystrike)
* [Shellter](https://www.shellterproject.com/)
* [msfvenom](https://www.offensive-security.com/metasploit-unleashed/msfvenom/)
* [The Backdoor Factory](https://github.com/secretsquirrel/the-backdoor-factory)
* [Veil framework](https://github.com/Veil-Framework/Veil)

## [↑](#table-of-contents) Books and ebooks
* [Phishing Dark Waters: The Offensive and Defensive Sides of Malicious Emails](https://www.amazon.com/Phishing-Dark-Waters-Offensive-Defensive/dp/1118958470)
* [Phishing for Phools: The Economics of Manipulation and Deception](https://press.princeton.edu/books/hardcover/9780691168319/phishing-for-phools)
* [Scam Me If You Can: Simple Strategies to Outsmart Today's Rip-off Artists](https://www.amazon.com/Scam-Me-You-Can-Strategies/dp/0525538968)
* [Phishing: Detection, Analysis And Prevention](https://www.amazon.com/dp/1090376928/)
* [Social Engineering: The Science of Human Hacking](https://www.amazon.com/Social-Engineering-Science-Human-Hacking/dp/111943338X)
* [Don't Step in the Trap: How to Recognize and Avoid Email Phishing Scams](https://www.amazon.com/Dont-Step-Trap-Recognize-Phishing-ebook/dp/B01DXI9X0I)
* [Asset Attack Vectors: Building Effective Vulnerability Management Strategies to Protect Organizations](https://www.amazon.com/Asset-Attack-Vectors-Vulnerability-Organizations/dp/1484236262)
* [Cyberpsychology: The Study of Individuals, Society and Digital Technologies](https://www.amazon.com/Cyberpsychology-Individuals-Technologies-Textbooks-Psychology/dp/0470975628)
* [Stealing Your Life: The Ultimate Identity Theft Prevention Plan](https://www.amazon.com/Stealing-Your-Life-Ultimate-Prevention/dp/0767925874)
* [Open Source Intelligence Techniques: Resources for Searching and Analyzing Online Information](https://www.amazon.com/Open-Source-Intelligence-Techniques-Information/dp/1530508908)
* [Swiped: How to Protect Yourself in a World Full of Scammers, Phishers, and Identity Thieves](https://www.amazon.com/Swiped-Yourself-Scammers-Phishers-Identity/dp/1610397207)
* [Spam Nation: The Inside Story of Organized Cybercrime - from Global Epidemic to Your Front Door](https://www.amazon.com/Spam-Nation-Organized-Cybercrime_from-Epidemic/dp/1501210424)

## [↑](#table-of-contents) Campaign write-ups
* [Darknet diaries: The hack](https://darknetdiaries.com/episode/19/)
* [YouTube Impersonation Scams Offering Fake Rewards are Running Wild](https://www.riskiq.com/blog/labs/youtube-impersonation-scams/)
* [Tainted Leaks: Disinformation and Phishing With a Russian Nexus](https://citizenlab.ca/2017/05/tainted-leaks-disinformation-phish/)
* [Nile Phish: Large-Scale Phishing Campaign Targeting Egyptian Civil Society](https://citizenlab.ca/2017/02/nilephish-report/)
* [Exposing One of China’s Cyber Espionage Units](https://www.fireeye.com/content/dam/fireeye-www/services/pdfs/mandiant-apt1-report.pdf)
* [Grizzly Steppe - Russian Malicious Cyber Activity](https://www.us-cert.gov/sites/default/files//JAR_16-20296A_GRIZZLY%20STEPPE-2016-1229.pdf)
* [Analysing a massive Office 365 phishing campaign](https://bartblaze.blogspot.com/2019/03/analysing-massive-office-365-phishing.html?m=1)
* [Gmail Phishing Campaign Racking Up Victims](https://www.pindrop.com/blog/gmail-phishing-campaign-racking-up-victims/)
* [Spying on a Budget: Inside a Phishing Operation with Targets in the Tibetan Community](https://citizenlab.ca/2018/01/spying-on-a-budget-inside-a-phishing-operation-with-targets-in-the-tibetan-community/)
* [Reckless Redux: Senior Mexican Legislators and Politicians Targeted with NSO Spyware](https://citizenlab.ca/2017/06/more-mexican-nso-targets/)
* [Reckless Exploit: Mexican Journalists, Lawyers, and a Child Targeted with NSO Spyware](https://citizenlab.ca/2017/06/reckless-exploit-mexico-nso/)
* [Shifting Tactics: Tracking changes in years-long espionage campaign against Tibetans](https://citizenlab.ca/2016/03/shifting-tactics/)
* [Packrat: Seven Years of a South American Threat Actor](https://citizenlab.ca/2015/12/packrat-report/)
* [How millions of DSL modems were hacked in Brazil, to pay for Rio prostitutes](https://citizenlab.ca/2012/10/how-millions-of-dsl-modems-were-hacked-in-brazil-to-pay-for-rio-prostitutes/)
* [Cloned RFE/RL phishing website in Uzbekistan](https://citizenlab.ca/2012/02/11988/)
* [Chinese hackers steal Gmail passwords: Google](http://m.digitaljournal.com/article/307490)
* [The RSA Hack: How They Did It](https://bits.blogs.nytimes.com/2011/04/02/the-rsa-hack-how-they-did-it/)

## [↑](#table-of-contents) Phishing prevention and detection
* [Email Phishing Protection Guide – Blog 19: Email Phishing Protection Security Checklist](https://blogs.technet.microsoft.com/cloudready/2018/11/21/blog-19-email-phishing-protection-security-checklist/)
* [Backtrack phishing email using Open-source intelligence gathering](https://www.peerlyst.com/posts/backtrack-phishing-email-using-open-source-intelligence-gathering-shaquib-izhar)
* [Phishing - Advanced URL Analysis - Obfuscation, Clickjacking and OSINT Gathering](https://mlhale.github.io/nebraska-gencyber-modules/phishing/url-analysis-advanced/)
* [Blunting the phishers spear: A risk-based approach](https://m.youtube.com/watch?v=5j6iSDBmCP4)
* [Deconstructing the Phishing Campaigns that Target Gmail Users](https://docs.google.com/presentation/d/1RlpF-uVEEe9SMM9g0o0MudcBD2r6nqyCB0iUHv3rwEg/embed)
* [How to Recognize Phishing Emails](https://resources.infosecinstitute.com/recognize-phishing-emails/#gref)


## [↑](#table-of-contents) Phishing-related scientific research
* [Every ROSE has its thorn 
The dark art of Remote Online Social Engineering](http://i.blackhat.com/us-18/Wed-August-8/us-18-Wixey-Every-ROSE-Has-Its-Thorn-The-Dark-Art-Of-Remote-Online-Social-Engineering.pdf)
* [Ichthyology-phishing-as-a-science](https://www.blackhat.com/us-17/briefings.html#ichthyology-phishing-as-a-science)
* [DeepPhish: Simulating Malicious AI](https://m.youtube.com/watch?v=fGtPmiNebDE)
* [Why Phishing Works](https://cloudfront.escholarship.org/dist/prd/content/qt9dd9v9vd/qt9dd9v9vd.pdf)
* [PhishEye: Live monitoring of sandboxed phishing kits](http://193.55.114.4/docs/ccs16_phisheye.pdf)
* [Phishnet: predictive blacklisting to detect phishing attacks](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.168.4540&rep=rep1&type=pdf)
* [The current state of phishing attacks](https://kilthub.cmu.edu/articles/The_Current_State_of_Phishing_Attacks/6470498/files/11899055.pdf)
* [Resurgence of Phishing-as-a-Service (PhaaS) platforms]( https://www.netskope.com/blog/resurgence-of-phishing-as-a-service-phaas-platforms)
* [Phishing in the public cloud: You’ve been served](https://www.netskope.com/blog/phishing-in-the-public-cloud)
* [Decoys, Phishing, and the Cloud: The Latest Fan-out Effect](https://www.netskope.com/blog/decoys-phishing-cloud-latest-fan-effect)
* [Targeted Attacks Abusing Google Cloud Platform Open Redirection](https://www.netskope.com/blog/targeted-attacks-abusing-google-cloud-platform-open-redirection)
* [Understanding User Behaviors When Phishing Attacks Occur](https://ieeexplore.ieee.org/abstract/document/8823468)
* [Weaponizing data science for social engineering: Automated E2E spear phishing on Twitter](https://www.co.tt/files/defcon24/Speaker%20Materials/DEFCON-24-Seymour-Tully-Weaponizing-Data-Science-For-Social-Engineering-WP.pdf)
* [Do security toolbars actually prevent phishing attacks?](http://cs.union.edu/~fernandc/srs200/readings/SecurityToolbars.pdf)
* [Large-scale automatic classification of phishing pages](https://ai.google/research/pubs/pub35580.pdf)
* [Social phishing](http://www.markus-jakobsson.com/papers/jakobsson-commacm07.pdf)
* [Phishing for phishing awareness](https://www.tandfonline.com/doi/abs/10.1080/0144929X.2011.632650)

## [↑](#table-of-contents) Miscellaneous
* [Defcon 24: Phishing without failure and frustation](https://m.youtube.com/watch?v=jXQSpDDyOYE)
* [Mitre ATT&CK: Spearphishing link]( https://attack.mitre.org/techniques/T1192/)
* [Mitre ATT&CK: Spearphishing attachment](https://attack.mitre.org/techniques/T1193/)
* [Mitre ATT&CK: Spearphishing via service](https://attack.mitre.org/techniques/T1194/)
* [Amazing mind reader reveals his gift](https://www.youtube.com/watch?v=F7pYHN9iC9I)
* [HackBack: A DIY Guide](http://pastebin.com/raw/0SNSvyjJ)
* [A DIY Guide for those without the patience to wait for whistleblowers](https://pastebin.com/BMb543G9)
* [This is what happens when you reply to spam email](https://m.youtube.com/watch?v=_QdPW8JrYzQ)
* [Google Phishing Quiz](https://phishingquiz.withgoogle.com/)
* [OpenDNS Phishing Quiz](https://www.opendns.com/phishing-quiz/)
* [PhishTank](https://PhishTank.com)
* [PhishBank](https://phishbank.org/)
* [KnowBe4 info site](https://www.knowbe4.com/phishing)
* [VirusTotal](https://www.virustotal.com/gui/)
* [mx toolbox](https://mxtoolbox.com/diagnostic.aspx)
* [TedX: Phishing for phools](https://m.youtube.com/watch?v=0Ax1wrJD2LU)
