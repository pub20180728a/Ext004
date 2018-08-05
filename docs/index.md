---
title: home of Ext004
---

# I am site Ext004

v-012

### dump THOSE in myPost WHERE page.id "/2001/01/01/nn001"
{% assign myPost = site.posts | where: "id", "/2001/01/01/nn001" %}
{{ myPost }}

### dump THOSE in myPost WHERE title: "nn002"
{% assign myPost = site.posts | where: "title", "nn002" %}
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
