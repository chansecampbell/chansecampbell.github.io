---
layout: default
title: Programming Basics with Ruby
---
<h1 class="header-name">{{ page.title }}</h1>
<h3 class="header-name">Written by Chanse Campbell on {{ page.date | date: '%B %d, %Y' }}</h3>

So I'm currently working my way through General Assembly's pre-work that was recently updated and resent out to me to try and tackle. I have to say that I'm enjoying tackling the challenges set to me in terms of creating simple programmes in Ruby, but it's took me a little while to work through 'bugs' on more than one occasion. For example, doing the classic 'Fizzbuzz' programming challenge, I couldn't figure out for a small while how to make the 'Fizzbuzz' string pop up instead of 'Fizz' and 'Buzz' on a word that was both a multiple of 3 &amp; 5. In the end I managed to get it working with the following code.

<code>if counter % 3 == 0 &amp;&amp; counter % 5 == 0
puts("FizzBuzz")
counter = counter + 1

elsif counter % 3 == 0
puts("Fizz")
counter = counter + 1

elsif counter % 5 == 0
puts ("Buzz")
counter = counter + 1

else
puts (counter)
counter = counter + 1
end</code>

In the end I found that I was trying to enclose the counter % 3 &amp;&amp; 5 in brackets and that it actually needed to be linked and separately connected to the counter variable in order to run. I have to say, it felt great to crack some of these code challenges (with a little help from the good old WWW) but I hope that it's normal to hit some speed bumps as a ruby newbie (haha!).

I've also been working on testing out my existing front-end knowledge by putting together a responsive portfolio page that scales between a mobile, tablet and desktop design. At the minute I've been playing with CSS stylings and font choices but I'm going to look at improving this and potentially adding some Ruby or Javascript before the start of my course next month. Here's a snippet of my very basic mobile version.

<a href="https://thelongcodeahead.files.wordpress.com/2015/01/portfolio-upcoming.png"><img class="alignnone size-medium wp-image-52" src="https://thelongcodeahead.files.wordpress.com/2015/01/portfolio-upcoming.png?w=300" alt="Portfolio Upcoming" width="300" height="289" /></a>

My thinking right now is that I'll add an interactive drop down nav menu amongst other things, but I'd like to keep the page potentially clean and simplistic in design. If anyone has any suggestions or tips for improvement they would be extremely welcome!