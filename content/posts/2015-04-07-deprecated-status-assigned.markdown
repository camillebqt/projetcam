---
author: supercobra
comments: false
date: 2015-04-07 13:40:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2015/04/deprecated-status-assigned/
slug: deprecated-status-assigned
title: 'Deprecated Status: Assigned'
wordpress_id: 59
categories:
- Product Updates
tags:
- help desk features
- help desk update
- Mojo Helpdesk
- ticket assignment
- ticketing
---

We recently made a change in Mojo Helpdesk to the ticket statuses. Back in March we changed the functionality so that ticket statuses were independent of the actual ticket assignment. Now in an effort to streamline the support process we have removed the 'assigned' status. Our goal is to always keep things simple and we feel the 'assigned' status doesn't serve a purpose any longer.


### There are two main reasons for this change:


1. When a new ticket is first assigned to an agent, the ticket will reflect 'new' status. An agent will receive an email that the ticket has been assigned to them, but in their 'My Assignments' list, the ticket will display as 'new' rather than 'assigned'. This helps an agent define tickets that are assigned to them but have not been worked on. A ticket should be placed 'in progress' by the agent when they start actually working on the ticket.

2. When a ticket is un-assigned or re-assigned, the ticket should retain the status of the previous agent. For example, if an agent leaves on vacation and un-assigns their tickets for other agents to pick up, the tickets should still reflect the original ticket status such as 'information requested' or 'on hold'.


### How does this change affect my tickets that were in 'assigned' status at the time of the change?


We have defaulted any tickets that were in 'assigned' status to an 'in progress' state. These tickets will still appear in the 'My Assignments' list under the category _Tickets I am Working On._


### How does this change affect automations I have filtered by status = assigned?​


Automations will still execute on assigned tickets. A​ny automation ​filtered by the 'assigned' status will need to be recreated using the ​'Is Assigned​?' filter. Please check your automations to be sure they are working correctly.

If you have any questions or feedback about this change, please submit a ticket in our [help center](https://help.mojohelpdesk.com/).
Thank you,

The Mojo Helpdesk Team
