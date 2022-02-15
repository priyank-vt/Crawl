<p align="center">
	<img src="https://i.imgur.com/GNWwMFb.png" width="600px">
</p>

#### Version 2.0.0
#### By Priyank-vt
All in one tool for **Information Gathering** and **Vulnerability Scanning**

# Scans That You Can Perform Using RED HAWK :
+ Basic Scan
	- Site Title **NEW**
	- IP Address
	- Web Server Detection `IMPROVED`
	- CMS Detection
	- Cloudflare Detection
	- robots.txt Scanner
+ Whois Lookup `IMPROVED`
+ Geo-IP Lookup
+ Grab Banners `IMPROVED`
+ DNS Lookup
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner `IMPROVED`
	- Sub Domain
	- IP Address
+ Reverse IP Lookup & CMS Detection `IMPROVED`
	- Hostname
	- IP Address
	- CMS
+ Error Based SQLi Scanner
+ Bloggers View **NEW**
	- HTTP Response Code
	- Site Title
	- Alexa Ranking
	- Domain Authority
	- Page Authority
	- Social Links Extractor
	- Link Grabber
+ WordPress Scan **NEW**
	- Sensitive Files Crawling
	- Version Detection
	- Version Vulnerability Scanner
+ Crawler
+ MX Lookup **NEW**
+ Scan For Everything - _The Old Lame Scanner_

---
# Released Versions:
    - Version 1.0.0 [11-06-2017]
    - Version 1.1.0 [15-06-2017]
    - Version 2.0.0 [11-08-2017]

# Changelog:
- Version 1.0.0
    - Initial Launch
- Version 1.1.0
    - Updated The `fix` command
- Version 2.0.0
	- Separated all scans so that you are served the amount of information you need
	- `Sub-Domain Scanner` improved
	- `fix` command improved
	- `Web Server Detection` Improved
	- `CMS Detection` Improved
	- `Banner Grabbing` Improved
	- Added `WordPress Scanner`
	- Added `Bloggers View`
	- Added `MX Lookup`
	- Added `Update` option
	- RED HAWK Banner Updated
	- Many Other Internal Fixes

# Installation:
1. Run The Tool and Type `fix` This will Install All Required Modules.
2. For The Bloggers View To Work Properly you have to configure RED HAWK with moz.com's api keys for that follow the following steps:

# Usage:
- git clone `https://github.com/priyank-vt/Crawl`
- cd RED_HAWK
- php rhawk.php
- Use the "help" command to see the command list or type in the domain name you want to scan (without Http:// OR Https://).
- Select whether The Site Runs On HTTPS or not.
- Select the type of scan you want to perform
- Leave the rest to the scanner

# List of CMS Supported
RED HAWK's `CMS Detector` currently is able to detect the following CMSs (Content Management Systems) in case the website is using some other CMS, Detector will return _could not detect_.

- WordPress
- Joomla
- Drupal
- Magento
# Known Issues
**ISSUE:** Scanner Stops Working After Cloudflare Detection!

**SOLUTION:** Use The `fix` Command OR Manually Install *php-curl* & *php-xml*

# Suggestions And Feedbacks
Want to contribute to RED HAWK or point out something wrong? Just create a new issue here: https://github.com/Tuhinshubhra/RED_HAWK/issues/new
I'd love to hear from you.

# Support and Donations
Found RED HAWK cool? well you could buy me a cup of tea ;) (no alcohol plz xD) just send any amount of donations (in BTC) to this address : **1NbiQidWWVVhWknsfPSN1MuksF8cbXWCku**

Can't donate? well that's no problem just drop a **THANK YOU** this will motivate me to create more exciting stuffs for you ;)

# TODOs

- Make a proper update option ( Installs current version automatically )
- Add more CMS to the detector
- Improve The WordPress Scanner ( Add User, Theme & Plugins Enumeration )
- Create a web version of the scanner
- Add XSS & LFI Scanner
- Improve the Links grabber thingy under bloggers view
- Add some other scans under the Bloggers View
