---
layout: post
title:  "Starting a django project in an already created directory"
date:   2015-02-26 00:28:53
categories: python notes
---

When you want to start a new Django project in a directory that already exists, you can specify that in the `startproject` command! (make sure you are inside that directory)

`django-admin.py startproject myproject .`

The dot tells Django to use the folder you're already in, instead of making a new one.

Source:

* [Getting Started with Django on Heroku](https://devcenter.heroku.com/articles/getting-started-with-django)
* [Effective Django - Getting Started](http://effectivedjango.com/tutorial/getting-started.html#installing-requirements)
