---
title: home of Ext004
---

# I am site Ext004

v-010

### dump THOSE in myPost WHERE myBool: true
{% assign myPost = site.posts | where: "myBool", true %}
{{ myPost }}

### dump ALL as myPost
{% assign myPost = site.posts %}
{{ myPost }}

### dump posts
{{ site.posts }}


###### EoF
