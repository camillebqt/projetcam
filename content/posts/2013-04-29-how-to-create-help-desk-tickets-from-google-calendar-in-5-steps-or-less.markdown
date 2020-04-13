---
author: supercobra thatbytes
comments: false
date: 2013-04-29 17:06:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2013/04/how-to-create-help-desk-tickets-from-google-calendar-in-5-steps-or-less/
slug: how-to-create-help-desk-tickets-from-google-calendar-in-5-steps-or-less
title: How to Create Help Desk Tickets from Google Calendar in 5 Steps (or Less)
wordpress_id: 116
categories:
- Product Tips
tags:
- google calendar
- Help desk
- how to
- tickets
---

It's a Google Calendar event. It's a help desk ticket. It's a do-it-yourself mash up that can be configured in 5 steps or less. If you've ever wanted your Google Calendar events to flow straight into helpdesk a ticket, here's how you do it:
_(Author's note: You'll need a Mojo Helpdesk account to get started. Sign up on our home page for a 30-day free trial.)_

[![Crowd go wild](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/Crowd-go-wild.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/Crowd-go-wild.png)


Girl Talk's new mash up makes the crowd go wild. Mojo's will too.  (photo credit: milkshake media)





### Step 1 (Optional). Create a new queue for your Google Calendar events


From your Mojo Helpdesk navigation bar, click '**manage**' >> '**Queues and email addresses**' and click the '**New**' button.  Enter a queue name and an email address and then click the '**create queue**' button.  Make note of the email address you created because you'll need it for Step 3.For this example, I created a new queue called Google Calendar and set my email address as calendar@ryanluedecke dot mojohelpdesk.com dot com :
[![42 2 - Mojo Queue and Email Settings2](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-2-Mojo-Queue-and-Email-Settings2.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-2-Mojo-Queue-and-Email-Settings2.png)
Instead of creating a new queue, you may prefer to use an existing queue that you've already setup. To use an existing queue, click '**manage**' >> '**Queues and email addresses**' and find the email address associated with the queue you plan to use. Take note of this email address because you'll need it for Step 3.Also, you'll need to temporarily enable guests requests in your helpdesk if they're not already enabled. To do so, click **manage >> all settings >> configure Mojo Helpdesk >> change >> check the box for Allow unregistered users to create tickets? >> uncheck the box for Email initiated guests requests confirmation required? >> save**


### Step 2. Set up email reminders in Google Calendar.** **


Open Google Calendar. Click the gear icon in the upper right, then select **Settings**. In the Calendars Settings screen, click the '**Calendars**' link. On the Calendars page, click the link for '**Reminders and notifications**' and then set up email reminders as shown below (don't forget to hit the Save button).
[![42 3 - Make sure your Google Calendar is set to send email reminders2](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-3-Make-sure-your-Google-Calendar-is-set-to-send-email-reminders2.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-3-Make-sure-your-Google-Calendar-is-set-to-send-email-reminders2.png)


### Step 3. Set up a forwarding address in Gmail.


Open Gmail. Click the gear icon in the upper right, then select Settings. Click the **Forwarding and POP/IMAP** tab.

Enter the queue email address from Step 1. Gmail sends a confirmation code that you need to grab from your '**Unassigned**' tickets view (or **'Unassigned' >> 'Guest Requests'** view if you have special filters or automations set up).

After verifying your code, click the '**Disable**' forwarding button and scroll down and click the '**Save Changes**' button. When you finish this step, your settings will look like this:
[![42 4 Forward settings2](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-4-Forward-settings2.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-4-Forward-settings2.png)


### Step 4. Set up a filter in Gmail.


Keep Gmail open. Click the gear icon in the upper right, then select Settings. Click the **Filter** tab. Click the '**Create a new filter**' link and fill in the filter pop up form as follows:

_From:_
(this is the email Google uses to deliver every Calendar reminder as of 4/29/13)

_To: your Gmail address_
(I entered my Gmail address: ryan |at| metadot dot com)

_Subject: Reminder(Optional) Has the words: #www.mojohelpdesk.com/blog_
(If you only want certain events to show up as tickets, set this filter and tag your Google Calendar events with '#www.mojohelpdesk.com/blog' in the title or description. In the example below, I want all Google Calendar events to create Mojo tickets so I didn't use this filter.)

Leave the 'Doesn't have' field blank. When finished, click the 'Create filter with this search' link.
[![42 5 Filter settings 1](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-5-Filter-settings-1.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-5-Filter-settings-1.png)

Now you need to check the '**Forward it to:**' box and select the forwarding address you set up in Step 1.  Click '**Create filter**' and you're finished (see example screen shot below).

[![42 6 Forward settings 3](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-6-Forward-settings-3.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-6-Forward-settings-3.png)


### Step 5. (Optional) Auto-assign the Google Calendar tickets to yourself.


Now that your Google Calendar event reminders are creating tickets in your help desk, you may want to auto-assign them to yourself using an automation.

To get started, click '**manage**' >> '**Automations**' then click the '**new**' button. Give the automation a title and then scroll down to the '**Assign to:**' field and select yourself from the drop down menu. From there, click '**Create & Activate**'. When this automation is activated, you'll be able to manage your Google Calendar tickets from your My Assignments view as shown below.
[![42 7 Automation1](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-7-Automation1.png)](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2013/04/42-7-Automation1.png)

###

Did you enjoy this mash up? If so, please [tweet this message](https://twitter.com/intent/tweet?text=Excited+that+I+can+create+@mojohelpdesk+tickets+from+Google+Calendar.+Try+it+for+free+at+mojohelpdesk.com) and help us spread the word about Mojo Helpdesk. Every tweet is appreciated.

Questions about this mash up or about our [ticket tracking software](http://www.mojohelpdesk.com/) in general? Send them to me at ryan (at) metadot

All the best,
Ryan
