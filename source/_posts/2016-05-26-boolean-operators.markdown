---
layout: post
title: "Boolean Operators"
date: 2016-05-26 12:55:03 +0300
comments: true
categories: 
---

Comparators aren't the only operators available to you in Ruby. You can also use logical or boolean operators. 
Ruby has three: and (&&), or (||), and not (!). Boolean operators result in boolean values: true or false.
The boolean operator and, &&, only results in true when both expression on either side of && are true.Ruby also has 
the or operator (||). Ruby's || is called an inclusive or because it evaluates to true when one or the other or both 
expressions are true.And the last one, Ruby has the boolean operator not (!). ! makes true values false, false values true.
Here's how these works.

And operator
```
true && true # => true
true && false # => false
false && true # => false
false && false # => false
```
<br />
Or operator
```
true || true # => true
true || false # => true
false || true # => true
false || false # => false

```

Not operator
```
!true # => false
!false # => true
```