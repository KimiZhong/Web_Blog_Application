Web_Blog_Application
====================

This is a simple web blog application built on Ruby on Rails framework.

There are two types of users: the blog administrator and the blog users.

The blog administrator can enter new posts and comments (typically in reverse 
chronological order).

Users can visit the blog site and enter comments on particular posts.

Only the administrator with proper username and password can modify the posts. 
When a post is removed, all the comments associated are deleted as well. 

This web blog application is built based on the Client-Server architecture, the 
Model-View-Controller model, and the Active Record Dsign Pattern.

Persistent blog data and post/comment association is stored in SQLite Database
using the Object-Relational Mapping (ORM).

User input data is validated on client-side (JavaScript, HTML5) and server-side
(Model-level, DB stored procedures) to avoid attacks such as SQL injection,
buffer overflow, cross-site scripting, etc.


Copyright (c) 2014 Kimi Zhong. MOOC Web Application Architectures.
Released under the MIT license. See LICENSE for details.
