---
layout: post
title: "Day 6: Don't Listen To Your Parents"
date: 2014-03-10 21:52:30 -0400
comments: true
categories: reading Ruby practice
---
Today was a travel day. Andrea has nurse practitioner conference all week in Boston so I took the opportunity to use some vacation time to accompany her and hang out in Beantown. Since I was away from an internet connection, I stayed productive by catching up on my reading and creating a Ruby program from scratch.

I'm about halfway through [*The Passionate Programmer*](http://www.amazon.com/The-Passionate-Programmer-Remarkable-Development/dp/1934356344) and I'm finding a ton of insight that I can relate to in this book. One chapter that really stood out was 6: "Don't Listen To Your Parents." It's not as disrespectful as it sounds, and by no means is the author (or am I) trying to undermine the authority of parents of potential IT students everywhere. The main point he's trying to make is that the days of taking the safe and secure career path and staying at one job until retirement are over, especially for IT professionals. The following thoughts really hit home, especially regarding some recent conversations.

> More than any other third party you might look to, your parents are going to give you fear-driven advice. Fear-driven advice is geared toward *not losing*. Thinking about not losing is *not* the way to win! Winners take risks. They think about where they want to go--not where the rest of the pack is.

The author goes on to explain this isn't just a rah-rah speech for individuals to follow their pie-in-the-sky dreams. There are logical, pragmatic reasons for a software developer to seek out a variety of experiences that can only come from having developed in multiple environments and having solved a variety of problems. In fact, he calls having only worked at one company a liability and a possible strike against a job candidate. Also, he aruges that truly enjoying one's work is the only way to become excellent and have a remarkable career.

Hear, hear.

## Ruby Practice: `99bottles.rb`

In an attempt to synthesize some of the concepts I've learned from [Ruby Bits](http://rubybits.codeschool.com/), I created a program that uses inline `if` and `unless` statements to minimize the amount of code necessary to set default values and get the grammar correct for the lyrics to "N Bottle(s) Of Beer On The Wall."

```ruby 99bottles.rb
# Get user's favorite beer
print "What is your favorite beer? (default is Sam Adams)\n"
beer = gets.chomp.split.map(&:capitalize).join(' ')
beer = "Sam Adams" if beer == ""

# Get user's number of bottles
print "How many bottles of #{beer} do you have? (default is 99)\n"
n = gets.to_i
n = 99 if n == 0

# Print lyrics
while n > 0
    s = "s" unless n == 1
    puts "#{n} bottle#{s} of #{beer} on the wall.\n#{n} bottle#{s} of #{beer}.\nTake one down, pass it around."
    n -= 1
    s = "" if n == 1
    puts "#{n} bottle#{s} of #{beer} on the wall.\n\n"
end
```