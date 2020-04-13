---
author: supercobra thatbytes
comments: false
date: 2008-05-29 07:51:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2008/05/google-is-the-new-ibm/
slug: google-is-the-new-ibm
title: Google is the new IBM.
wordpress_id: 283
categories:
- Product Tips
---

After few weeks of beta testing, [Google App Engine](http://code.google.com/appengine/) has opened their signup to everyone. This is significant for several reasons: It makes hosting your web app really simple, cheap and scalable.  
  
If you think at all the steps it takes to host a web app and all the knowledge required to make it work, it is a fairly complicated and slow process.  
  
What we need from a hosting company to host a database backed website:  


  * Simple, affordable and quick setup
  * Enough CPU cycle when the app needs it
  * Good tech support
The painful reality includes the following steps:  


  * Buy a domain name
  * Choose a hosting company
  * Log in using the web hosting proprietary and sometimes not easy-to-use control panel
  * Setup users, passwords
  * Create a database
  * Zip your web app on your PC and upload it on your server  via FTP
  * Transfer the domain name to point to your hosted server
  * getting upset with the bad support of your hosting company  

  * get enough CPU cycles for your app to run smoothly
With Google App Engine it’s incredibly easy:  


  * Register your app
  * Run the deploy script from your development environment (yes, this is the only step!)
Done(!)  
  
What you get on top of it:  


  * Dynamic webserving, with full support of common web technologies
  * Persistent storage (powered by [Bigtable](http://labs.google.com/papers/bigtable.html) and [GFS](http://labs.google.com/papers/gfs.html) with queries, sorting, and transactions)
  * Automatic scaling and load balancing
  * Google APIs for authenticating users and sending email
and also...  


  * It’s free for small scale hosting and reasonably cheap for bigger scale requirements.
  * The application life cycle management is included: Google App Engine allows you to roll back to any previous version of your app at any time.
  * Automatic database schema update: no need to mess with phpMyAdmin. Your app will talk to Google and the database schema is managed automatically.
Google App Engine provides an ultra simple web app hosting solution that is more efficient, cheaper and dead easy to us.  It’s only available in the Python language at this point but Google plans to rollout other languages shortly. This means 90% of all standard web apps could use this service and they probably will because it only requires running the ‘deploy’ command to send your app to Google.  
  
Did you hear about the computing grid that is as pervasive and invisible as  the electricity grid? I thought IBM would make it available to the world like they did it for the Personal Computer but Google made it a reality for all of us.  
  
Google is the new IBM.
