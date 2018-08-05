---
title: home of Ext004
---

# I am site Ext004

v-003

### dump just the 1
{{ posts./2001/01/01/nn001 }}

### get post /2001/01/01/nn001
---
{% assign myPost = site.posts | where: "id" == "/2001/01/01/nn001" %}
{{ myPost }}
---

### dump posts
{{ site.posts }}


###### EoF
