---
author: supercobra thatbytes
comments: false
date: 2013-05-20 12:24:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2013/05/how-to-turn-tweets-into-helpdesk-tickets/
slug: how-to-turn-tweets-into-helpdesk-tickets
title: How to Turn Tweets into Helpdesk Tickets
wordpress_id: 113
categories:
- Product Tips
tags:
- Help desk
- tickets
- tweet
- twitter
---

You may not have asked for it, but it's happening.

Your clients are using Twitter to reach out to you when they need customer support.<!-- more -->

[![40 Turn customer Tweets into helpdesk tickets](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-Turn-customer-Tweets-into-helpdesk-tickets.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-Turn-customer-Tweets-into-helpdesk-tickets.png)


Turn customer Tweets into helpdesk tickets with our latest mash up.
(Photo credit: @daskeyboard)


Their question, requests, and complaints are in the public eye; your responsiveness and service quality are out in the open for anyone to see.

It's the perfect time to start getting systematic about how you address support via social media channels.

Having your customer's Tweets automatically turn into helpdesk tickets is a great place to start so we've setup a little hack to make it happen.

You'll need a Gmail account and a Mojo Helpdesk account for this to work.

###


### Step 1 (Optional). Create a Helpdesk Queue for Tweets


If you haven't done so yet, sign up for a trial of Mojo Helpdesk.

From your Mojo Helpdesk navigation bar, click 'manage' >> 'Queues and email addresses' and click the 'New' button. Enter a queue name and an email address and then click the 'create queue' button. You now have a place for all your customer's Tweets to be stored as tickets that you can follow up on.

Make note of the email address you created because you'll need it for Step 3.

For this example, I created a new helpdesk queue called Twitter and set my queue email address as twitter@ryanluedecke.mojohelpdesk.com:

[![40 1 Mojo Queue and Email Settings](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-1-Mojo-Queue-and-Email-Settings.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-1-Mojo-Queue-and-Email-Settings.png)

If you already have a Mojo Helpdesk account, you may prefer to use an existing queue that you've already setup. To use an existing queue, click 'manage' >> 'Queues and email addresses'and find the email address associated with the queue you plan to use. Take note of this email address because you'll need it for Step 3.


### Step 2. Link Twitter to a Gmail address.


Log in to Twitter. Click the gear icon in the upper right hand corner of the navigation bar, then click Settings. In the Account view enter a valid Gmail address in the email field.

Check Gmail to confirm your account is receiving Twitter notifications. You should have a verification message from Twitter.

[![40 2 Twitter Email Settings2](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-2-Twitter-Email-Settings2.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-2-Twitter-Email-Settings2.png)




### Step 3. Tell Twitter which Tweets to send to Gmail.


Click the gear icon in Twitter and select Settings. In the Email Notifications screen you need to tell Twitter which Tweets to send as email notifications to your Gmail inbox.

For my helpdesk I selected "My Tweets get a reply or I'm mentioned in a Tweet - By anyone" and "I'm sent a direct message" as these are the types of Tweets that are most likely to contain a customer inquiry, a new feature request, or a complaint.


### [![40 3 Twitter Settings for Notifications](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-3-Twitter-Settings-for-Notifications.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-3-Twitter-Settings-for-Notifications.png)
Step 4. Tell Gmail where to forward Tweets.


Open Gmail. Click the gear icon in the upper right, then select Settings. Click the Forwarding and POP/IMAP tab.

Enter the queue email address from Step 1. Gmail sends a confirmation code that you need to grab from your 'Unassigned' tickets view (or 'Unassigned' >> 'Guest Requests' view if you have special filters or automations set up).

After verifying your code, click the 'Disable' forwarding button and scroll down and click the'Save Changes' button. When you finish this step, your settings will look like this:


### [![40 4 Forward settings Twitter Hack](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-4-Forward-settings-Twitter-Hack.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-4-Forward-settings-Twitter-Hack.png)
Step 5. Tell Gmail which Tweets to Forward.


Log into Gmail. Click the gear icon in the upper right, then select Settings. Click the Filter tab. Click the 'Create a new filter' link and fill in the filter pop up form as follows:


From: *@postmaster.twitter.com




(this is the email domain Twitter uses to deliver every email notification as of 5/15/13. The asterisk tells Gmail to include any email with a domain of postmaster.twitter.com)


Has the words: _"mentioned"_ OR _"direct message"_

Leave the other field blanks. When finished, click the 'Create filter with this search' link.

Here's how it will look on screen:

[![40 6 Gmail Filter2](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-6-Gmail-Filter2.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-6-Gmail-Filter2.png)
Now you need to check the 'Forward it to:' box and select the forwarding address you set up in Step 1. Click 'Create filter' (or 'update filter' as shown below) and you're finished.

[![40 5 Gmail Filter](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-5-Gmail-Filter.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/05/40-5-Gmail-Filter.png)
**Note 1:** Filter fields in Gmail work just like Google Search by giving you more control with search operators like the asterisk (*). The asterisk (*) serves as a placeholder for any unknown or "wildcard" terms. Here it protects our filter if Twitter changes the local part, or first part, of the email which looks like something this for notifications:"n-elna=zrgnqbg.pbz-ab31d".

**Note 2:** There are probably several ways to set this Gmail filter, but unless you are an expert and willing to troubleshoot, I'd recommend using the filters as shown in the screen shot above. The filter example is especially useful if you've having Twitter send you notifications for new followers and retweets as you probably don't want those flowing into your helpdesk as tickets.

#####

Once these steps are complete, you'll get notices when people Tweet you, reply to a Tweet, or send you a direct message on Twitter.

Questions about this Twitter mash up or about our hosted helpdesk software in general? Send them to me at ryan (at) metadot

All the best,
Ryan
