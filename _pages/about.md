---
permalink: /
title: "Security is full of hidden features"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

In an attempt to start contributing back to the security community, I am starting a new blog series about Red Teaming for and with Macs. Macs seem to be more and more popular, but most red teaming blogs are exclusively Windows based. In conjunction with these blog posts, I will be releasing tools to help with red teamers on Macs. 

Blog Series
-----
Series #1:  
[Active Directory Discovery](https://its-a-feature.github.io/posts/2018/01/Active-Directory-Discovery-with-a-Mac/)
: Basics of Active Directory discovery with JXA, command-line tools, and wrapped in [Orchard](https://github.com/its-a-feature/Orchard)

Active Directory Discovery - Now with more Objective
: Delving deeper into Objective C bridge in JXA to query Active Directory via APIs

Series #2:  
[Creating an Apfell - Part 1](https://its-a-feature.github.io/posts/2018/02/Creating-an-Apfell-Part-1/) - Sanic
: Creating a basic RESTful, asynchronous, python web server  

[Creating an Apfell - Part 2](https://its-a-feature.github.io/posts/2018/02/Creating-an-Apfell-Part-2/) - peewee, peewee-async
: Connecting to a Postgres database, ORMs, and event loops  

[Creating an Apfell - Part 3](https://its-a-feature.github.io/posts/2018/02/Creating-an-Apfell-Part-3/) - Jinja2, Twitter Bootstrap
: User interface HTML templeting with Jinja2 and new UI elements with twitter bootstrap  

[Creating an Apfell - Part 4](https://its-a-feature.github.io/posts/2018/03/Creating-an-Apfell-Part-4/) - LISTEN/NOTIFY, Websockets
: Asynchronous notifications from Postgres database, websockets (both in Sanic and JavaScript)  

[Creating an Apfell - Part 5](https://its-a-feature.github.io/posts/2018/03/Creating-an-Apfell-Part-5/) - Vue
: Dynamic real-time page updates with Vue  

[Creating an Apfell - Part 6](https://its-a-feature.github.io/posts/2018/04/Creating-an-Apfell-Part-6/) - Sanic-auth, Sanic-wtf  
: User authentication with sanic-auth, and form submissions with sanic-wtf  

[Bare-Bones Apfell server code release](https://its-a-feature.github.io/posts/2018/07/bare-bones-apfell-server-code-release/)  
: Initial release of a bare-bones server incorporating all of the above elements for expansion

Current frameworks: the upsides, the downsides, and my ideal  
: A brief walkthrough of common red teaming frameworks and why I decided to learn how to create my own

Series #3:  
Creating a RAT - Part 1 - What is basic functionality  
: A walkthrough of the first release of apfell-jxa to discuss what is required for a basic RAT

Creating a RAT - Part 2 - Upping the game, securing your comms  
: Adding encryption, authentication, and detection checks to your basic RAT

Creating a RAT - Part 3 - Updating configurations  
: How to update configurations on the fly, including swapping out C2 mechanisms and loading code in JXA

Tooling
-----
  - [Orchard](https://github.com/its-a-feature/Orchard) - A JavaScript for Automation (JXA) Active Directory enumeration tool.
  - [Apfell](https://github.com/its-a-feature/Apfell) - A macOS, post-exploit framework for red teaming  
    - [apfell-jxa](https://github.com/its-a-feature/apfell-jxa) - A JXA implant for use with the Apfell framework.

For the Network is Dark and Full of Terrors
======
This is just a blog for personal coding projects, blog posts, and other interesting things that relate to red teaming, pen testing, CTFs, etc. By hosting it here, I can easily reference other github repositories and gists.
