---
layout: post
title: "Get Rolling"
date: 2014-03-18 18:23:12 -0400
comments: true
categories: Ruby Rails framework convention configuration
---
After taking a much needed break from all things constructive to properly celebrate St. Patrick's Day while still in Boston, I'm back on the Ruby train. Since I only had a little bit of time today, I listened to some [free audio lessons about Ruby on Rails](http://www.buildingwebapps.com/transcript/79326-why-you-should-learn-ruby-on), tried to install Rails on my Mac, failed hard, [overcame failure](http://railsapps.github.io/installrubyonrails-mac.html), poked around, and then try to reinforce what I'm doing by reading some blog posts that praise Ruby and Ruby on Rails.

## Installing `Ruby On Rails`

```bash Install Rails
% sudo gem install rails
```

That's all it should take, they said. Developing on Rails is easy, they said. They didn't say how hard it might be to actually complete the install.

Part of my problem was that I was using the version of Ruby that ships with Mac OS X 10.9 Mavericks, which is known to have a security flaw. The recommended way to upgrade is to use [RVM](https://rvm.io/). From there I had to

* get [Homebrew](http://brew.sh/)
* uninstall [MacPorts](http://bitboxer.de/2010/06/03/moving-from-macports-to-homebrew/)
* update .bash_profile PATH to point to `/usr/local/bin:PATH` to stop some error messages
* install Rails
* and finally reinstall [Rake](http://rake.rubyforge.org/) so I could blog about it on Octopress.

Ruby On Rails is now up and running on my MacBook Pro with Mavericks. Now I must figure out what to do with it!

## Convention Over Configuration

In the podcast above, I came across the concept of "Convention Over Configuration" as a main theme in Rails development. Sure, having the ability to customize and do things your own way is nice, and sometimes necessary, but why would you in most cases? Choice paralysis can be costly when time is money. This is a big reason I've returned to the iPhone and Mac for personal productivity after dabbling with Android and Linux for a bit. Kyle Samani wrote a nice article on the concept [here](http://kylesamani.com/blog/convention-configuration) and I originally talked about "the cost of freedom" on my main blog [over here](http://brianhamburg.com/2013/06/the-cost-of-freedom/).