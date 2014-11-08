Web_Blog_Application
====================

This is a simple web blog application built on Ruby on Rails framework.

There are two types of users: the blog administrator and the blog users.

The blog administrator can enter new postings and comments (typically in reverse 
chronological order), and modify any posting or comment. When a post is removed,
all the comments associated are deleted as well. 

Users can visit the blog site and enter comments on particular postings, but 
cannot modify postings or other users' comments.

This web blog application is built based on the Client-Server architecture, the 
Model-View-Controller model, and the Active Record Dsign Pattern.

Persistent blog data and post/comment association is stored in SQLite Database
using the Object-Relational Mapping (ORM).

User input data is validated on client-side (JavaScript, HTML5) and server-side
(Model-level, DB stored procedures) to avoid attacks such as SQL injection,
buffer overflow, cross-site scripting, etc.


Copyright (c) 2014 Kimi Zhong.
Released under the MIT license. See LICENSE for details.
