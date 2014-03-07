---
layout: post
title: "Day 2: Installed Octopress"
date: 2014-03-06 22:11:14 -0500
comments: true
categories: updates Octopress Ruby
---
Today was a day of great progress. After reading up on the benefits of Octopress, I decided to delete my Jekyll repository and start from scratch with a clone of <a href="https://github.com/imathis/octopress">Octopress</a>. Since you are reading this, it means my installation was successful and I can now track my daily efforts towards denoobification. I admit that just the install turned out to be an excellent learning experience because the process didn't go as smoothly as the Octopress documentation lead me to believe it would. 

### Not So Fast

The first problem I noticed was that I was only running Ruby 1.8.7 since it is the default version in OS X Mountain Lion which is what I'm running on this iMac. The Octopress documentation recommends to upgrade to Ruby 1.9.3 via `rbenv`. For reasons outlined in [this article](http://blog.zerosharp.com/installing-ruby-with-homebrew-and-rbenv-on-mac-os-x-mountain-lion/), I was unable to do so before installing GCC. After that crucial step I was back on track via the documentation to upgrade Ruby, install Octopress, deploy to GitHub Pages, and get to blogging!

### Portability Problem

Another issue I ran into was the fact that I did my initial push from my iMac but would be doing most of my blogging from my laptop. This didn't hold me up for long thanks to another article on 
[zerosharp](http://blog.zerosharp.com/clone-your-octopress-to-blog-from-two-places/).

### Learning The Lingo, Making it Mine

Now that everything is up and running, the next step was to learn the lay of the land. The first thing I noticed is that Octopress blog posts use [Markdown](http://daringfireball.net/projects/markdown), which is something I have no prior experience with. After poking around for a few minutes, I managed to learn enough syntax to write this post (and go back and fix yesterday's post). I really like the ability to add `code` tags so easily.

I had a few hours when I got home tonight to get a feel for how Octopress is structured and managed to make some changes to `_layout.scss` and `_typography.scss` and added my logo to the header and favicon. Overall, I'm very pleased with tonight's results. Here are before and after shots.

<img src="{{ root_url }}/images/before.png" style="height: 45%; width: 45%;" /> <img src="{{ root_url }}/images/after.png" style="height: 45%; width: 45%; float: right;" />