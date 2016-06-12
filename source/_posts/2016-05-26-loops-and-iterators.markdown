---
layout: post
title: "Loops"
date: 2016-05-26 13:19:23 +0300
comments: true
categories: 
---

There are three operator for loops. These are `while`, `for` and `until`.
These operators looping until they being false. And also they save you put you to a bother.
For example you want to print 1 to 100.
```ruby
i = 1
while i != 100
  puts i
  i = i + 1
end

# or

i = 1
unless i == 100     #You had to be careful at here only '=' equal something to another thing 
  puts i            # but '==' is controlling is they equal or not
  i = i + 1
end

# or


```

