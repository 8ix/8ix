---
layout: post
title:  "Improve your website security and performance with Sucuri"
date:   2016-04-08 22:30:00 +0000
categories: security performance 
featured: Security & Performance
icon: sucuri.jpg
description: While the tips that WordPress provide to improve security greatly prevent a compromise, They are not always practical to maintain regularly when managing a large quantity of sites. From my experience “time” has been the primary issue, resulting in not being able to update WordPress quick enough to protect it from the next vulnerability.
color: pink
permalink: /website-performance-and-security-with-sucuri
---

About two years ago I was asked to find a solution to prevent recurring attacks on one of our WordPress sites. It was compromised many times, and no matter what precautions I put in place the site still seemed to be re-infected. My initial investigation for preventing attacks started by following the usual good practice guidelines such as:

My initial investigation for preventing attacks started by following the usual good practice guidelines such as:

1. Update WordPress along with your plugins to the latest versions
2. Hardening the WordPress Core files
3. Moving the WP-Config.php one directory back out of the root directory
4. Ensuring your File permissions are correct

See the official Wordpress resource for tightening your WordPress installation below:
(<a href="https://codex.wordpress.org/FAQ_My_site_was_hacked" target="_BLANK">https://codex.wordpress.org/FAQ_My_site_was_hacked</a>).

While the tips that WordPress provide to improve security prevent a compromise, They are not always practical to maintain when managing a lot of sites. From my experience “time” has been the primary issue, resulting in not being able to update WordPress quick enough to protect it from the next vulnerability.

On the same WordPress Codex link specified above, I spotted multiple references to the company name “Sucuri.” It seemed that the official WordPress Codex referred to the Sucuri blog as a resource for cleaning up compromised WordPress sites. While reading through Sucuri’s guide, I discovered their Firewall product at the time labeled as ‘CloudProxy’ which I decided trial across our sites. 

Sucuri’s primary selling point is through hack prevention along with a malware removal services. CloudProxy, which is their Firewall offering, has both a predefined traffic filter managed by sucuri. This filter blocks known bad IP ranges, Problematic geographical areas and also monitors your user's activity for malicious use. All of these can be seen through their detailed reporting.

One of Sucuri’s chief selling points for me was their virtual patching. Which claims to protected known WordPress version vulnerabilities no matter what version you are running, providing that your website runs through their firewall. Security also isn’t the only benefit for running your site through their firewall. Similar to other services such as CloudFlare the website is distributed through Sucuri’s Content delivery service (CDN) to your users along with their site compression, speed, and caching options, All of which is customizable through the admin panel.

Setting up your website to use CloudProxy is also really easy, It requires you to setup couple of DNS records to point to an IP address that Sucuri assigns to you. I found this method better than other services in the market such as CloudFlare that requires you to assign your Name servers with them instead. Depending on your client changing the name servers of a domain isn’t always possible.

Sucuri’s second offering which I have also started to use is their malware scanning and removal services. Sucuri scan your site frequently and notify you if compromised. Once notified you can arrange with them to clean the website via FTP. Upon their completion, you are given a breakdown of what happened along with the actions they have taken and recommendations for you to complete. 

I have now been using Sucuri’s services for the last couple of years and highly recommend their services; I have rolled out their services across the majority of my sites, and all using the service have remained clean and unharmed. 

Sucuri also has a ton of services and features I haven’t mentioned which you will find details for on their site at <a href="https://sucuri.net/">https://sucuri.net/</a>


