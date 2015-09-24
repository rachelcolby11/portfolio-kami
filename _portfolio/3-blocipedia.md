---
layout: post
title: Blocipedia
thumbnail-path: "img/blocipedia.png"
short-description: A SaaS app where users create their own wikis and can opt to pay for premium.

---

{:.center}
![]({{ site.baseurl }}/img/blocipedia.png)

{:.center}
<h5>
  <a href="https://blocipedia-rc.herokuapp.com/" class="button">
    Heroku Demo
  </a>  
  <a href="https://github.com/rachelcolby11/Blocipedia" class="button">
    Source Code
    <i class="fa fa-fw fa-github"></i>
  </a>
</h5>

{:.center}
### Overview

Blocipedia is a Ruby on Rails application that allows users to create wikis and collaborate on other wikis. Users can pay to upgrade their membership, allowing them to view and create private wikis. 

{:.center}
### Features
* Users can create a standard account in order to create, edit, and collaborate on public wikis using Markdown syntax. Anyone can view public wikis.
* Users can pay to upgrade their account to Premium in order to view and create private wikis.
* Premium users can allow others to view and collaborate on the private wikis they create.
* Premium users can downgrade their account back to Standard.
* When a user downgrades his or her account, his or her private wikis will automatically become public. 

{:.center}
### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Devise for user authentication
* SendGrid for email confirmation
* Redcarpet for Markdown formatting
* Pundit for authorization
* Stripe for payments