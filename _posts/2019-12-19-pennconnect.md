---
layout: post
title:  "PennConnect"
comments: false
author: parth
categories: [ Projects ]
image: assets/images/pennconnect_2.png
---
<div style="padding: 1vw; border:0.2vw solid #212529;">
<a href="https://github.com/parthnatu/pennconnect"><i style="margin-right: 2vw" class="fab fa-github fa-4x"></i></a>
<span style="padding-bottom: 2vw">The code repository can be found here.</span>
</div>
PennConnect is a full-stack social network built from scratch. It was an attempt in collaboration with my teammates at using a graph database in combination with a conventional RDBMS to capture data and relationships between the users on the platform.

It supports the following functionalities:
- Sign in and Sign out sessions
- A user-specific news feed
- UI for profile, groups and events
- The ability to create, view, edit and delete comments
- Authentication for users
- Schedule events
- Create, view, edit and delete users, posts, events
- Friend and unfriend users
- Search for users, groups and events
- Upvote and downvote posts
- Analytics for administration

We used an Azure instance with a LAMP stack to deploy the web application. Just to make things more interesting, I used a dynamic DNS (DuckDNS) so that I could have a unique URL on the internet. The architecture is shown here:

![Architecture Diagram](/assets/images/pennconnect_2.png)

Here are a few screenshots:

Login Page:
![Login Page](/assets/images/pennconnect_1.png)

News Feed:
![News Feed](/assets/images/pennconnect_3.png)

Analytics Page:
![Analytics Page](/assets/images/pennconnect_4.png)
