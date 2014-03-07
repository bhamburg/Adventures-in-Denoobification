---
layout: post
title: "Day 1: Commence Denoobification"
date: 2014-03-05 21:07:14 -0500
comments: true
categories: updates GitHub Jekyll Ruby
---
I've always been a dabbler. I used to dabble in DOS and Windows configuration and eventually did it long enough to get my first real job doing technical support. I dabbled in banjo enough to make it to the front line of the [Fralinger String Band](http://fralinger.org) and make a pretty steady side gig out of it. I dabbled in HTML, CSS, and JavaScript enough to make a career as a front-end web developer. Since then, I've dabbled in C++, Java, PHP, Python, and C# (the latter just enough to gain my [Sitecore developer certification](http://brianhamburg.com/resume/) even though I much prefer working on my [open-source projects](http://github.com/bhamburg)). With all of that dabbling, I've become very much an IT generalist (that happens to play banjo). A jackass of all trades, if you will. This has taken me pretty far in life, but even more importantly it's shown me how much I don't know and should know to take my career to the next level, namely a strong understanding of programming in the real world.

### Become a `Ruby` Developer

Just from conversations with my colleages and reading articles on the web, I started to gain an interest in taking my career further in open-source development. I've heard of Ruby on Rails and knew it was the latest hot trend in webdev, but I couldn't tell you much about it other than the seemingly well-paid pros were cool characters who shared a lot on GitHub. Then, in my daily Internet stumblings, I happened to read this page: [Become a Ruby Developer](http://rubycon.rkcudjoe.com/become-a-ruby-developer/)

I really like what Raymond Cudjoe has put together here and, based on the book reviews and other articles I read, his advice seems to be solid. I've decided to dive into this guide and become a Ruby developer. My inner geek is calling me to get serious. **Consider this ~~Jekyll~~ Octopress blog his *Retrospection #1* assignment.** I plan to read *The Passionate Programmer* over the next week or so. I'm looking forward reporting my progress here, keeping track of everything that I have learned along the way.

### GitHub

Prior to 2012, my only exposure to version control had been Dreamweaver's check-in feature. Once I started working at Jefferson Hospital, I was introduced to Subversion using a GUI without much command line interaction. My cursory knowledge of such an important aspect of a front- or back-end developer's world needs to change. I'm going to make a concerted effort to become a Git expert and contribute to GitHub regularly as I learn Ruby and continue to work on my other projects. I've found a good starting point in this effort to be [Git Immersion](http://gitimmersion.com/). Check out my very first Ruby program and contribution to GitHub below. It's official, folks.

## The Obligatory `hello.rb`

```ruby
# Default is "World"
name = ARGV.first || "World"
puts "Hello, #{name}!"
```