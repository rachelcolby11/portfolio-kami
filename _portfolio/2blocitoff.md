---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: A to-do list app that automatically deletes old items, forcing users to prioritize.

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)

### Overview

Blocitoff is a self-destructing to-do list application using Ruby on Rails. Users add items to to-do lists, and items are automatically deleted after seven days. This self-destructing functionality is designed to keep the list manageable: users must prioritize and complete items or let them go.

### Features
* Users can create an account and make their own personal to-do list.
* Users can create items, mark them as complete, or remove them from the list.
* The list will display the number of days until each item is scheduled for automatic deletion.
* At the end of each day, items more than 7 days old will be automatically deleted from the list.

### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, jQuery, AJAX, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Devise for user authentication
* SendGrid for email confirmation
* Heroku Scheduler for rake automation