---
layout: post
comments: true
published: true
title: Learning Linux for Hosting
---

In my [last post][last-post], I mentioned that I was in the market for a new hosting service. Over the past week or so, I've been moving domains to a new virtual private server from [Digital Ocean](http://www.digitalocean.com). I've been consistently impressed with how well their system performs and the nice [tutorials][do-tutorials] that they feature. It has made things much easier to set up and configure.

One thing that I've been wanting to do for a while is take some time to see how a web server is set up and have a place to experiment. The Digital Ocean site makes this extremely easy. I have the option of taking a snapshot of the current server and can use that to activate a new system whenever I want. This way, I can try any sort of crazy idea without affecting my existing production server.

<!--more-->

Additionally, now that I am no longer using shared hosting, I know that all the server capacity is totally devoted to my sites that are running. This has brought the load time down significantly. I paired things up with a [Cloudflare](http://www.cloudflare.com) account to provide some basic CDN functionality and additional caching.

### Performance Improvements

The best performance improvement has been on my brother's blog, <http://patrickpadley.com>. At one point, his site was taking upwards of 25-30 seconds to display on the old system. After doing some investigating, changing a few caching plugins around and switching to the VPS, his site is now loading within a second or two. Not too bad of an improvement!

One of my biggest fears with moving to a VPS is having the knowledge to put the server together and lock it down. The tutorials on the Digital Ocean site made things very easy and, while I'm not the biggest expert on security, I feel like the sites that I'm hosting are protected. There's still a lot to learn, but for the moment, this has been a great experience in starting a new hosting project.

[last-post]: {% post_url 2013-10-22-now-hosted-on-github %}
[do-tutorials]: https://digitalocean.com/community