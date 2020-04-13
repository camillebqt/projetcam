---
author: supercobra
comments: false
date: 2016-09-13 22:31:30+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/09/using-queue-access-rights-to-restrict-form-access/
slug: using-queue-access-rights-to-restrict-form-access
title: Using Queue Access Rights to Restrict Form Access
wordpress_id: 2580
categories:
- Product Updates
---

'Queue Access Rights' are settings where you can restrict users from submitting tickets to certain queues. For example, if you support several different types of clients you can allow clients from Company A to submit tickets only to Queue A and restrict them from Queue B and C.  Before the recent update, this worked great if you were only using one ticket form but with multiple ticket forms there was not a way to choose which forms could be restricted and consequently which queues on the forms could be restricted.  In other words queue access was not being restricted on multiple forms and not working as expected. With a recent modification to the Queue Access Rights handling, you can now use these settings to restrict access to certain forms and queues on secondary forms will follow the Queue Access Rights settings.

With that said, if you find that some users are suddenly not seeing forms they could previously see or cannot see queue values previously available, it is because your Queue Access Rights are set to restrict them. You may need to reconfigure your access settings in Admin> Queue Access Rights.

For others, the ability to restrict form access has been a highly requested feature.  To set this up you will need to be sure ticket forms default to a queue and then set Queue Access Rights for the user's group.

Here is how it works:



 	
  * Users are set to a Group.

 	
  * Groups are given rights to submit tickets to specific queues in Queue Access Rights.

 	
  * Forms are defaulted to specific Queues: Ticket Form> Ticket Fields> Queue> Edit> Remove Visibility from End User> Add Default> Save (So that anytime the form is filled out it always creates the ticket in the default queue).


Then:

 	
  * The Form will be visible only to Groups (users in a group) that have access to the default Queue of that Form.


[caption id="attachment_2584" align="aligncenter" width="691"]![queueaccessrights](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/09/queueaccessrights-1.jpg)          Configuration of 'Queue Access Rights' determining available Forms for a user Group.[/caption]



If you have any questions regarding this please visit our [help center](https://help.mojohelpdesk.com).



Thank you,

The Mojo Helpdesk Team












