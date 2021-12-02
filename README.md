# Note-Book

## Google Dorking

What are Crawlers?
```
Q.1: Name the key term of what a "Crawler" is used to do
A: index
Q.2: What is the name of the technique that "Search Engines" use to retrieve this information about websites? 
A: crawling
Q.2: What is an example of the type of contents that could be gathered from a website?
A: keywords
```
Search Engine Optimisation (SEO)
```
https://web.dev/measure/
https://pagespeed.web.dev/
https://seositecheckup.com/
https://neilpatel.com/seo-analyzer/
```
Robots.txt
```
Q.1: Where would "robots.txt" be located on the domain "ablog.com"
A: ablog.com/robots.txt
Q.2: If a website was to have a sitemap, where would that be located?
A: /sitemap.xml
Q.3: How would we only allow "Bingbot" to index the website?
A: User-agent:Bingbot
Q.4: How would we prevent a "Crawler" from indexing the directory "/dont-index-me/"?
A: Disallow:/dont-index-me/
Q.5: What is the extension of a Unix/Linux system configuration file that we might want to hide from "Crawlers"?
A: .conf
```
Sitemaps
```
Q.1: What is the typical file structure of a "Sitemap"?
A: xml
Q.2: What real life example can "Sitemaps" be compared to?
A: map
Q.3: Name the keyword for the path taken for content on a website
A: route
```
Using Google for Advanced Searching
```
Q.1: What would be the format used to query the site bbc.co.uk about flood defences
A: site:bbc.co.uk flood defences
Q.2: What term would you use to search by file type?
A: filetype:
Q.3: What term can we use to look for login pages?
A: intitle:login
```
## Web Fundamentals

```
Q.1: What request verb is used to retrieve page content?
A: GET
Q.2: What port do web servers normally listen on?
A: 80
Q.3: What's responsible for making websites look fancy?
A: CSS
```
```
Q.1: What verb would be used for a login?
A: POST
Q.2: What verb would be used to see your bank balance once you're logged in?
A: GET
Q.3: Does the body of a GET request matter? Yea/Nay
A: Nay
Q.4: What's the status code for "I'm a teapot"?
A: 418
Q.5: What status code will you get if you need to authenticate to access some content, and you're unauthenticated?
A: 401
```
Mini CTF
```
Q.1: What's the GET flag?
A: thm{162520bec925bd7979e9ae65a725f99f}
Q.2: What's the POST flag?
A: thm{3517c902e22def9c6e09b99a9040ba09}
Q.3: What's the "Get a cookie" flag?
A: thm{91b1ac2606f36b935f465558213d7ebd}
Q.4: What's the "Set a cookie" flag?
A: thm{c10b5cb7546f359d19c747db2d0f47b3}
```
## OWASP Juice Shop

```
Q.1: What's the Administrator's email address?
A: admin@juice-sh.op
Q.2: What parameter is used for searching?
A: q (search?q=a)
Q.3: What show does Jim reference in his review? 
A: Star Trek
```
Injection

SQL Injection is when an attacker enters a malicious or malformed query to either retrieve or tamper data from a database. And in some cases, log into accounts.

Command Injection is when web applications take input or user-controlled data and run them as system commands. An attacker may tamper with this data to execute their own system commands. This can be seen in applications that perform misconfigured ping tests. 

Email injection is a security vulnerability that allows malicious users to send email messages without prior authorization by the email server. These occur when the attacker adds extra data to fields, which are not interpreted by the server correctly. 

```
Q.1: Log into the administrator account!
A: 32a5e0f21372bcc1000a6088b93b458e41f0e02a
Q.2: Log into the Bender account!
A: fb364762a3c102b2db932069c0e6b78e738d4066
```
Broken Authentication
```
Q.1: Bruteforce the Administrator account's password!
A: c2110d06dc6f81c67cd8099ff0ba601241f1ac0e
Q.2: Reset Jim's password!
A: 094fbc9b48e525150ba97d05b942bbf114987257 
```
Sensitive Data Exposure
```
Q.1: Access the Confidential Document!
A: 
