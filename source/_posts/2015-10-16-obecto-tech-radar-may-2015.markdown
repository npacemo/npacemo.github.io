---
layout: post
title: "Obecto Tech Radar - May 2015"
date: 2015-05-16 14:24:11 +0300
comments: true
categories: [Blogging, Obecto, Technology Radar] 
---

In our third edition of the radar, we have attempted to represent the radar in a way more approachable for customers and even non-technical people.
How would you explain what the radar is to someone who's never seen it before?

> <cite>One of the biggest challenges is our industry is how to stay fresh. New technologies, tools and practices are coming in all the time — especially new unproven ones. Technology strategy will be at the core of most business strategies, and it is essential to have a plan how new technology is adopted.</cite>

To answer the question above, at Obecto, we think that the **tech radar** is a really good way to proactively seek for new ways to do our work and bring competitive advantage to our customers, while at the same time maintain focus on what we currently do as standard practices in our industry and maintain the Obecto portfolio of projects in production.

<!-- more -->

The radar is organised in 4 quadrants:

* **Languages & Platforms**
* **Tools & Frameworks**
* **Techniques & Methodology**
* **Practices**

Within a quadrant there are rings showing the stage of adoption of each point:

* **Everyday Use** — the final stage of adoption; considered to be our core expertise.
* **Proficient** — used in production projects, but yet to be fully adopted.
* **Playing with** — still in experimentation and research stage, used only in pet projects.

## Languages & Platforms

<div class="screenshot">
{% img https://farm1.staticflickr.com/633/22030390419_423bb96fb2_o.png 640 640 Languages & Platforms - Obecto Tech. Radar - May 2015 %}
</div>

Some points from this quadrant that are worth highlighting:


* **Node.js** — as our portfolio of Node.js project grows, this platform is in trend to be fully adopted in the near quarters.
* **Java 8** — we’re following closely the Java 8 readiness of all frameworks we currently use and plan to migrate existing projects to Java 8.
* **Android & iOS** — our native apps mobile experience portfolio is not impressive enough to consider this fully adopted. Nevertheless, we feel proficient in both mobile platforms. That’s an expertise not to be underestimated!
* **Swift** — our next iOS project will be in Swift instead of Objective C.
* **Clojure, Scala, Erlang** — our team is quite excited about the functional programming languages. The following quarters will show if any new project would be approached with a solution that includes the functional style of programming.
* **ECMA Script 6** — we’re experimenting with ECMA Script 6 to Javascript compilers that we can use in existing projects.

## Tools & Frameworks

<div class="screenshot">
{% img https://farm1.staticflickr.com/592/22029213280_4b0f04cd3f_o.png 640 640 Tools & Frameworks - Obecto Tech. Radar - May 2015 %}
</div>

Our current selection of tools and frameworks is optimised for building very efficiently Single Page Applications (SPA) with backends providing REST APIs. 

* **Symfony 2** — in the current edition of the radar we’re putting on hold Code Igniter taking it out of everyday use. All new PHP projects are started with Symfony. All PHP projects in production have been migrated to Symfony 2.
* **Bootstrap** — when it comes to responsive web applications and mobile-first, 2014 was a very busy year for us (for more info check our mobile experience portfolio).
* **Mongo** — very soon Mongo will get its place in the core ring next to the relational databases we typically use (e.g. MySQL and PostgreSQL).
* **Cassandra & Hadoop** — even though these are placed in the Proficient ring it worths mentioning that we have over 2 years of experience in using them as part of our custom analytics solution that we built for [Newstag][newstag]. 

## Techniques & Methodology

<div class="screenshot">
{% img https://farm1.staticflickr.com/672/21594525034_31c532dcc4_o.png 640 640 Techniques & Methodology - Obecto Tech. Radar - May 2015 %}
</div>

The process and methodology in Obecto has evolved to support projects of varying complexity and size with ever increasing focus on being as lean as possible.

* **SCRUM** — we consider ourselves experts in applying the *SCRUM framework* for projects that need to sustain longer term development.
* **OOP** — we still feel that the *Object Oriented Programming* paradigm when combined with good knowledge of the *Design Patterns* and the *SOLID principles* gives the most versatile approach for software projects.
* **Responsive & Mobile-First** — when it comes to responsive web applications and mobile-first, 2014 was a very busy year for us. These two techniques have become a valuable additions to our core expertise.
* **Customer Development** — that’s a lean startup methodology. Nevertheless, when applied in the context of the early stages of a software project it brings very efficiently validation and verification of the core concepts and assumptions by using a systematic approach.

## Practices

<div class="screenshot">
{% img https://farm1.staticflickr.com/727/22217268745_14d047471e_o.png 640 640 Practices - Obecto Tech. Radar - May 2015 %}
</div>

Practices are specific elements that we use and apply in our software development process, such as how we write, or test, or release our code.

* **Clean Code** — we have projects that need to sustain development in the longer term. Cleanliness of the code is crucial when we need to maintain our productivity in the long term.
* **TAD** — *Testing After Development* is a practice where the unit test is written after the actual code, and only specific part of the code are put under such unit testing instead of being in pursuit of 100% code coverage. For many project we have done exactly the opposite and we’re very proficient in **TDD** *(Test Driven Development)*, as well as writing *end-to-end tests* with the help of **BDD** *(Behaviour Driven Design)*.
* **Story Points** — we’re currently playing with Story Points in the practice of estimation and we’re looking forward to use this practice in our customers’ projects.

Don't hesitate to contact me if you have questions regarding any dot on the Obecto tech. radar.

Keep in mind, this is a **no comments**-type of blog, because [there are better ways to respond][no-comments].

[newstag]: http://newstag.com/ "Newstag - you are it!"
[no-comments]: http://vladi.io/blog/2014/01/07/switching-off-comments/ "Switching Off Comments"
