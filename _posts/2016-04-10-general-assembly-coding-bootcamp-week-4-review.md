---
layout: default
title: General Assembly Coding Bootcamp Week 4 Review
---
<h1 class="header-name">{{ page.title }}</h1>
<h4 class="header-name">Written by Chanse Campbell on {{ page.date | date: '%B %d, %Y' }}</h4>

So I really slacked this week in terms of writing lots of notes for this blog post, but at least I've still managed to write it! Week 4 is officially <strong>done</strong> at GA in London and the pace is as relentless as ever, here's the review from the fastest week yet.

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/running.gif" rel="attachment wp-att-362"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/running.gif?w=300" alt="running" width="300" height="218" class="aligncenter size-medium wp-image-362" /></a>

<h1>Week 4 – Day 16 – Monday</h1>
Today was the day! We officially began <strong>Ruby</strong>, our second official programming language after pretty much 3 weeks of JavaScript. Our first day at it <em>wasn't actually too bad</em>. We spent the day tackling Ruby 101 in the same way we did JavaScript, only we covered about the same amount that took us 3 days in JavaScript 2 weeks earlier. By the end of the day we had covered who created Ruby (Yukihiro Matsumoto aka <strong>'Matz'</strong>, who it turns out is a lovely, lovely guy) and also how to write basic command line programmes with it. By 5pm we had covered <strong>control flows</strong>, <strong>arrays</strong> and <strong>hashes</strong> (the new object of Ruby, because apparently absolutely everything is an object).

Also today we had a special guest instructor for an hour or so (look at the far left of the picture):

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/newteacher.png" rel="attachment wp-att-354"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/newteacher.png?w=227" alt="newteacher" width="227" height="300" class="aligncenter size-medium wp-image-354" /></a>

When it was time for the homework, my confidence came crashing down. The homework was titled the '<strong>MTA map</strong>' and essentially was a New York tube map with 3 lines as seen here:

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/mtamap.png" rel="attachment wp-att-352"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/mtamap.png?w=300" alt="mtamap" width="300" height="223" class="aligncenter size-medium wp-image-352" /></a>

Our task was thus to write a programme using control flows in Ruby to return the number of stops it would take to get from a users start to end position. It sounded fine and many of us quickly figured the trick for getting around the issue of changing lines (and thus directions) but for some reason I got a little bit lost within the syntax and spent longer than I should have getting the code completely wrong. I left a little earlier than usually feeling a bit frustrated with myself, especially as lots of other people seemed to get it working much earlier. I left about 8:30pm.

Mood: <strong>Frustrated</strong>.

<h1>Week 4 – Day 17 – Tuesday</h1>
We tackled the homework in a review and then continued on with our new found relationship with Ruby. I definitely felt a little better after looking at some solutions and reminding myself that it was only day one of a new language, sometimes it's hard to not expect too much of yourself on this course. Today the agenda was then mainly a continuation of Ruby 101 (102?) in which we explored functions, known as <strong>methods</strong> in Ruby. We looked at how they worked slightly differently to what we had come to expect in JavaScript and most of us couldn't help but feel a little confused as we had grown used to the idea of <strong>local</strong> and <strong>global scope</strong>. In Ruby the rules seem to be more along the lines of <strong>public</strong> and <strong>private</strong> methods which is still kind of confusing, but Alex assures us that it makes more sense so I'm confident that it will click soon enough.

My impressions so far of this new language are that <strong>Ruby</strong> is a pretty cool language and the lack of <strong>curly braces</strong> and <strong>semi colons</strong> are honestly a much welcome convention after the <em>bat-shit</em> crazy syntax of <strong>jQuery</strong> (that I was admittedly just about getting used to).

We had a really fun group coding challenge in the afternoon. Our task was to create a game of <strong>Pling, Plang, Plong</strong> in groups of threes (basically a game that spits out the numbers 1-105 but uses the word pling, plang or plong if the number is a multiple of 3, 5, 7 or a combination of two or more. By this point it was a surprisingly easy thing to make and probably took us under 10 minutes to do, but the main purpose of the challenge was to come up with the shortest and cleanest solution we could manage. We ended up putting them into a test on Alex's computer that compared their benchmarking time (essentially how fast they were to run) and we all got way too into it. We ended up coming a very close third but I'm convinced we should have been higher!

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/plingplangplong.png" rel="attachment wp-att-355"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/plingplangplong.png?w=300" alt="plingplangplong" width="300" height="225" class="aligncenter size-medium wp-image-355" /></a>

Our homework for the night was to build a <strong>Blackjack</strong> game, again in the terminal. I was actually really excited to get stuck in as I love Blackjack and it sounded like a cool thing to make. I have to say that in hindsight this was probably one of the most difficult homework's for most people in the class that I can remember, although I found it relatively OK because I took a simple approach and built the entire thing with <strong>control flows</strong> and no methods in the most easy to write way first. I didn't actually get around to putting it into chunked methods (which would have made it easier to read) but I finished by about 9pm feeling pretty happy with myself and my working game (despite a few nightmare issues with the Ace that had a value of both 1 and 11).

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/ruby-blackjack.png" rel="attachment wp-att-357"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/ruby-blackjack.png?w=300" alt="ruby blackjack" width="300" height="199" class="aligncenter size-medium wp-image-357" /></a>

Mood: <strong>Chuffed</strong>.

<h1>Week 4 – Day 18 – Wednesday</h1>
Wednesday we had a massive homework review and spent much of the morning rewriting the Blackjack game again to try and go over the concept of methods in Ruby and how they could be chained in order to create Blackjack. By the end I felt like I could have maybe gone back and made the game in a slightly different way which was good.

We then had a guest speaker come into the room during our <strong>outcomes session</strong>, this week it was Mike Harris who was on the WDI course two years ago. I think the entire class <em>really</em> seemed to enjoy hearing from someone who was once in our shoes and we asked lots of questions. Apparently next week we have a panel of 4 students so I'm definitely looking forward to finding out even more about 'life beyond GA' soon!

The rest of the day was focused on tackling <strong>OOP</strong> (<strong>object orientated programming</strong>) in which we found out that you could create custom classes that were essentially capable of being cookie cutters for instances and instance methods. It's all still a <em>little bit</em> confusing at the minute but we did a really useful lab along with Alex in which we built an Airport using three custom classes (Airport, Airplane &amp; Passengers) and then looked at how we could create a programme that run in the command line using all three of them.

The homework tonight was more of the same, our task was to build a <strong>pet shelter</strong> using custom classes in the same way - only this time for the shelter, clients and pets. I found it a little easier to do after the lab and even managed to use some methods. I <em>couldn't</em> help but start to think that I was getting the hang of things a little bit!

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/woohoo.gif" rel="attachment wp-att-363"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/woohoo.gif?w=300" alt="woohoo" width="300" height="222" class="aligncenter size-medium wp-image-363" /></a>

I added some ascii art of dogs for shits and giggles and then left for around 9pm.

Mood: <strong>Mellow</strong>

<h1>Week 4 – Day 19 – Thursday</h1>
Today I forgot to make notes on what we got up to for the first time, but essentially it was the day of <strong>Sinatra</strong>. If we hadn't already been introduced to enough bloody names/languages/frameworks, here was another!

<strong>Sinatra</strong> is essentially Ruby's answer to Express that we had looked at whilst using JavaScript. It became clear pretty quickly that it was actually much more simple than Express (which required a nightmare amount of packages to be required every time we started a new project) and was essentially capable of setting up a <strong>RESTful</strong> website using almost the same syntax and structure as we had done in JavaScript. By the end of the day I was actually feeling pretty fond of it and it's ability to allow us to create simple websites using Ruby. It almost felt nice because of the familiarity with what we were doing the week before, despite us working in a language we had only now known for 3 days. Clearly I'm now a programming genius.

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/likeaboss.gif" rel="attachment wp-att-361"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/likeaboss.gif?w=300" alt="likeaboss" width="300" height="225" class="aligncenter size-medium wp-image-361" /></a>

Only joking. The homework for the night was to create a basic site within Sinatra and have something <strong>randomise</strong> upon the page load. I decided to make a Pokemon randomiser (which is completely random but people had been talking about Pokemon all day) and it turned out to be ridiculously simple after some initial confusion with randomising both a key and a value from a hash in Ruby. Just to clarify, it actually loads up a different Pokemon along with it's name every time you click the 'A' button. And <strong>yes</strong> I know, I did the buttons and control pad on the wrong sides, but here's the result anyway:

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/pokemonrandomizer.png" rel="attachment wp-att-356"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/pokemonrandomizer.png?w=300" alt="pokemonrandomizer" width="300" height="165" class="aligncenter size-medium wp-image-356" /></a>

An evening well spent, I feel like an 8 year old boy again. I left for around 8:45pm.

Mood: <strong>Pleased</strong>

<h1>Week 4 – Day 20 – Friday</h1>
I can't believe that it's Friday already! As always we had a team breakfast today at <strong>Leon</strong> before starting a little bit later than usual at 10am. Our agenda for the day was to tackle <strong>custom classes</strong> again, and we had a decent look at how we could use them to create a fake database worth of content for a <strong>RESTful</strong> website. It was nice to work on classes some more as I'm still not 100% confident on both how to use them and also how <strong>OOP</strong> across multiple pages works in general with Ruby.

We also had a cool <strong>pair programming</strong> lab today on <strong>Pig Latin</strong>. The task was to try to recreate the rules of the made-up language using methods, first in whatever way possible and then tidy up the code and make it as tidy as possible. We also used some code tests to see if certain words would change to be as expected in pig latin. The most interesting thing was that when it came to sharing our solutions at the front of the class, nearly everyone had done a completely different thing. Solutions ranged from 60 odd lines of Ruby to an <em>impressive</em> 10, and all had some brilliance to them that I wouldn't have initially thought of myself. I think that's probably one of the <em>coolest</em> things about code, it can be written in a <strong>million</strong> different ways.

We had a decent reprise of some top topics that people were still struggling with (mainly Ruby classes) and then Alex created a random generator on Ruby for the <strong>Grand National</strong> so we were all assigned two random horses each for the GA Electron sweepstakes. It was time for the <strong>pub</strong>.

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/downit.gif" rel="attachment wp-att-359"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/downit.gif" alt="downit" width="227" height="172" class="aligncenter size-full wp-image-359" /></a>

It was 2 for 1 on beers at the Big Chill and it actually very quickly descended into madness. I got in at <em>unknown</em> o'clock.

Mood: <strong>Buzzing</strong>

<h1>Week 4 - Weekend - Sat &amp; Sun</h1>
The weekends homework was the same as the previous Friday, we needed to create a <strong>RESTful</strong> website only this time using <strong>Ruby and Sinatra</strong>. Despite a slow start on Saturday I actually got quite a lot done when I came into Second Home. My idea was to create a website that could be used to enjoy the special features extra content of films and TV shows that used to be enjoyed on a DVD's extra features disk that nobody no longer sees. Here is the end result as of Sunday night:

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/beyonderlysinatra.png" rel="attachment wp-att-351"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/beyonderlysinatra.png?w=300" alt="beyonderlysinatra" width="300" height="165" class="aligncenter size-medium wp-image-351" /></a>

I'm pretty happy with it but would liked to have done a bit more in terms of content and it would have been cool to maybe even add some client side JavaScript interaction but you can't do it all.

And there we have it! The fourth week is done and dusted and I'm already 1/3rd of the way through the <strong>WDI course</strong>. <strong>20</strong> working days down and <strong>40</strong> more to go! This week has been a bit of a whirlwind, but when has it not since I started four weeks ago. I definitely started the week unsure about Ruby after a road bump with the first homework, but I now feel much more comfortable writing in a second language and I'm finding myself needing less help by the week in terms of homework's in general which is encouraging. I think my <strong>key learning</strong> of the week is that tackling new languages <em>isn't as bad</em> as it may first seem and that eventually you start to realise that it's just a new lot of syntax that needs to be learned. And also <strong>JavaScript</strong> may actually be a <em>little bit</em> fucking crazy after all.

<strong>Week 5, I'm ready.</strong>

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/lightsabre.gif" rel="attachment wp-att-360"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/lightsabre.gif?w=300" alt="lightsabre" width="300" height="138" class="aligncenter size-medium wp-image-360" /></a>

Mood: <strong>Encouraged</strong>