---
layout: post
title: Blocipedia
thumbnail-path: "img/blocipedia.png"
short-description: A SaaS app where users create their own wikis and can opt to pay for premium.

---

{:.center}
![]({{ site.baseurl }}/img/blocipedia.png)

### Overview

Blocipedia is a Ruby on Rails application that allows users to create wikis and collaborate on other wikis. Users can pay to upgrade their membership, allowing them to view and create private wikis. 

### Features
* Anyone can view public wikis.
* Users can create a standard account in order to create and collaborate on public wikis.
* Users can pay to upgrade their account to Premium in order to view and create private wikis.
* Premium users can invite others to view and collaborate on the private wikis they create.
* Premium users can downgrade their account back to standard.
* When a user downgrades his or her account, his or her private wikis will automatically become public. 

### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Devise for user authentication
* SendGrid for email confirmation
* Pundit for authorization
* Stripe for payments