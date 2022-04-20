# Day 5 Secure Development

### Guides:

- [Code Review Guide](https://owasp.org/www-pdf-archive/OWASP_Code_Review_Guide_v2.pdf)
- CODE REVIEW GUIDE - CODE CRAWLING for Grep
- [Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/)
- [OWASP .NET Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/DotNet_Security_Cheat_Sheet.html)

### [Insecure source code management](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Source%20Code%20Management)

### Vulnerabilities and Security Advisories
- [Snyk](https://security.snyk.io)
- [.NET announcments](https://github.com/dotnet/announcements/issues?q=is%3Aopen+is%3Aissue+label%3ASecurity)
- [ASP.NET announcments](https://github.com/aspnet/Announcements/issues?q=is%3Aopen+is%3Aissue+label%3ASecurity) 
- 

### Some XSS examples
- NodeJS XSS (xss1,xss2,xss3) simple examples
#### XSS in frameworks
- React uses `dangerouslySetInnerHTML`
- Angular uses `[innerHtml]` [Juice Shop](https://github.com/juice-shop/juice-shop/blob/427ba939a05ea667d5b66370448946cb824287bb/frontend/src/app/search-result/search-result.component.html)
- Vue uses : `v-html`
- XSS in hr-yo.ga portal
- [XSS Hunter](https://xsshunter.com/app)
- [BeEF](https://beefproject.com)
- [XSS Polyglots](https://gist.github.com/michenriksen/d729cd67736d750b3551876bbedbe626)
### More Practice 
- [SecureFlag](https://secureflag.owasp.org/)
- [Lab Mass Assignment in User Sign-up](https://secureflag.owasp.org/user/index.html#/exercises/details/f1fb9cb4-559f-460e-af9b-7bfbcd092dd8)
- Prototype Pollution Explanation with `prototype-pollution-explained` app
- [Lab NodeJS OS Command Injection](https://secureflag.owasp.org/user/index.html#/exercises/details/f4a98af5-6392-4ea5-a86d-0bbce98958fe)[Describtion](https://knowledge-base.secureflag.com/vulnerabilities/code_injection/os_command_injection_nodejs.html)
- [Lab SQL Injection in NodeJS](https://secureflag.owasp.org/user/index.html#/exercises/details/8e1f3056-32a3-4382-943a-6956ff93f4dc)
- [hr-yo.ga](https://appsec.hr-yo.ga) business logic on password recovery
- [hr-yo.ga](https://appsec.hr-yo.ga) NoSQLi vulnerability

## ASP.NET labs
- [Arbitrary File Download in Catalogs](https://secureflag.owasp.org/user/index.html#/exercises/details/fc5671b8-f258-4356-b0cc-4e709100d021) E-commerce application allows visitors to download the product catalog `src/Web/Controllers/PublicController.cs`
- [Open Redirect](https://secureflag.owasp.org/user/index.html#/exercises/paths/details/84bc7af1-af23-4eaf-8fad-474e52a0531e) VulnShop application accepts untrusted input that could redirect the request to an attacker-controlled URL `src/Web/Areas/Identity/Pages/Account/Login.cshtml.cs`
- [OAuth Cookie Stealing via unchecked Redirect URI](https://secureflag.owasp.org/user/index.html#/exercises/details/df798d83-fcc4-49c1-a742-a3ba59ffdbee)
- [Unsafe Deserialization in Geo update](https://secureflag.owasp.org/user/index.html#/exercises/details/2e25648b-b319-43d5-af44-8486923e5b72)

## PHP labs
- [PHP sandbox](https://sandbox.onlinephpfunctions.com)
```<?php
var_dump(md5('240610708'),md5('QNKCDZO'));
```
- [DVWA](https://hub.docker.com/r/vulnerables/web-dvwa)
` docker run --rm -it -p 80:80 vulnerables/web-dvwa `
- [File Upload](https://gist.github.com/joswr1ght/22f40787de19d80d110b37fb79ac3985) easy-simple-php-webshell.php
- [SQLi explanation](https://secureflag.owasp.org/user/index.html#/exercises/details/e89a6528-693e-49db-b6d1-5815404f0bd8)
- [SQLi blind on DVWA](http://127.0.0.1/vulnerabilities/sqli_blind/)

### Homework
- [Web Security Academy](https://portswigger.net/web-security)
- [Juice Shop](https://github.com/juice-shop/juice-shop)
