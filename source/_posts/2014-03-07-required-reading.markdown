---
layout: post
title: "Required Reading"
date: 2014-03-07 13:01:28 -0500
comments: true
categories: reading Ruby
---
Today I started reading [*The Passionate Programmer*](http://www.amazon.com/The-Passionate-Programmer-Remarkable-Development/dp/1934356344) by Chad Fowler. I'm only a few chapters in after the train rides to and from work, but I can already say that this is a book I should have read years ago. The comparisons he draws between his career as a jazz musician and a software developer certainly hit home.

My favortie advice in the book so far comes from chapter 4 in which the author quotes jazz guitarist Pat Metheny, "Always be the worst guy in every band you're in." This is really just a clever way to say, always keep company with those who may make you better. His point is that if you're continuously pushing yourself outside your comfort zone and surrounding yourself with people who are better than you are at a certain skill, you will almost automatically get better. I have found this to be true in my own life experiences.

I also picked up [*Practical Object-Oriented Design in Ruby*](http://www.amazon.com/Practical-Object-Oriented-Design-Ruby-Addison-Wesley/dp/0321721330) by Sandi Metz, but I probably won't get to start that until at least next week. For now, I'll stick to the first book and do some online exercises in Git and Ruby.

## Codecademy

As part of a requirement that I've placed on myself for this journey to push code to GitHub every day, here is one of the early Ruby tutorials I've completed on [Codecademy](http://codecademy.com). Variables with user input. Fancy-shmancy, indeed.

```ruby names.rb
# Get user's first name
print "What's your first name? "
first_name = gets.chomp
first_name.capitalize!

# Get user's last name
print "What's your last name? "
last_name = gets.chomp
last_name.capitalize!

# Get user's city
print "From which city do you hail? "
city_name = gets.chomp
city_name.capitalize!

# Get user's state
print "From which state do you hail? "
state_name = gets.chomp
state_name.upcase!

# Display results
puts "Your name is #{first_name} #{last_name}, and you're from #{city_name}, #{state_name}!"
```