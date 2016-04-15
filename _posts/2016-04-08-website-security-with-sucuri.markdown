---
layout: post
title:  "Improve your website security and performance with Sucuri"
date:   2016-04-08 22:30:00 +0000
categories: security performance 
featured: Security & Performance
description: Two years ago I was asked to find a solution to prevent recurring attacks on a Hacked WordPress site, no matter what precautions I put in place the site still seemed to get re-infected.
color: pink
permalink: /website-performance-and-security-with-sucuri
---

Two years ago I was asked to find a solution to prevent recurring attacks on a Hacked WordPress site, no matter what precautions I put in place the site still seemed to get re-infected. My initial investigation for preventing attacks started by following the usual good practice guidelines such as:

My initial investigation for preventing attacks started by following the usual good practice guidelines such as:

1. Update WordPress along with your plugins to the latest versions
2. Hardening the WordPress Core files
3. Moving the WP-Config.php one directory back out of the root directory
4. Ensuring your File permissions are correct

While I am not going to go into this in depth you can see the official Wordpress resource for tightening your WordPress install below:
(<a href="https://codex.wordpress.org/FAQ_My_site_was_hacked" target="_BLANK">https://codex.wordpress.org/FAQ_My_site_was_hacked</a>).

While the tips that WordPress provide improve security to prevent a compromise, They are not always practical to maintain when managing multiple sites. From experience “time” has been the primary issue, with the result not being able to update WordPress quick enough to protect it from the next vulnerability.

On the same WordPress Codex link specified above, I spotted multiple references to the company name “Sucuri.” It seemed that the official WordPress Codex referred to the Sucuri blog as a resource for cleaning up compromised WordPress sites. While reading through Sucuri’s guides, I discovered their Firewall product offering called CloudProxy and instantly took the decision to trial across one of my sites. 

Sucuri’s primary selling point is hack prevention along with malware removal services. CloudProxy, which is their Firewall offering, has a predefined traffic filter managed by sucuri. This filter blocks known bad IP ranges, Problematic geographical areas and also monitors your user's activity for malicious use. If one of the filter conditions are met, they are instantly blocked from accessing the site. A detailed report of full site activity is in the admin panel.

One of Sucuri’s leading selling points for me was their virtual patching. Which claims to protected known WordPress version vulnerabilities no matter what version of Wordpress that you are running, providing that your website runs through their firewall. Security also isn’t the only benefit for using their firewall. Similar to other services such as CloudFlare the website is distributed through Sucuri’s Content delivery service (CDN) to your users along with their site compression, speed, and caching options, All of which is customizable through the admin panel.

Setting up your website to use CloudProxy is also really easy, It requires you to setup couple of DNS records to point to an IP address that Sucuri assigns to you. I found this method better than other services in the market such as CloudFlare, which requires you to assign your name servers with them instead. Requiring your client to change the name servers of their domain is not always possible if they are using other DNS management services.

Sucuri’s second offering which I have also now started to use is their malware scanning and removal services. Sucuri scan your site frequently and notify you if compromised. Once notified you can arrange with them to clean the website via FTP. Upon their completion, you are given a breakdown of what happened along with the actions they have taken and recommendations for you to complete. I have had three sites cleaned by them recently and each clean up has been fine. 

I have now been using Sucuri’s services for two years and can not find any alternatives with the same offerings. Overall I have been impressed by their services and highly recommend them; 

I have rolled out their services across the majority of my sites, and each site using the CloudProxy has remained clean and unharmed. Sucuri also has a tonne of services and features I have not given justice which is available on their site at <a href="https://sucuri.net/">https://sucuri.net/</a>


