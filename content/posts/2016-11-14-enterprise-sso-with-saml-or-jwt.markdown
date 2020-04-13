---
author: supercobra
comments: false
date: 2016-11-14 21:18:38+00:00
layout: post
link: https://www.mojohelpdesk.com/blog/2016/11/enterprise-sso-with-saml-or-jwt/
slug: enterprise-sso-with-saml-or-jwt
title: Enterprise SSO with SAML or JWT
wordpress_id: 2644
categories:
- Product Tips
- Product Updates
---

Mojo Helpdesk provides no-fuss authentication methods such as Mojo's system login, Google and Azure Active Directory.  However, Mojo now supports the use of SSO using either SAML (Secure Assertion Markup Language) or JWT (JSON Web Token).  Both SAML and JWT are available on the Enterprise plans.  Using either method will replace Mojo's out-of-the-box authentication methods.

Once enabling Enterprise Single Sign-On you can set up a 3rd party identity provider to authenticate users externally thus bypassing the Mojo login methods.  Whether you use SAML or JWT to do this depends on the 3rd party service's capability. Typically SAML is an easier setup and can be done from the Identity Provider's interface (Oracle, SAP, LDAP, OneLogin, etc).  JWT is more of a custom build you will need to implement in an application that supports it, most likely one you have developed internally.

For example, if you are an app developer and you want users logged into your app to be authenticated in your Mojo Helpdesk to access support, you would use JWT to accomplish this.  SAML would be used if you wanted your Mojo Helpdesk users to be authenticated using LDAP or some other Identity Provider.

[caption id="attachment_2646" align="aligncenter" width="712"][![Authentication using JWT](http://www.mojohelpdesk.com/blog/wordpress/wp-content/uploads/2016/11/JWT.jpg)](JWT) Authentication using JWT[/caption]

Learn how to set up Enterprise Single Sign-On methods in our [Knowledge Base](https://help.mojohelpdesk.com/help/search?query=%22Enterprise+Single+Sign+On%22).






