---
author: supercobra
comments: false
date: 2016-01-25 17:10:34+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/01/scheduled-maintenance-saturday-january-30/
slug: scheduled-maintenance-saturday-january-30
title: 'Scheduled Maintenance: Saturday, January 30'
wordpress_id: 2246
categories:
- Product Updates
---

Mojo Helpdesk will be undergoing a system maintenance on Saturday, January 30, 2016 from 10:00 to 13:00 CST with expected downtime of 1 hour maximum.

During this maintenance, Mojo servers will be upgraded to improve performance and scalability. We also be moving to an encrypted database environment that will increase data protection.

Downtime is expected which means the Mojo Helpdesk web service will not be available. Incoming emails will be delayed, but nothing will be lost. All emails sent during this time will be received in the helpdesk after the service is restored.

Important status updates during the maintenance period will be posted on our [Twitter page](https://twitter.com/mojohelpdesk).

**CHANGES THAT MAY BREAK YOUR HELPDESK**

This maintenance will include changes in our DNS records. If you created DNS  A records pointing to Mojo Helpdesk's IP please read on, otherwise you can ignore this section.

**CHANGES YOU NEED TO MAKE AS SOON AS POSSIBLE**

1 - If you have an SSL certificate installed, and if you are using **DNS A** record that points to the IP number of our application, change it to a CNAME record that points to ssl.app.mojohelpdesk.com. You do not need to change anything if you are already using the CNAME record.

2 - If you don't have custom SSL certificate installed, and you are using **DNS A** record that points to the IP of our server, change it to a CNAME record that points to app.mojohelpdesk.com

3 - If you are using **DNS MX** record that points to our server, then change it to point to mail.app.mojohelpdesk.com.  Please note you will not need to place an MX record if you are using a CNAME record.

We apologize for any inconvenience this may cause but we are excited about the improved performance and scalabilty of Mojo Helpdesk. Thank you for your continuing support.

If you have any questions regarding this maintenance please [contact us](https://help.mojohelpdesk.com/).


