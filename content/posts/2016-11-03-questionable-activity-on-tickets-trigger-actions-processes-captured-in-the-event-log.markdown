---
author: supercobra
comments: false
date: 2016-11-03 15:05:37+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/11/questionable-activity-on-tickets-trigger-actions-processes-captured-in-the-event-log/
slug: questionable-activity-on-tickets-trigger-actions-processes-captured-in-the-event-log
title: 'Questionable Activity on Tickets: Trigger Actions, Processes Captured in the
  Event Log'
wordpress_id: 2635
categories:
- Product Tips
- Product Updates
tags:
- Trigger Event Log
---

A few weeks ago we released Triggers to help automate actions on tickets.  Trigger actions and processes which may have affected a ticket's outcome is now listed  in the ticket's Event Log.

Recently, we had a customer report a questionable bug stating the priority of his ticket kept changing to Emergency. No matter what priority he chose, the ticket always went back to Emergency.  After looking at the Event Log he could see the process the Trigger took and also that the Trigger was responsible for changing the priority of that ticket.

![Screen Shot 2016-11-01 at 1.17.54 PM](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/11/Screen-Shot-2016-11-01-at-1.17.54-PM.png)

Keep in mind only agents with a Manager or Admin role are able to set up Triggers.  If you see some questionable activity on your tickets be sure to check the Event Log of the ticket.  If a Trigger is causing the behavior,  then you can speak to the Manager or Admin that set up the helpdesk to find out if this is the right action to be performing on tickets.

Now, if there is a question about which Manager or Admin actually created the Trigger, this can be looked up in the helpdesk's main Event Log. (Admin> Event Log). Searching for Action = Trigger will display a list of agents that created or updated Triggers.  Or you can click the Event Log icon next to the Trigger in the list. This should help you track down the creator of the Trigger in question.


![Trigger Event Log](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/11/trigger2.png)
