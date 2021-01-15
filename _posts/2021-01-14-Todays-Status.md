---
layout: post
title: "Status January 14, 2021"
date: 2021-01-14 11:08:13 -0400
categories: jekyll github
permalink: status-January-14-2021
---
**Back to Minima**

I had a problem getting the site to build under Garth so I'm back to minima. The repo is techlog and I'm serving it on github. 

I've also reinstalled tiddlywiki and dokuwiki on the terryinfcco.com site. 

And I fixed index.html to reflect all that.

**Another New Jekyll Blog**

I've created a blog using the Garth theme. It's nice and simple and I'm happy with it. I can't get it to work on github, I'm guessing because it's not an officially supported github jekyll theme. But I've uploaded it to terryinfcco.com, pointed the index.html navigation to it, and created a shell script to upload new posts, etc to it. 

To make it work:
* I need to edit or create new content
* I need to run bundle exec jekyll build (to create the _site file)
* I need to run the **uploadtechlog.sh** script from /home/terry/bin
* Once I'm good with it, I need to do the whole **git add .**; **git commit -m "what I did"**; and **git push origin main** so that I've got a backup on github along with the ones scattered around via syncthing.