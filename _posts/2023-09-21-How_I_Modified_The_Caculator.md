---
toc: true
comments: true
layout: post
title: Modifications to the caculator
description: How I modified the caculator
type: plans
courses: {compsci: {week: 4} }
---

# **How I Modified the Caulator**
The first thing I did to modifiy my caculator was adding a divide and exponet button.

The way I added the divide symbol was like this:
```
<div class="calculator-operation">/</div>
```
This adds the division symbol. Next i had to tell it what it does. 
```
case "/":
              result = first / second;
              break;
```

Next I had to add exponets.
```
<div class="calculator-operation">^</div>
```

Then I had to tell it what it does by doing this:
```
case "^":
              result = Math.pow(first,second)
              break;
```
