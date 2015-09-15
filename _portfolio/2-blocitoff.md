---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: A to-do list app that automatically deletes old items, forcing users to prioritize.

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)

{:.center}
<h5>
  <a href="https://blocitoff-rc.herokuapp.com/" class="button">
    Heroku Demo
  </a>
  <a href="https://github.com/rachelcolby11/Blocitoff" class="button">
    Source Code
    <i class="fa fa-fw fa-github"></i>
  </a>
</h5>

{:.center}
### Overview

Blocitoff is a self-destructing to-do list application using Ruby on Rails. Users add items to to-do lists, and items are automatically deleted after seven days. This self-destructing functionality is designed to keep the list manageable: users must prioritize and complete items or let them go.

{:.center}
### Features
* Users can create an account, make their own personal to-do list, and add new items to their list.
* The list will display the number of days until each item is scheduled for automatic deletion.
* Once users complete an item, they can mark it as complete and remove it from the list.
* At the end of each day, items more than 7 days old will be automatically deleted from the list.

{:.center}
### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, jQuery, AJAX, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Devise for user authentication
* SendGrid for email confirmation
* Heroku Scheduler for rake automation