---
layout: single
title: "Different layers in a Software" # title shown in home page
excerpt: "The simplest form of layered architecture in the IT world is a three-tiered architecture. All layered software..."
permalink: # global permalink is set in_config.yml
tags:
  - software
  - software layers
  - application tiers
published: true
comments: true
author_profile: true
header:
  teaser: /assets/images/layer.jpg
  image:  
#header:
#	teaserlogo:
#  	teaser: "/assets/images/mm-responsive-feature.png"
# 	image: 	"/assets/images/mm-home-page-feature.jpg"
#  	caption:
gallery:
  - image_path: ''
    url: ''
    title: ''
---

The simplest form of layered architecture in the IT world is a three-tiered architecture. All layered software architecture contains these layers -

**Presentation layer:** This is the first layer, which presents content to the end-user through a graphical user interface (GUI) such as a mobile application or a web browser. This layer interacts with the application layer and hosts mainly the static files such as HTML pages, CSS files, and images. 

**Application layer:** This is the middle layer of the architecture. The business logic of the application is provided by this layer and it hosts the core application code written by application developers. This layer receives the requests from the presentation layer and talks to the database layer if needed to serve the requests.

**Database layer:** This is the lowest layer of the architecture. Application data is stored in this layer and accessed using the application layer.


![appLayers](/assets/images/layers.jpg)

A multi-layered architecture, which is an advanced form of 3 layered architecture is getting more popular these days where the application layer is expanded into multiple layers.

Source: [Packthub](https://hub.packtpub.com/what-is-multi-layered-software-architecture/#:~:text=Sometimes%20called%20tiered%20architecture%2C%20or,to%20tackle%20the%20entire%20architecture.)
