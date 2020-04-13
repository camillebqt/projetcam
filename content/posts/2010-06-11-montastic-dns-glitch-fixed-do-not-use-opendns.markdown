---
author: supercobra thatbytes
comments: false
date: 2010-06-11 14:31:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2010/06/montastic-dns-glitch-fixed-do-not-use-opendns/
slug: montastic-dns-glitch-fixed-do-not-use-opendns
title: 'Montastic DNS glitch fixed: do not use OpenDNS'
wordpress_id: 247
categories:
- Product Updates
---

We fixed a DNS issue that caused non-existent domains to resolve. This happened when "someone" at Metadot reconfigured one of our DNS servers to use OpenDNS as a forwarder. To our surprise Montastic started to alert us of a non-existent domain name being "up and running." This happened because OpenDNS intercepts all unresolved requests and returns the IP of their server instead of nothing. This violates the DNS protocol.


[![wrongway](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2010/06/wrongway.jpg)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2010/06/wrongway.jpg)

Why does OpenDNS do this?

To make money. From a practical standpoint, web users misspelling a URL will end up seeing an OpenDNS search page filled with advertising. OpenDNS has contracts with major search engine providers to do this.

Why is this bad?

Resolving non-existing domain names is wrong because it breaks the domain name protocol which is a standard used by hundreds of millions of systems.

On the Internet, network standards must be followed just as driving rules are on the road: most accidents occur when rules are violated.
