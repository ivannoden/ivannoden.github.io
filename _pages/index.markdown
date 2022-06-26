---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: Home
layout: default
---

# Hello 

I'm Ivan Noden and, as you may guess, this is my website. I'm not quite sure why you'd be here as there's nothing to see at the moment but feel free to enjoy it anyway.

This site was created to facilitate my entry into [3Blue1Brown's 'Summer of Math Exposition'](https://www.youtube.com/watch?v=hZuYICAEN9Y) which I may or may not complete.

### Recent blog posts:
{% for post in site.posts %}
* [{{post.title}}]({{post.url}})
{% endfor %}