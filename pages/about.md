---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## 1st Psychiana Collection 
This is the first part of Psychiana Collection.
{% include feature/item-figure.html objectid="psychiana026" width="50" %}

## 2nd Psychiana Collection
This is the second part of Psychian Collection

{% include feature/card.html header="This is a Psychiana Collection Card" text="The card features an image from the Psychiana Collection as a cap" objectid="demo004" width="25" centered=true %}

## About the Collection

This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

The base site features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include feature/abouttheabout.md %} 
