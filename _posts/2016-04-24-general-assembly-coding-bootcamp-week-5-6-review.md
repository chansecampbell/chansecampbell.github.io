---
layout: default
title: General Assembly Coding Bootcamp Week 5 & 6 Review
---
<h1 class="header-name">{{ page.title }}</h1>
<h4 class="header-name">Written by Chanse Campbell on {{ page.date | date: '%B %d, %Y' }}</h4>

I knew that it was too good to be true. So I've officially reached the point where I've missed a week of keeping track of things properly, so here's my double blog post recapping everything that's happened in the last 14 days at General Assembly.

<h1>Week 5 – Day 21 – Monday</h1>
Today we were finally introduced to <strong>databases</strong> via <strong>MySQL</strong>. I'm not going to lie, the idea of a database in general sounds boring as hell and so I was feeling a little apprehensive about how much I would like this particular part of the course. We took a very long approach and began by building databases from scratch by writing in sql. It was all a bit confusing and I probably felt the most tired I've ever been on the course. I will say this though, it was a great moment when we finally got a database in MySQL linked up to Ruby and could actually add and delete data through a website. I finally <em>kind of</em> felt like a proper programmer for a minute or two before I felt lost and confused again. The homework was a short sql based one. I went home for 8pm-ish.

<img src="https://media.giphy.com/media/z2Sectp9SiC88/giphy.gif" alt="" />

<strong>Mood:</strong> Shattered

<h1>Week 5 – Day 22 – Tuesday</h1>
Tuesday made everything learned on Monday a little bit easier (which is usually the case at GA). We were introduced to <strong>Active Record</strong> which is essentially an Object Relational Mapping system. In short, Active Record gave us a whole host of really cool new methods that we could use in Ruby to deal with our website and database without having to write out nightmarish lines of sql. The homework today was to build a restful website and link a database up to it. Probably one of the most heavy days yet overall. 
<strong>Mood:</strong> Battered

<h1>Week 5 – Day 23 – Wednesday</h1>
Today we arrived into class and had a slightly nice surprise when we found out during standup that we would be looking at <strong>CSS frameworks</strong> and <strong>sass</strong> for most of the day. CSS has long since been a favourite amongst most people in the class, probably due to the fact that you see some instant results and they are mostly semi-pleasing. The one thing that we couldn't yet do however was to make a website that actually looks industry standard and that's where frameworks come in. Essentially the frameworks (we looked at Materialize, Bootstrap, Bourbon, Pure and Foundation) are downloadable stylesheets that have already been made and designed to get your website looking good quickly. It amazed me that suddenly we were grabbing a piece of code and snapping it into our layout.erb and BAM my classwork had the best header bar I'd ever seen. And it's responsive.

<img src="https://media.giphy.com/media/vRnArG5o62Gs0/giphy.gif" alt="" />

The homework was nothing short of hectic. Lot's of people decided to try tackling more of the database stuff by attempting to link two different models and establishing some sort of website relationship (e.g. a user can submit many posts). I went down this route too and successfully had a working two model relationship by 10pm which is good going to say we only looked at databases on Monday. Unfortunately that meant a sacrifice to styling for tonight.

<strong>Mood</strong>: Pleased

<h1>Week 5 – Day 24 – Thursday</h1>
Thursday was a pretty rewarding day (and it was also a bit of a head fuck). Today we tackled website encryption using the Ruby Gem BCrypt. We first examined how to get a user model to create a user that could register to a website and create their own username and password. Next we also got our user to log in and out of a website's session. It's definitely a good feeling to be able to take our websites to that next level and understand a tiny bit more about how password encryption works but I ended up super stressed during homework time when I tried to do it all from scratch and broke the project. I left at around 10pm.

<strong>Mood</strong>: Tired
 
<h1>Week 5 – Day 25 – Friday</h1>
Everyone loves Friday. We had our usual team breakfast which also meant that I had time to go to the gym which is a bit of a rare treat at the minute. We then spent most of the day going through relationships between models and how this worked within the database as lot's of us still felt unsure about how it worked beyond a second model. Our weekend homework was to put all of our knowledge into practice and make a cool multi-model website with a CSS framework in preparation for our upcoming second project.

<strong>Mood</strong>: Glad the week is over.

<h1>Week 5 – Weekend – Sat &amp; Sun</h1>
I powered on through a hangover to create a mock version of a reddit message forum. It ended up looking pretty good for a weekend homework thanks to Materialize and I even managed to successfully use BCrypt and two models.

This week has definitely been the hardest yet in terms of the sheer amount of content we've had to cover and the rate in which we've moved. Just when you think you're starting to understand how something might work you're given a shortcut which makes matters more confusing or even worst a completely new topic entirely, but I'm into a rhythm now and we're nearly half way!

<strong>Mood</strong>: Prepared

And that finally brings me up to this week, I'm going to keep this one nice and <strong>short</strong>!

<img src="https://media.giphy.com/media/Fd2RnPlhaHVlu/giphy.gif" alt="" />

<h1>Week 6 – Day 26 – Monday</h1>
Today was a pretty cool day. We finally met <strong>Rails</strong> after hearing so much about it whilst working in <strong>Sinatra</strong>. By the point we were up to in the weekend homework, Rails basically seemed to be a super useful framework that did a lot of what it took us hours to do in Sinatra in a matter of minutes. Infact, we actually timed our instructor Alex and he managed to set up a website that allowed him to add, list, delete and edit books in under 2 minutes. That's <em>slightly</em> insane. 

I can definitely see the use case in learning the long way round though as if we had come straight here from learning Ruby 101 we would have no idea what was going on for sure. Tonights homework was to get acquainted with Ruby by building another RESTful website and playing with a CSS framework so we could re-familiarize with the slightly new way of setting up a site. I played around with Ruby and the relationships but didn't go to town on the styling personally. My only train of thought right now is that there suddenly seems to be a shit ton of files that get created and it's a nightmare to keep a track of everything.

<strong>Mood</strong>: Lost

<h1>Week 6 – Day 27 – Tuesday</h1>
We continued on with our conquest of Ruby by coding along together as a class the basic website structure for Fiverr. For those who haven't seen the site before, you basically have users who sign up and post their odd-job services for up to five pound (although ironically there are now a LOT of things listed at over 5 quid). This lab we really useful as we started by discussing the ERB relationship model as a group and then built the basic structure for a social media website.

Along with looking at a few little things like validations and how they could work to ensure a user inputs an email address and password, our homework for the night was music to our ears. We basically had to brainstorm and consider what we wanted to do for our project beginning on Friday. This discussion pretty much happened in the pub with several pints in hand but by the end of the night I had an idea.

<strong>Mood</strong>: Excited

<h1>Week 6 – Day 28 – Wednesday</h1>
Wednesday we concluded our journey into building Fiverr by finishing off our group code along which was super helpful to do and was also accompanied with a walkthrough by one of the TA's Ollie. We then spent quite a bit of the day looking at <strong>Devise</strong>, a very useful Rails Ruby that would allow our website to authenticate and support login/out sessions even easier and faster than BCrypt. Along with that we looked at <strong>OAuth</strong> which essentially allows a website to utilise a Facebook or G+ login to access a site without the need of a user signing up.

Although it was very useful to see this and practice the OAuth during a lab, I'm definitely still not comfortable that I know what I'm fully doing here. Homework for the night was to look at a few new gems that could allow for some very cool things in Ruby - comments, photo uploading and website searching. Surprisingly it was all relatively easy stuff to understand and grasp!

<img src="https://media.giphy.com/media/3o85xyQCzhau6gxiFi/giphy.gif" alt="" />

<strong>Mood:</strong> Optimistic

<h1>Week 6 – Day 29 – Thursday</h1>
Today marked the start of our <em>second official project</em> at GA, this would be the first time that we would be making a proper website that we have more than 2 days on. I think that most of the class felt pretty excited to finally buckle down on a single idea and combine a couple of weeks worth of new knowledge onto one piece of work. For my project I'd decided to create a skills sharing website, essentially a moneyless marketplace in which users can offer a tutorial or local training in any area (think a free guitar lesson, coding advice or someone to give a bit of training at the gym). In return the user earns a credit that they can then utilise elsewhere in order to also access free training in a field they've always wanted to try. I'll elaborate more on the idea when I'm done but for now we focused on the planning aspect of the project before we could even think about coding it.

As a class we had a brief look at using Trello to organise workflow and also wire framing in order to draw out and visualise the user experience. I ended up getting super into the <strong>wireframes</strong> and spent the entire day on Balsamiq creating all of the designs that my user might see as they use the website. This ended up being really helpful as I realised on multiple occasions that I had missed out a key step in the journey and by the end of the day I had a lot of my site planned out.

<a href="https://thelongcodeahead.files.wordpress.com/2016/04/skwap_app.png"><img src="https://thelongcodeahead.files.wordpress.com/2016/04/skwap_app.png?w=300" alt="skwap_app" width="300" height="131" class="alignleft size-medium wp-image-379" /></a>

<strong>Mood</strong>: Creative

<h1>Week 6 – Day 30 – Friday</h1>
After a morning of further planning in which I dabbled yet again with my wireframes, I finally cracked on with some basic coding as I was fairly keen to get the Devise encryption setup on my project at the very least (so that a user could register, login and logout). I ended up being one of the last people in the class to start coding but I tried to forget about it and work at my own pace. The plans don't look too complicated to be fair, so fingers crossed it's all smooth sailing from here over the next 7 days.

<strong>Mood</strong>: Friday

<h1>Week 6 – Weekend – Sat &amp; Sun</h1>
This weekend I got a <strong>shitload</strong> done. I went into Second Home both days for several hours and by Sunday had built a three model website that allowed a user to register, sign in and post a skill available. Another user could then login and request to be trained up. As of right now I <em>even</em> have submittable comments for users to arrange to meet to share skills and a search feature via Ransack that allows a user to search through listing categories or listing locations.

Over the next few days I've got quite a few things I still need to add, along with what I'm hoping is at least a fourth model for reviews. I'll post a link to the site at the end of next week on here. On a side note, as of tomorrow we are officially the older class in London (with a new GA cohort starting). It's crazy to think that we are now past the halfway point, but despite not knowing what's going on half the time and feeling knackered most of the other half - I can definitely see a huge leap in knowledge and capability amongst the class now. Now it's time for project week!

<img src="https://media.giphy.com/media/SRsh4bSvJ980U/giphy.gif" alt="" />

<strong>Mood</strong>: Productive