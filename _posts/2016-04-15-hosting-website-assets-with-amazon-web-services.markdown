---
layout: post
title:  "Hosting website assets with Amazon S3 and Cloudfront"
date:   2016-04-15 20:00:00 +0000
categories: Website performance 
featured: Website Performance
description: Hosting your websites images, videos, stylesheets and javascript via two of Amazons Web Services (AWS) comes with stacks of benefits and has become the perfect solution for my development environment. 
color: blue
permalink: /hosting-website-assets-with-amazon-s3-and-cloudfront
---

Hosting your websites images, videos, stylesheets and javascript via two of Amazons Web Services (AWS) comes with stacks of benefits and has become the perfect solution for my development environment. 

The First Service is Amazon S3 Storage. Which is online storage space organised through a file structure Amazon call buckets. You would usually set up a new bucket to separate your client or project assets. S3 is similar to other online storage services such as Dropbox, SugarSync or Onedrive where you can store virtually any static based file. The difference with S3 Storage is that its target users are going to be those of technical background in web and software development, alike all of the AWS services. 

The Second Service is Amazons Content delivery network (CDN) called "Cloudfront".  Any file or assets accessed through CloudFront or any CDN is set up for global delivery to your users, Whatever location your end user is viewing the site from they will automatically download the asset through the nearest Amazon server to their location. Delivery of static files will be sent at the quickest speeds and configured for both caching and compression. The combination of fast delivery, caching and compression will add to your overall sites performance.

Unlike other CDN services such as CloudFlare and Sucuri, CloudFront offers a lot more complexity. Rather than running your entire site through the CDN Amazon lets you choose what you want to run through the service, such as an S3 Bucket or a hosted directory on one of your servers. CloudFront is also enabled for the Real Time Media Protocol to stream sound and video.

The Amazon services described above have vastly improved my overall websites performance and development process. To explain how these services improved my development flow I will need to outline my process.

A typical website project in my team runs across three servers. A local server using  Vagrant, A Staging server using a digital ocean and a live production server. Over the course of development, the build starts moving across each one of our servers via our version control GIT repository.  We are fairly strict and content based images and static assets not associated directly with our website theme do not get committed to the repository. We do this to keep the repository size minimal. When viewing the site on each server or if another developer joins the project, we have to ensure a local copy of the assets is copied across to avoid any broken links.

Our answer to seamlessly move across each server environment without moving assets is to host your user content directly through Amazon S3 Storage, and then serve through Amazon Cloudfront for performance benefits. Wherever the website sits, all the image content is loaded in from Amazon S3.

If you are a WordPress user there is a plugin called Offload S3 by Delicious brains which handle all of the AWS connectivity and the integration of both S3 and Cloudfront: 
<a href="https://wordpress.org/plugins/amazon-s3-and-cloudfront/" target="_blank">https://wordpress.org/plugins/amazon-s3-and-cloudfront/</a>

S3 and Cloudfront can be setup on any Content management system (CMS) or website project by finding a plugin or implementing your solution using the API's.
<a target="_blank" href="https://aws.amazon.com/cloudfront/">https://aws.amazon.com/cloudfront/</a>