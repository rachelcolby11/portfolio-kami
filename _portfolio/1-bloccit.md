---
layout: post
title: Bloccit
thumbnail-path: "img/bloccit.png"
short-description: A Reddit replica where users can post, comment, and vote on links and content.

---

{:.center}
![]({{ site.baseurl }}/img/bloccit.png)

### Overview

Bloccit, a Reddit replica, is the first app I made as a Bloc student. Bloccit is a Ruby on Rails app that lets users post, comment, and vote on links and content. 

### Features
* Users and guests (those without accounts) can view public topics, posts, and comments.
* Users can create their own accounts in order to view private topics and posts and create their own posts and comments.
* Users can format their posts using Markdown.
* Users can favorite posts they like and vote posts up or down.
* Posts are organized by topic and sorted by their rank (determined by age and number of votes).
* Users can choose to receive email notifications when there are new comments on a post they have favorited.
* Users can upload images to use in their posts and as their avatar.

### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, AJAX, jQuery, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Test-Driven Development: RSpec, Capybara, FactoryGirl
* Amazon Web Services (S3) for image storage
* Devise for user authentication
* SendGrid for email notifications
* Redcarpet for Markdown formatting
* Will_paginate for pagination 
* Pundit for authorization