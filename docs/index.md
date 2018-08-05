---
title: home of Ext004
---

# I am site Ext004

v-011

### dump THOSE in myPost WHERE title: "nn001"
{% assign myPost = site.posts | where: "title", "nn001" %}
{{ myPost }}


### dump THOSE in myPost WHERE myBool: true
{% assign myPost = site.posts | where: "myBool", true %}
{{ myPost }}

### dump ALL as myPost
{% assign myPost = site.posts %}
{{ myPost }}

### dump posts
{{ site.posts }}


###### EoF
