---
title: Responsive is more than just resizing elements
layout: post
author: Rami James
year: 2013
month: October
---

#Not all elements are created equal

##We live in a complex technological world in which we surround ourselves with many types of devices which have different pixel densities, dimensions, and physical sizes. 

##This means that the content we produce, for it to be truly responsive, it needs to both be flexible visually and flexible functionally.

<img src="{{ site.baseurl }}images/responsive.jpg" class="blogimage">

##What this means for forms, buttons, and menus

There is no getting around the fact that fingers are very different pointing devices than a mouse cursor. The sizes and positioning of buttons needs to be more central and larger. The smaller a screen gets, the harder it is to hit a small, clickable area. Larger, less pixel-dense screens like computers and laptops can get away with having a tiny link be clickable for an important functional element (logout, etc.). This does not work on small screens like an iPhone.

<img src="{{ site.baseurl }}images/buttons.jpg" class="blogimage">

Menus must be made simpler and they must fit within the constraints of the screen they are shown on. For simple menus with eight or so elements, which is common in a "brochure" website, it is fine to lay them all out and have a two-click scenario. One click to access the menu, one to select the menu item. What happens when you have a shopping website which has ten top-level items, each having twenty secondary level items and some of those have third-level items? You have to come up with flexible and intuitive solutions which you don't have access to on mobile devices and on tablets. This means that drop-downs are off-limits and certainly child-based drop-downs.

##What this means for layouts

For layouts, the common solution (which is also generally implemented in grid-systems like bootstrap and skeleton, et al) is to have all columns collapse into one column which the user then scrolls through vertically. This is a generally good generic solution, but has a few caveats that I should talk about.

The first is, of course, that not all content is equal. A mobile user has constraints such as slower connections, smaller screens, and most importantly less mental space to filter through "junk" content. When a user comes to a blog, for example, it is very likely that they will read through the single post, but much less likely that they will click on the side articles (which are now at the bottom of the page in a single column site). This means we made them load all that content and functionality for nothing. Things like secondary footers, non-critical side-content, and complex imagery should be hidden from mobile users on phones. Tablets is more of a grey area which needs to be considered carefully for each situation.

##Testing, testing, testing!

The best way to get a feel for responsive design, both for websites and for applications, is to test them on many devices and device-orientations. Tested it on iPhone? Did you test both portrait and landscape mode? iPad? Android? Old laptop computer with 1024x800 screen (it's smaller than a tablet!)?

There are many, many constraints and it really feels like a juggling act sometimes. A very good responsive site isn't just twice the work of a regular site. I would estimate it at least four times! 

I guess that's why they say, practice makes perfect. 

