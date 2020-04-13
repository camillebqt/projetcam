---
author: supercobra thatbytes
comments: false
date: 2012-02-17 10:44:00+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2012/02/tip-of-the-week-bypass-the-googleyahoo-sign-on-by-adding-a-login-to-your-portal-homepage/
slug: tip-of-the-week-bypass-the-googleyahoo-sign-on-by-adding-a-login-to-your-portal-homepage
title: 'Tip of the Week: Bypass the Google/Yahoo Sign-On By Adding a Login to Your
  Portal Homepage'
wordpress_id: 167
categories:
- Product Tips
---

We made it easy for users to login to Mojo Helpdesk by providing single sign-on through Google and Yahoo. For many companies this is a welcomed feature. However, some companies prefer avoiding this as it requires users to login with their Gmail or Yahoo account.  We have a solution for anyone wanting to avoid the Google/Yahoo sign-on. By placing a login form on the homepage of the customer portal, you can encourage your staff to avoid using the single sign-on when logging into the helpdesk.







To add this feature to your customer portal, you will need owner/admin access to your helpdesk. Select All Settings from the Manage menu and then click Configure Mojo Helpdesk from the Helpdesk Owner/Admins column. Then, from the Helpdesk Settings page, click the change button. We are going to be editing the Portal Home, which can be found in the Customer Portal Customization section, by adding some code that will insert the login form. Take some time to look at your portal home page and decide where you want the form to be. For this example, we're going to put it at the top of the page so it's the first thing people see.


Insert the following bit of code into the Portal Home section, replacing the two mentions of yoursiteaddress (text in red) with the site address for your help desk. If you have a custom domain,  you'll need to replace the entire url  with your custom domain. For example, in this situation, Metadot has a custom domain, so we used: https://support.metadot.com/login for the form action and https://support.metadot.com for the input value.


<blockquote>

> 
> yoursiteaddress.[mojohelpdesk.com/login](http://mojohelpdesk.com/login)" id="login_form" method="post">
yoursiteaddress" type="hidden"> 

remember me on this computer

[>I forgot my password](/login/request_password)
<table border="0" >
<tbody >
<tr >
Email Address:
</tr>
<tr >
Password:


</tr>
</tbody>
</table>





> 
> </blockquote>







Once you have the code personalized and placed in the Portal Home section, click save to push the changes live.







Now you can encourage your people to login through this form and avoid the Google/Yahoo single sign-on.



