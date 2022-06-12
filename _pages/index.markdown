---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /

layout: home
---

# Hello {#greeting}

Visit: 
* [About](/about/)

Blog posts
{% for post in site.posts %}
* [{{post.title}}]({{post.url}})
{% endfor %}