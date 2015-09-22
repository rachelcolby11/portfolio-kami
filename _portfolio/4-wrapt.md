---
layout: post
title: Wrapt
thumbnail-path: "img/wrapt.png"
short-description: An app that lets users make and share lists of gifts they hope to receive.

---

{:.center}
![]({{ site.baseurl }}/img/wrapt.png)

{:.center}
<h5>
  <a href="https://wrapt.herokuapp.com/" class="button">
    Website
  </a>
  <a href="https://github.com/rachelcolby11/Wrapt" class="button">
    Source Code
    <i class="fa fa-fw fa-github"></i>
  </a>
</h5>

{:.center}
### Overview

Wrapt is a Ruby on Rails application that allows users to create a wishlist of gifts and view their friends'​ wishlists in one place. It's designed to make the process of gift-giving and gift-receiving easier,  less stressful, and more gratifying for everyone involved.

{:.center}
### The story behind Wrapt:
Wrapt was my capstone project at Bloc, and one that is very close to my heart. I want to give my family and friends amazing gifts, but it's hard to think up ideas that are truly worthy of them. At the same time, it can also feel awkward or presumptous to update my friends and family when I think of a gift I'd like to receive. I built Wrapt so that people could access up-to-date wishlists from their friends and family all in one place, and update their own wishlist without feeling obnoxious.

Although I began this project as a Bloc student, I've kept building on it since graduating. I've made continual updates to improve the user interface, and I constantly think of improvements I'd like to make and features I could add. I would ultimately like to monetize the app by leveraging the Amazon Product Advertising API to suggest items to users.

{:.center}
### What makes Wrapt unique?
* Unlike existing registry options, users can identify a specific product (like, "one-year subsciption to Apple Music") **or** they can simply describe something for the gift-giver to pick out on their own (like, "a new laptop bag, preferably pink or purple").
* Wrapt allows users to "claim"​ a gift they plan to purchase so that other users will know not to duplicate that gift.
* Wrapt also lets users restrict viewing permissions on items they want only certain friends or relatives to see. For instance, (believe it or not!) my parents are the only people I trust to buy me shoes. So if I wanted a new pair of boots, I'd restrict everyone but my parents from viewing that item.

{:.center}
### Features
* Users can create an account, make a profile describing their preferences, and create a list of gifts they would like to receive.
* Users can share their profile and gift list with other users, allowing them to view their preferences and desired items.
* Users can invite friends and family to join the site and view their gift list.
* Users can view a list of friends who can see their gift list, and a list of friends who have allowed them to view their lists.
* Users can add, edit, or remove items from their gift list, and update their profile and preferences at any time.
* Users can restrict viewing permissions on items so that only certain friends can see them.
* Users can "claim" an item they plan to purchase. (The person who created the item cannot see that the item has been claimed.)
* Seven days after claiming a gift, users receive a reminder to purchase the gift or release their claim so that others can purchase it.
* Users can create, edit, and delete quick notes of gift ideas they think of.
* After signing in, users are directed to a dashboard showing the items they have claimed, the notes they have made, and a list of friends whose birthdays are approaching within the next three months. 
* Users who still need to fill out their profile or add their birthday will see a reminder to do so at the top of the dashboard.

{:.center}
### Technologies
**Languages, Libraries, and Frameworks:** Ruby on Rails, Bootstrap

**Databases:** SQLite (Test, Development), PostgreSQL (Production)

**Development Tools, Gems and Methodologies:** 

* Devise for user authentication
* SendGrid for email notifications
* Pundit for authorization