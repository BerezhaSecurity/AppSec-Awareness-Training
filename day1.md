# Day 1 Notes

## Establish context: demonstrate current state of applicaiton security and its effect on technology and economy

# DAST Day 1. Introduction to Cybersecurity

* Have you ever been hacked?
    * Poll: Have you ever been hacked?
        * Definitely yes
        * Definitely no
        * No idea
    * Poll: Did you ever have a "virus" on your device?
        * Yes
        * No
    * Have you really been hacked?
        * Did you ever have a “virus” on your device?
        * Have I been pwned https://haveibeenpwned.com  
    * Redo Poll: Have you ever been hacked? Compare results.
* Cybersecurity threats, threat actors, cyberattacks, and data breaches.
    * Data Breaches over time https://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/ 
    * New: Ransomware attacks https://informationisbeautiful.net/visualizations/ransomware-attacks/ 
    * Threat actors
        * Script kiddies
        * Cybercriminals
        * Nation-states
    * Targeting
        * OPM + Equifax + Anthem + Marriott https://www.wired.com/story/china-equifax-anthem-marriott-opm-hacks-data/ 
    * Poll: Who causes most security incidents?
        * Skiddies
        * Cybercriminals
        * Cyber spies
        * Malicious insiders
    * Data Breach Investigation Report 
        * 2020 https://enterprise.verizon.com/resources/reports/dbir/2020/summary-of-findings/ 
        * 2021 https://www.verizon.com/business/resources/reports/dbir/2021/ 
* Attack vectors and security vulnerability classes.
    * Poll: Do you know what is OWASP?
        * Yes 
        * No
    * Intro video: https://www.youtube.com/watch?v=T2tlcZsYtko 
    * Attack vectors
        * Understanding the cyberattack kill chain
            * OWASP Top 10 2017 https://owasp.org/www-project-top-ten/2017/Application_Security_Risks.html 
            * Mitre ATT&CK matrix https://mitre-attack.github.io/attack-navigator/ 
    * Security vulnerabilities
        * OWASP Top 10 2021 https://owasp.org/Top10/ 
* Security design and secure protocol demo based on the Have I Been Pwned website.
    * This is what this course is about https://haveibeenpwned.com/Passwords 
    * Stop-by-step design of a secure protocol fo password verification
        * Hashes
        * K-anonymity
            * Send 5 chars prefix
            * Receive hash_prefix(2)+rest_of_hash:pwdcount
    * Principles
        * Privacy: client-side decision
        * Anonymity: no one, including the server and a capable passive observer, can make any sense
* Cybersecurity online resources and communities.
    * r/netsec 
    * Conferences and meetups
        * OWASP chapters (Kyiv, Lviv, Zhytomyr)
    * Awesome AppSec Resources https://github.com/paragonie/awesome-appsec
    * Twitter
