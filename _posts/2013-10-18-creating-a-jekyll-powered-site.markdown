---
title: Creating a Jekyll Powered Site
layout: post
author: Rami James
year: 2013
month: October
---

#Using the right tools for the job is what it is all about. For us, Jekyll is the right tool.

It's been a long time coming and it was well worth the effort. We hope that you all will find here a new and interesting source for design and development processes, insights, and tools.

The new site is built on a technology platform based on Ruby called Jekyll. It is a system which runs either locally or on a server (we use Heroku) and can be run for free on Github Pages as long as you don't mind running without any of the fancy plugins available.

We are using a plugin to generate the portfolio page and manage the projects inside, so Heroku was our best bet.

<img src="{{ site.baseurl }}images/jekyll.jpg" class="blogimage">

## Moving from Wordpress to Jekyll

I've used Wordpress to develop every site that I've created over the past six or seven years. It is a brilliant CMS and there is good reason for the fact that it powers 22% of the world's website. That's huge!

The simple fact of the matter is that Wordpress is a brilliant CMS, but that it is also a monster to run and a hassle to keep up to date. Many security breaches are due to a host's inability to secure their server, security flaws in the setup, or in Wordpress or its plugins.

Jekyll is a beautiful alternative which offers most of the templating flexibility of a complex CMS, with none of the drawbacks of a dynamic site. Static files are relatively secure and are blazing fast -- and this is really the core brilliance of Jekyll. You get all the advantages of a full templating system such as includes, metadata, and auto-generated pages -- with none of the overhead of running a database or setting up Wordpress.

## Some of the technical details of our setup

Putting together a site like this was done with the help of two really great projects and a bit of hackery on our end.

First, we used Jonas Forsberg's <a href="http://jonasforsberg.se/2012/07/22/jekyll-heroku-unicorn">Jekyll+Heroku+Unicorn setup</a> as a base. I tried a few other projects which either did not run on heroku or did not fit the needs of my company's site. It let me quickly get a base setup going which we could hack away on.

Secondly, we used the <a href="http://getskeleton.com/">awesome grid system Skeleton</a> for building the site's look and feel. Skeleton has a few really nice advantages over a full-on theme like Boostrap. It generally gets out of your way when it should, something which designers appreciate, and that it is minimalistic so that you add functionality you want instead of ripping out functionality you don't need. Designers tend to be finicky about how they work and it is nice to find a system which plays nice.

## Time to talk about some limitations in the system

Like all things, working with Jekyll has its limitations. Since it outputs static files, there is no ability for dynamic content like comments and email forms to be submitted to a server and processed. This means things like a simple contact form need to use alternate solutions. Ours was to use Wufoo to process forms using local javascript files. It works well and we recommend it. For comments, Disqus is always an option.

Sitemaps are also not built in. There are a few solutions out there for generating a sitemap.xml file. In the end we decided it wasn't a critical feature, but it is something which we believe we will add in the future to our set up.

## The overall result

We are very happy with how the site works, how easy it is to update -- just a git push, no messy FTP transfers and you always have a commit history! The learning curve wasn't too daunting and we get to use our favorite development language, Ruby, to do our in-house website. 

If you haven't considered Jekyll for your company's website needs, you should. The advantages of stability, speed, and easy updates far outweigh the disadvantages I outline above.