---
title: home of Ext004
---

# I am site Ext004

v-004

### dump just the 1 post
{{ posts./2001/01/01/nn001 }}

### dump just the 1 page
{{ page./2001/01/01/nn001 }}

### get post /2001/01/01/nn001
---
{% assign myPost = site.posts | where: page.id == "/2001/01/01/nn001" %}
{{ myPost }}
---

### dump posts
{{ site.posts }}


###### EoF
