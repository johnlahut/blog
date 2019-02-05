---
layout: post
title:  "My Django Mess"
date:   2019-01-26
categories: general
permalink: /:year/first-post/
---

A lot of my past and current projects at my company revolve around migrating old VBA Excel macros (whose only job is to validate data) to more dynamic solutions. I have achieved this by using Python and a combination of great libraries, particularly `openpyxl`, `xlwings`, and `cx_oracle`.

I am now working on taking these weird Python-Excel hybrid beasts and migrating everything to a web-based solution. Since all of my code is already written in Python, I am using [Django][2] to support this.

The [Django][2] migration project has been a hard one. 

This is my first "programming" job (I say this in quotes because I am not on a software team, nor is development work in my job description) and I am building an entire system from the ground up. I have no experience in web development or database design, let alone the specifics of the [Django][2] framework.

So I bought [Two Scoops of Django][1], and got to reading. 🍨

Within 6 months, I was able to get a server up and running with a site deployed that was able to connect to our databases and produce reports. 

Looking back, that was the easy part.

I am now lost in trying to figure out how to handle this project as it scales. I have no staging/production paradigm (I know, insane. I barely knew what staging was when I started this project). 🤦‍♂

I have no idea how to gracefully handle reports that take over five minutes to produce, just due to the shear amount of data. Right now the page just hangs while the user waits for the download. 🤦‍♂

I have a ton of duplicated code. All over the place. I mean everywhere. In models, views, templates, forms, you name it. 🤦‍♂

Management wants others on the team to contribute so if I get laid off/quit/fired someone will know how it works. As you might have guessed, I have abolutely zero infrastructure in place to support multiple developers working on this project. 🤦‍♂

Besides all that, I still feel like I am grasping at straws when using [Django][2] and the front-end languages like JavaScript, HTML, and CSS. Hell, I thought JQuery and JavaScript were different languages, and I thought an "AJAX" was a wild animal. 🤦‍♂

The thing is, it works great right now from the user's perspective. Reports that use to take 6+ hours to produce (not a hyperbole) now take under 5 minutes. It is hard to justify cleaning the code up to colleagues when new tools and further migration seems obvious to them.

I've got a lot of problems piling up that seem hard to solve, which inspired me to write this post. 

I want to do my best to make sure my learning will be communicated to others. There has to be other people out there that can benefit from learning how to migrate Excel templates into fully integrated web-based solutions in Python. 

So that's where we're at, see you soon.




[1]: https://www.twoscoopspress.com/products/two-scoops-of-django-1-11
[2]: https://djangoproject.com
