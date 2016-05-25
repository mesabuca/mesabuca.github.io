---
layout: post
title: "Lots of file"
date: 2016-05-25 23:41:26 +0300
comments: true
categories: 
---

When we are working on small projects, we are writing all codes to one file but if you want to improve yourself you should 
know dividing your code to more than one files. When you begin using multiple files, you have a need for the Ruby's 
require and load methods (both are global functions defined in Object, but are used like language keywords) that help you 
include other files in your program.
<br />
<br />
The load method includes the named Ruby source file every time the method is executed:
<br />
```ruby
    load 'filename.rb'  
```
The more commonly used require method loads any given file only once:
<br />
```ruby    
require 'filename'  
```



