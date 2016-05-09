---
layout: post
title: Bloccit
thumbnail-path: "img/bloccit.png"
short-description: A Reddit replica where users can post, comment, and vote on links and content.

---

{:.center}
![]({{ site.baseurl }}/img/bloccit.png)

{:.center}
<h5>
  <a href="https://bloccit-rc.herokuapp.com/" class="button">
    Heroku Demo
  </a>
  <a href="https://github.com/rachelcolby11/Bloccit/" class="button">
    Source Code
    <i class="fa fa-fw fa-github"></i>
  </a>
</h5>

{:.center}
### Overview

Bloccit, a Reddit replica, is the first Ruby on Rails app I built. Bloccit is a Ruby on Rails app that lets users post, comment, and vote on links and content.

{:.center}
### Features
* Users and guests (those without accounts) can view public topics, posts, and comments.
* Users can create their own accounts in order to view private topics and posts and create their own posts and comments.
* Users can format their posts using Markdown.
* Users can favorite posts they like and vote posts up or down.
* Posts are organized by topic and sorted by their rank (determined by age and number of votes).
* Users can choose to receive email notifications when there are new comments on a post they have favorited.
* Users can upload images to use in their posts and as their avatar.

{:.center}
### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, jQuery, AJAX, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Test-Driven Development: RSpec, Capybara, FactoryGirl
* Amazon Web Services (S3) for image storage
* Devise for user authentication
* SendGrid for email notifications
* Redcarpet for Markdown formatting
* Will_paginate for pagination 
* Pundit for authorization

{:.center}
<h5>
  <a href="/portfolio/2-thebuzz/" class="button next-project">
    Next: The Buzz
    <i class="fa fa-chevron-right"></i>
  </a>
</h5>