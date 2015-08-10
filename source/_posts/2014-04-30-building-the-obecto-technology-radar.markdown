---
layout: post
title: "Building the Obecto Technology Radar"
date: 2014-04-30 17:01:38 +0300
comments: true
categories: [Blogging, Obecto, Technology Radar] 
---

We started [Obecto][obecto] at the fall of 2008. During the period of 2007-2012, I was particularly focused on growing my company's Flex expertise *(including mine)*. For those that never heard of Flex, this is a front-end technology developed by Adobe. It's comprised of a set of **programming languages** (ActionScript 3 and MXML), a **byte-code execution environment** (Flash & AIR) and a very mature set of quite sophisticated **SDK and frameworks** (Eclipse-base IDE, debugger, profiler, Cairngorm, Parsley, RobotMVC, etc.) As we were growing our expertise we had our share of contributions to the open source community, namely the [FLit framework -- a light-weight Flex for Flash Applications][flit]. Our reputation grew to a point where the Bulgarian division of VMware contracted us to train over 80 of their finest engineers. We also taught a significant part of a Flex university course at the *Sofia University*...

> <cite>My point is, we become so damn good at Flex/Flash, and the technology was so powerful *(even now the most popular Javascript framework are still not providing the same capabilities and productivity)*, that our hubris blinded us from seeing the bigger picture in the technology world despite all of the signs *(e.g. the total lack of support of Flash on the iOS devices and mobile in general)*...</cite>

<!-- more -->

Flex was the answer to all of our needs -- current and future -- you name it: complex web applications, desktop applications and even a viable alternative to native mobile. Despite the unprecedented productivity and technology capabilities of Flex allowing the development of mind-blowing user interactions and user experiences, this technology was very quickly in decline. And it suddenly vanished one day, leaving my company with a portfolio of impressive projects done with a dead technology. We had to start basically from scratch to develop a new expertise, and build a new portfolio respectively, that will set us apart and beyond the average software development studio. It took us almost 2 years to regain expertise and build up our portfolio. 

> <cite>That thought us an important lesson! Technology companies need a process to continuously assess new technology and discuss potential future directions, while at the same time maintain sharp focus at the technologies offered as main platform choices to their customers.</cite>

As part of such process, at [Obecto][obecto], we decided to use a tool called **Technology Radar**. For those readers, unfamiliar with this tool and his concepts, I suggest reading [Build Your Own Technology Radar][neil] *by Neil Ford*. The *radar* as [ThoughtWorks][thought-works], the company that invented it, defines it is:

> <cite>...a document that sets out the changes that we think are currently interesting in software development - things in motion that we think you should pay attention to and consider using in your projects. It reflects the idiosyncratic opinion of a bunch of senior technologists based on our day-to-day work and experiences.  
> --- **ThoughtWorks**, [Technology Radar - FAQ][tech-faq] </cite>

So let me present you the first version of the Obecto technology radar:

<div class="screenshot">
{% img https://farm1.staticflickr.com/442/20456936485_17a922efe2_o.png 640 640 Obecto Tech. Radar - April 2014 %}
</div>

The first edition of our radar marks few important moments:

* **Flash/Flex** - our departure from Flex/Flash has finished and it has deserved its honourable place in the graveyard of good technologies. Nonetheless, we're still continuing to support a couple of AIR desktop applications for the pharmaceutical industry.
* **Spring-Roo** - even though *spring-roo* has saved us numerous hours of coding by generating the boilerplate and necessary plumbing for us, it has reached a point where projects that are using *spring-roo* are very difficult to maintain as tooling. The tooling behaves inconsistently across different versions and especially when combined with **Eclipse STS**. The **Spring frameworks** had matured to a level where we no longer need *spring-roo*. No new projects will be started with *spring-roo* and there's an undergoing initiative to get rid of *spring-roo* from all active projects. We expect to complete this effort until the end of 2014. It'll certainly be reflected on the coming editions of the radar.
* **Angular.JS** - now that we no longer rely on the use of *Flex/Flash* for building web applications, we have adopted *Dojo 1.8* as one of our core technologies for building SPA *(Single Page Applications)*. Since the beginning of the year we have spotted *Angular.JS* as a better alternative to *Dojo* and we're in a process of active adoption. All new web application projects are using *Angular.JS* and we expect it to be fully adopted in the coming quarters.
* **JSP/JSF** - using server-side generated pages still has its place in certain solutions. But the JSF technology is not intended to be the most performing web technology. Also as an enterprise technology it relies on a sufficient hardware. There is always some room for performance optimization, but regardless of performance there are certain limitations when trying to implement more sophisticated interaction design and UX, such as applying the **mobile-first** technique.
* **Node.js** - after few successful pilot projects, we truly believe in the pursuit of a **full Javascript** technology stack. One programming language used across all application layers. With some rough edges for operations, it is time to put *Node.js* through a trial of several bit more complex projects.

Don't hesitate to contact me if you have questions regarding any dot on the Obecto tech. radar.

Keep in mind, this is a **no comments**-type of blog, because [there are better ways to respond][no-comments]. 

[obecto]: http://obecto.com "My Company"
[flit]: https://code.google.com/p/flit/ "FLit - a lightweight Flex for Flash Apps"
[neil]: http://nealford.com/memeagora/2013/05/28/build_your_own_technology_radar.html "Build Your Own Technology Radar"
[thought-works]: http://www.thoughtworks.com/ "ThoughtWorks corporate site"
[tech-faq]: http://www.thoughtworks.com/radar/faq "ThoughtWorks -- Technology Radar FAQ"
[no-comments]: http://vladi.io/blog/2014/01/07/switching-off-comments/ "Switching Off Comments"
