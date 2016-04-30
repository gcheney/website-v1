---
layout: post
title: Hello World
description: 
modified: 2016-04-30
comments: true
tags: [sample post, code, highlighting]
image:
  feature: helloworld-toast.jpg
  credit: Windell Oskay
  creditlink: https://www.flickr.com/photos/oskay/
---

Hello world and welcome to my very first post! As a long time Wordpress user this is my first step into the world of the simple, blog-aware, static site generator known as [Jekyll](https://jekyllrb.com/), and what better way to start this blog off than with the traditional "Hello World" post! 

I will take it one step further though and make this "Hello World" post *about* the famous first programming example so many books and tutorials have used over the years. Ever since it first appeared in the [The C Programming Language](https://en.wikipedia.org/wiki/The_C_Programming_Language), the "Hello world" example has been the go to introduction to a new programming langauge for most software developers. In honor of that, I will present "Hello World" `foreach` of the current [Tiobe Index](http://www.tiobe.com/tiobe_index) top ten programming langauges as of April 2016. This will be a great way to learn a bit of what makes each of these langauges unique in both their syntax and their design philosophy (plus it will let me test out the code highlighting styles). Lets get started! 

### 1. Java

{% highlight java %}
/******************************************************************************
 *  Compilation:  javac HelloWorld.java
 *  Execution:    java HelloWorld
 *
 *  Prints "Hello, World". By tradition, this is everyone's first program.
 *
 *  % java HelloWorld
 *  Hello, World
 *
 *  These 17 lines of text are comments. They are not part of the program;
 *  they serve to remind us about its properties. The first two lines tell
 *  us what to type to compile and test the program. The next line describes
 *  the purpose of the program. The next few lines give a sample execution
 *  of the program and the resulting output. We will always include such 
 *  lines in our programs and encourage you to do the same.
 *
 ******************************************************************************/
 
public class HelloWorld {

    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
{% endhighlight %}

### 2. C

{% highlight c %}
#include <stdio.h>
// hello.c
int main()
{
  printf("Hello world\n");
  return 0;
}
{% endhighlight %}

### 3. C++
{% highlight c++ %}
//hello.cpp
#include <iostream>

int main()
{
  std::cout << "Hello World!";
  return 0;
}
{% endhighlight %}


### 4. C\#

{% highlight c# %}
// hello.cs
public class HelloWorld
{
   public static void Main()
   {
      System.Console.WriteLine("Hello, World!");
   }
}

{% endhighlight %}


### 5. Python

{% highlight python %}
# hello.py
print "Hello World!"
{% endhighlight %}

### 6. PHP

{% highlight php %}
 <?php 
    //hello.php
    echo 'Hello World'; 
 ?> 
{% endhighlight %}

### 7. Javascript

{% highlight javascript %}
// hello.js
console.log("Hello world!");
{% endhighlight %}

### 8. Perl

{% highlight perl %}
#!/usr/bin/perl
print "Hello World!\n";

{% endhighlight %}

### 9. Ruby

{% highlight ruby %}
# hello.rb
puts 'Hello world!'

{% endhighlight %}

### 10. Visual Basic

{% highlight html %}
{% raw %}
' hello.vb 
Module HelloWorld
  Sub Main()
      Console.WriteLine("Hello World!")
  End Sub 
End Module
{% endraw %}
{% endhighlight %}