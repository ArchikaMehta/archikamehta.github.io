---
layout: single
title: "System, System integration and end to end testing" # title shown in home page
excerpt: "It would be very easy if we take an example to  understand the difference between System, System integration and End to end testing..."
permalink: # global permalink is set in_config.yml
tags:
  - system
  - system integration
  - End to end
published: true
comments: true
author_profile: true
header:
  teaser: "/assets/images/systemtesting.png"
  image:  
#header:
#	teaserlogo:
# 	teaser: "/assets/images/systemtesting.png"
# 	image: 	"/assets/images/mm-home-page-feature.jpg"
#  	caption:
gallery:
  - image_path: ''
    url: ''
    title: ''
---

It would be very easy if we take an example to  understand the difference between System, System integration and End to end testing.

For example, we will assume the process of ordering any product from Amazon portal. If we talk about Amazon it is not a single application, which is dealing with our order process. Amazon has tied up with various other portals to make their work easier and cheaper. Like Amazon don't have its own payment gateway so it can't allow you to pay to it directly and it won't be feasible for it to make it's own gateway while these services are already available in the market, so Amazon would prefer to directly deal with those services rather than creating its own.

In our context, if we are willing to order something from Amazon first we would need to create an account to its portal, then search the product, then add it to the cart for buying, then making payment and finally after making the payment we will receive an order confirmation email and payment receipt, this is the whole process of online shopping. 

So now in our testing context if we will test the functionality which is only related to the product search then we will refer it as System testing, when we will test the functionalities from product search to payment then we will call it as System integration testing (as in this process external payment gateway like Google pay is also included with Amazon) and finally if we will teat all the functionalities from the beginning (creating a user account) to end (receive the order confirmation and payment receipt) then we will call it as End to end testing.
![SystemTesting](/assets/images/systemtesting.png)


