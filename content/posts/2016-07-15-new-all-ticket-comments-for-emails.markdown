---
author: supercobra
comments: false
date: 2016-07-15 20:24:55+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/07/new-all-ticket-comments-for-emails/
slug: new-all-ticket-comments-for-emails
title: 'New: All Ticket Comments for Emails'
wordpress_id: 2498
categories:
- Product Updates
---

When an agent comments on a ticket, Mojo sends an email to the ticket submitter and also to any cc'd recipients containing the message they have just added.  However, if you want the previous comment or all comments that were previously added to the ticket you can now add a variable to the '_message added'_ email template to display this.

These new variables allow more freedom for cc'd users and ticket submitters. They will no longer need to login to the ticket to see the full details or message thread since it will be displayed on the email itself.

To set this up you will need to edit the 'Message Added' email template: Admin> Email Templates

Choose the template and click on the link to view available variables at the bottom of the email body.  The options include last comment, all public comments, or all comments including private.  Add the variable to the bottom of the email template.

In this example below, the variable {{ticket.all_comments}} was pasted into the email template with a section to define the area called 'previous comments'. This variable will show ALL comments including private comments to the ticket submitter and cc'd users. If you just want to display public comments use the {{ticket.public_comments}} variable.

![Screen Shot 2016-07-14 at 4.47.24 PM](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/07/Screen-Shot-2016-07-14-at-4.47.24-PM.png)
When sent to the ticket submitter and cc'd recipients, the email will look like this:

![Screen Shot 2016-07-14 at 5.08.27 PM](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/07/Screen-Shot-2016-07-14-at-5.08.27-PM.png)



Again, adding the variable to the 'message added' email template will save the end-users from needing to login. CC'd users will now be able to see the entire ticket comment thread without needing to login to the help center.

We hope this helps delight your customers. Please feel free to send feedback.

Thank you,

Mojo Helpdesk
