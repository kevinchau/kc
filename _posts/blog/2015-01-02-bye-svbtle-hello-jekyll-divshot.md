---
layout: post
title:  "Goodbye Svbtle, Hello Jekyll + Divshot"
categories: blog
---

2015 marks a new year - time to start fresh. In the last few months of 2014, I've been working on my new website that allows me infinite customization. I can showcase photography, blog freely, and tweak the styling to my liking. There was one thing I knew since last summer - I needed to leave Svbtle.

### Leaving Svbtle

I needed to search for greener pastures. Svbtle is great without a doubt. But it's very limting creatively. They've done a great job with readability and ease of use, but there were a ton of things that bothered me. I've lost work countless times because they don't autosave, pictures aren't always displayed well, and I couldn't have a commenting system or my own mailing list.

It's a limiting platform that's only slightly better than Medium - which I deeply dislike.

### Why Jekyll & Divshot

Naturally - I work at [Divshot](https://divshot.com), so it was wise for me to dogfood. Not to mention I don't have to pay for the awesome services that we make (humble brag). But the key features that I'm using Divshot and not Wordpress/Ghost is because I wanted a CDN, and a staging environment.

However, the most important thing was having the ability to easily set redirects. I wanted my old links 301'd to the new site and it was really easy doing that using [Superstatic](http://superstatic.org), which is what Divshot is built on.

I spent the last few months designing and coding this site off and on in my free time. It uses Bootstrap with very minimal JQuery. It's fast, responsive, and most importantly - we already use Jekyll at Divshot. It was something I could expand my knowledge on and practice web design in my free time.

![Screenshot](../images/blog/site.png)

I kept everything minimal and as sleek as possible. It's a landing page for myself.

### What's Coming?

Well, now that everything is custom, over the next few months there's going to be additions:

* Mailchimp newsletter signup
* Static contact form
* More sophisticated photo gallery
* Improved styling
* Finally finishing my About page

### Infrastructure

I'm using Divshot CDN, Cloudfront DNS, and all on HTTPS - which would take you 3x longer to develop on Wordpress. I guarantee it.
