---
author: supercobra
comments: false
date: 2016-11-01 16:05:28+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/11/backdoor-admin-access-to-mojo/
slug: backdoor-admin-access-to-mojo
title: Backdoor Admin Access to Mojo
wordpress_id: 2626
categories:
- Product Tips
- Product Updates
---

We recently released new functionality that allows specified login methods to be displayed on the user login page. With this comes the question: What will account admins do if they select to display only the Google login method, but the Google SSO integration goes down?

Hey, it's happened with Google before and it's not something we here at Mojo can fix, we have to wait for Google to come back up.  So, if this happens (hopefully won't) but if it does, Admins in Mojo can always get into their account by clicking the Can't login link at the bottom of the login area.

![cantlogin](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/10/cantlogin.jpg)
This will lead the user to a help article that will have a working link _**for admins only**_ to their Mojo Helpdesk account login fields. If the admin does not remember his/her system password, they can use the 'forgot password' link on that page.
![newlogin3](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/10/newlogin3.jpg)

We hope this helps if you ever find the services for SSO with Google or Azure Active Directory are not working, admins can still get into the helpdesk account to allow the Mojo login temporarily until the Google or Microsoft issue is resolved.












