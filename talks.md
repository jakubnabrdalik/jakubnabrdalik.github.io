---
layout: page
title: Talks
permalink: /talks/
---

Apart from regular work, I go to a lot of conferences, meetings, hackathons, and alike, for inspiration and knowledge. At some point I started giving talks and leading workshops myself. Each talk requires a lot of research, so it helps me to get better, while helping others as well. Pure win-win situation. 

So far I've given 136 talks. Not bad for a hobby. Below you will find some of them.

--------

### Migrate your company to microservices: a step by step tutorial

I’ve worked with microservices for 9 years now, and I’ve migrated systems from monoliths / distributed monoliths to microservices. Companies call me to help them in this process, and I kind of worked my “standard” way of how to do this. In this talk, I’d like to show you step by step what I do when I help companies moving into microservices. 

This talk is not about how to design microservices per se (I’ve already talked about it a lot, and I give workshops on that) but what exactly I do in the process, and what you should not forget about. So it’s everything apart from architecture itself. 

I’ll talk about: 
- how (much) to design the initial architecture
- how to build an easy to use tailored service template
- what you need in pipelines
- how to test the system
- what security changes are required
- how to teach observability
- how to introduce product teams and a culture to get the most of microservices (and what happens if you don’t). 

Of course every company is a bit different and this is not the only way to do it, but if I show you what it usually means for me perhaps you will find something you didn’t take into account in your process, if you are ever in such a situation. And if you are currently working with monolith (distributed or not), this may be really useful.

[Slides](https://jakubn.gitlab.io/migrate2microservicesstepbystep)

### Why nobody sane builds a large monolithic system today

There are architects that suggest starting every system with a monolith.

That is a harmful suggestion, you need to understand what microservices and monoliths require, why microservices were invented and what problems they solve.

After working for 12 years with monolithic systems and 8 years with microservices I'd like to give you some insight into when to use microservices, and when it's pointless. 

In addition I'll talk about:
- why for 38 years companies struggled to build large systems, and why Fred Brooks can finally rest in peace
- how Ken Thompson and Dennis Ritche easily solved the problem which costed IBM millions of dollars
- why developers get insane and burn out, and why the next generation will be much healthier
- why for some companies building large systems is easy, and gets easier every month. It also does not require any pain or blood spilled
- why your company is getting on your nerves and why your manager struggles with the concept of autonomous teams
- what are the PREREQUISITES for a company to benefit from microservices
- simple heuristics when to build which kind of the system

[Video@DDD-WAW](https://www.youtube.com/watch?v=1pBOUa4vX0w)

### How to NOT get insane when working for 20 years as a dev - personal mental health tricks.

I've been designing and building software for the last 20 years, and in that time I've lost a lot of friends due to burnout and depression. A lot of others have moved to management, become POs, Scrum Masters or full-time celebrities. When talking with them most say that writing software became too difficult for them. Which is strange, because from my perspective, programming is much easier than 20 years ago.

I'm not a psychologist, I have no proper education or skills to help you out, but I've survived 20 years, and I'm no more insane than I was back then, so maybe I can tell you what have helped me survive, and be even more happy in a software dev job. If it helps one person not become a manager, I'll consider my job done.

[Video@Confitura](https://www.youtube.com/watch?v=PabarutaU6I), [Slides@Confitura](https://jakubn.gitlab.io/howtonotgetinsane/)


### Best practices in practice: things that work for me so well I cannot believe you are not using them

There's a lot of "best practices" around, but after 19 years of work I've found a set that really helps get my systems done well. I'd like to share those tools and methods and why they work in my context. While they are not a novelty (some of them have years of history), I see even experienced developers ignoring them. These include: how to use BDD to work with requirements, using a scientific method to fix problems in production (as opposed to shotgun debugging), verifying observability during development (before going to production), making the most interesting parts visible via higher order functions, and more. Nothing groundbreaking, but perhaps those will also work in your context.

[Slides@Confitura](https://jakubn.gitlab.io/bestpracticesinpractice/#1), [Slides@DevTernity](https://jakubn.gitlab.io/bestpracticesinpractice/#1)

## What I wish I knew when I started designing systems years ago

I started designing systems (also known as: architecture) 18 years ago. I'm not very smart, so I've made a lot of mistakes on the way. Surprisingly it turned out these are quite common. I'd like to share a few things I’ve learned that would save me a lot of tears, had I known better back then. I’ll talk about communication styles, modularity, SLA, invariants and events, choreography vs orchestration, single point of truth vs data ownership, products vs projects.

This talk is for people starting with software architecture.

[Slides](https://jakubn.gitlab.io/wish-i-knew-architecture/#1), [Video@DevoxxPL](https://www.youtube.com/watch?v=4Iqjhi3kusY), [Video@JDD](https://www.youtube.com/watch?v=OX0HHHhiapQ), [Video@Developers World Academy](https://www.youtube.com/watch?v=1HJJhGHC2A4), [Video@Silesia JUG](https://www.youtube.com/watch?v=Q1bQcu_lFCk)

### With a little help from my friends: architecture in a group of anarchists

So if you already have an Architecture Guild (see "Common mistakes" talk), how do you actually grow your soft skills? As a nerd. Lots of books and thoughts on that matter.

[Slides@Devdays](https://jakubn.gitlab.io/devdays2020/#1), [Slides@Orange](https://jakubn.gitlab.io/withalittlehelp/#1)

### Common mistakes when moving to microservices

Since I help enterprises move to microservice based architecture, I've noticed some common mistakes and I've learned how to fix them

[Slides](https://jakubn.gitlab.io/mistake2microservices/#1), [Video@GeeconPrague](https://www.youtube.com/watch?v=6H3mSY1AJ1k), [Video@Confitura](https://www.youtube.com/watch?v=jo46-CP6ywU), [Video@SegFault](https://www.youtube.com/watch?v=8zKuvyhKroQ), [Video@KJUG](https://www.youtube.com/watch?v=PSZ2jJRTP3I), [Video@DevTernity](https://www.youtube.com/watch?v=sXIvrgTtmZE), [Video@JDD](https://www.youtube.com/watch?v=Ei64m2rrhv4), [Video@JSanta](https://www.youtube.com/watch?v=Qxa4Aay-nYw), [Video@DevOpsProE](https://www.youtube.com/watch?v=9CfABzQd6Mc), [Video@4Developers](https://www.youtube.com/watch?v=uL6EYqN17Oo&feature=youtu.be)

### Improving your Test Driven Development in 45 minutes 

I use TDD since 2005, and I've been teaching BDD/TDD for several years now, so I have a few tricks I can share

[Slides](https://jakubn.gitlab.io/improvingtdd/), [Video@DevoxxPL](https://www.youtube.com/watch?v=2vEoL3Irgiw), [Video@Greenfield](https://www.youtube.com/watch?v=PwMNtiKb-P4), [Video@GeeCon](https://www.youtube.com/watch?v=lJT0aZbrWUo), [Video@JeeConf](https://www.youtube.com/watch?v=NzknrbrV8BY)

### Keep IT clean, mid-sized building blocks and hexagonal architecture

On Java package-scope visibility, hexagonal architecture (ports&adapters) and modularity

[Slides](https://jakubn.gitlab.io/keepitclean), [Video@IstanbulTT](https://www.youtube.com/watch?v=sOaS83Ir8Ck)[Video@Confitura](https://www.youtube.com/watch?v=ma15iBQpmHU), [Video@AJLabs](https://www.youtube.com/watch?v=5Q8kiSN6390), [Video@TorunJUG](https://www.youtube.com/watch?v=KO6K3_Ac54M), [Video@SilesiaJUG](https://www.youtube.com/watch?v=kW-k9UXhGqw)

### Peer-2-Peer Salary Review

A case study for a how I solved the problem of setting up salaries for an IT department

[Article](https://jakubnabrdalik.github.io/P2P-Salary-review/), [Video@WJUG](https://www.youtube.com/watch?v=odrean5ShZQ), [Video@AceConference](https://www.youtube.com/watch?v=hIkNRCQaGBg), [Video@DevTernity](https://www.youtube.com/watch?v=vQMYjpjpelg), [Video@ABE15](https://www.youtube.com/watch?v=qlpAAxCtEgg)

### User Stories considered harmful

Why Product Owners and Developers failed at gathering requirements and communication. The lost art of analysis and testing scenarios. A talk about gathering requirements, use cases, behavioural acceptance scenarios and TDD/BDD

[Slides](https://docs.google.com/presentation/d/1VhDuWbCbdbOwdB1GG9Jxf9OfGq0OKfsRmLDPlWxgrSk/edit?usp=sharing), [Video@DevoxxPL](https://www.youtube.com/watch?v=2df8_PHJuzk), [Video@WJUG](https://www.youtube.com/watch?v=ATZ0GEMSivM), [Video@AgileByExample](https://www.youtube.com/watch?v=aKa6xogoztM), [Video@ITT2018](https://www.youtube.com/watch?v=jnox2eCJoL0)

### Requirements & BDD: The lost art of analysis and acceptance scenarios

A different take on "User Stories considered harmful"

[Slides](https://jakubn.gitlab.io/requirements-and-bdd/#1), [Video@Programistok](https://www.youtube.com/watch?v=71fdXhlHXjE)

### Test Driven Traps 

In 2012 I gave the first summary of errors with TDD/BDD (having 7 years of experience at that point). For an up-to-date version see the "Improving your Test Driven Development" talk.

[Video@Confitura](https://www.youtube.com/watch?v=wbAtJlbRhbQ)

### Creating a knowledge-sharing culture

Because your really need it

[Video@ABE](https://www.youtube.com/watch?v=ArtWaNglMQk)

### Conway's revenge: How ignoring org setup backfires in architecture, and vice versa

[Video@BydgoszczJUG](https://www.youtube.com/watch?v=UhIIpUQ-i38), [Video@DevTernity](https://www.youtube.com/watch?v=jcpaAsfQOUQ), [Video@GDoC](https://www.youtube.com/watch?v=krUc9l0o33I)

### eXtreme Programming for beginners

[Video@ABE](https://www.youtube.com/watch?v=RUlsNnzFWy8)

--------

## Activity log

Here I keep a list of events and activities, to keep me motivated and remind me, I actually had some social life apart from software development.

### 2024

*Migrate your company to microservices: a step by step tutorial* - Given at 4Developers, Geecon, IT-Konekt, javeloper

CodingFestival

### 2023

*Why nobody sane builds a large monolithic system today* - Given at DDD-Warsaw

*What I wish I knew when I started designing systems years ago* - Given at CodingFestival

*Best practices in practice: things that work for me so well I cannot believe you are not using them* - Given at Craft-IT Rzeszów, I love dev in Warsaw, MS Tech Summit, Warsaw Java User Group, 4Developers

*Hexagonal architecture interview* - at Better Software Design

### 2022

*How to NOT get insane when working for 20 years as a dev - personal mental health tricks.* - Given at Confitura

*Refactoring from monolith to microservices* - Nerguru, Asseco

*Malevolent Architect: only bad decisions* - Closing keynote at Geecon

*Developer w świecie mikroserwisów: W co warto pakować swój czas, by mieć aktualny skillset* - at Warszawskie Dni Informatyki

*What I wish I knew when I started designing systems years ago* - Given at Devflix

### 2021

*What I wish I knew when I started designing systems years ago* - at JDD, Devternity, 4Developers, Warszawskie Dni Informatyki, Bydgoszcz JUG

### 2020

*With a little help from my friends: architecture in a group of anarchists* - Given at Orange Atom Dev Days, Infobip DevDays

*Common mistakes when moving to Microservices, 2 years later* - Given at SegFault Online, Kielce JUG, DevOps Pro Europe, 4Developers Online, V Project Management Forum

### 2019

*Common mistakes when moving to microservices* - Given at Geecon Prague, DevTernity in Riga, Confitura in Warsaw, JDD in Krakow, J-Santa in Lublin, Motorola in Krakow, [Devternity](https://devternity.com/) conference in Riga

*Hexagonal Architecture in practice* - Given at Istanbul Tech Talks

*Requirements & BDD: The lost art of analysis and acceptance scenarios* - Given at Confitura in Warsaw

*Improving your Test Driven Development in 45 minutes* - Given at Devoxx Marocco,[Grienfield Conf](http://greenfieldconf.pl) in Zielona góra, GeeCON in Krakow, Sonalake in Poznan

*User Stories considered harmful* - Given at Istanbul Tech Talks

###  2018

*Requirements & BDD: The lost art of analysis and acceptance scenarios* - Given at [Programistok](http://programistok.org/) conference in Bialystok

*Improving your Test Driven Development in 45 minutes* - Given at [Geecon](https://2018.geecon.org) conference in Krakow, at Wroclaw Java User Group, at [Devoxx](http://2018.devoxx.pl/) conference in Krakow, at [Confitura](2018.confitura.pl) conference in Warsaw, at [JCConf](https://jcconf.tw/2018/schedule-1.html) in Taiwan, at [ByteMyCode](bytemycode.pl) conference in Wroclaw, and at [Devternity](https://devternity.com/) conference in Riga, at Orange in Warsaw

*User Stories considered harmful* - Given at [Devoxx](http://2018.devoxx.pl/) conference in Krakow, and at [Agile Warsaw](https://www.meetup.com/AgileWarsaw/events/252166967/)

*Keep IT clean* - Given at the Faculty of Mathematics and Information Science of Warsaw University of Technology during Warszawskie Dni Informatyki, at jSession (Java User Group in Białystok), at Silesian Java User Group, and at [C-tech](https://eventil.com/events/c_tech-5-jakub-nabrdalik-wspolne-ogladanie-meczu-spotkanie-na-swiezym-powietrzu/) group meeting in Warsaw

Once again, I was in the Program Committee of [DEVOXX PL](http://devoxx.pl) responsible for the Architecture track

### 2017

*Shit in, shit out* - A revised and extended version of my previous talk User Stories considered harmful given at ALE Krakow

*User Stories considered harmful* - Given at Agile by Example 2017 conference in Warsaw

*Creating a knowledge-sharing culture* - Given at Agile Silesia in Katowice (slides)

*Conway's revenge: How ignoring org setup backfires in architecture, and vice versa* - Given at Bydgoszcz Java User Group

*Spring introduction* - A lecture given at the Warsaw University of Technology.

*Keep IT clean* - Given at Confitura conference in Warsaw, at Warsaw Java User Group, at Software Architecture & Design Debate in Warsaw, at Allegro Tech Talks in Poznan, at the Faculty of Physics, Astronomy and Applied Computer Science of Jagiellonian University (itakademia), at 4Developers conference in Warsaw, at JDD conference in Cracow, and at Devternity conference in Riga

I mentored a young graduate for 5 months as part of the Tech Leaders programme for Women In Technology

Once again, I was in the Program Committee of DEVOXX PL

### 2016

*Peer-2-Peer Salary Review* - Given at Devternity in Riga

*Creating a knowledge-sharing culture* - Given at Agile By Example 2016 conference in Warsaw	

*Keep IT clean* - Given at JUGtoberfest in Łódź and at Torun Java User Group

*Peer-2-Peer Salary Review* - Given at Warsaw Java User Group, ACEconf in Cracow and CybercomDev in Łódź

*Spring introduction* - A lecture given at the Warsaw University of Technology.

*Conway's revenge: How ignoring org setup backfires in architecture, and vice versa* - Given at Kiev DevOps Day conference

Once again, I was in the Program Committee of DEVOXX PL one of the biggest Java conferences in central Europe, helping choose speakers and talks for all tracks

I was mentoring two Spring Framework project groups at Warsaw University of Technology

I helped to organize Gr8day Warsaw, a conference on all things Groovy

## 2015

*Conway's revenge: How ignoring org setup backfires in architecture, and vice versa* - Given at Devternity craftsmanship conference in Riga

*Game of throneware, or how not to get killed when a developer becomes a manager* - Given at PGS Software Talks in Gdańsk

*Peer-to-peer salary review in a corpo: a case study* - Given at the Agile By Example conference; I was one of the panelists at the Product Owner discussion panel there

*Conway's revenge: How ignoring org setup backfires in architecture, and vice versa* - Given at bycraft.by craftsmanship conference in Minsk

*Test Driven Traps* - Given at Geecon TDD in Poznań

*Game of throneware, or how not to get killed when a developer becomes a manager* - Given talk at Latvian Software Craftsmen group in Riga

I helped organize Agile Development Day during Global day of coderetreat, mentored developers on TDD, and gave the opening presentation

I led a Spring Cloud & Boot workshop (3h) at Codepot.pl conference in Warsaw

I helped shape the agenda of JDD Conference in Cracow as part of the program committee

I was in the program committee for DEVOXX PL, one of the biggest Java conferences in central Europe

### 2014

*eXtreme Programming for beginners* - Givem at AgileByExample conference in Warsaw

*Game of throneware, or how not to get killed when a developer becomes a manager* - Given at jPiknik in Warsaw, at JDD conference in Cracow and JUGtoberfest event organized by Java User Group Łódź

*Spring framework* - A lecture given at JInkubator in Warsaw [Video](https://www.youtube.com/watch?v=RQEsSCwsRf0)

*Spring Data JPA* - An open workshop at Spring Labs in Warsaw

*Spring Security* - An open Workshop at Warsaw Spring Labs in Warsaw

Together with my collegues, I organized microhackaton, a hackathon about microservices

Together with Tomasz Szymański and Marcin Grzejszczak, I've created Warsaw Groovy User Group, with regular meetings.

### 2013

*Gitkata* - I lead 4 workshops about git, during a full day mini conference Gitkata 2 and 5 during Gitkata

*Test Driven Development for beginners* - A workshop at Agile by Example conference in Warsaw

*Test Driven Traps* - Given at Confitura conference in Warsaw, 33rd Degree for charity conference in Krakow, Poznań Java User Group, and Trójmiasto Java User Group

*Apocomito, or what problems DDD, CQRS, NoSQL and microservices solved for me* - Given at j.Piknik in Warsaw

*Test Driven Development* - I lead a workshop a full day mini conference Testkata in Warsaw

*MongoDB* - Given at Warsaw Java User Group [Video](https://www.youtube.com/watch?v=r3wIYOggWmU)

*QA in the day of Test Driven Development* - Given talk at Kariera Testera

*Job interviews in Software Development* - Given at Warsaw Java User Group, together with Jakub Kubryński, and Tomasz Szymański

*NameCollison Opening talk* - Given at NameCollison Hackathon

*Spock* - A flashtalk at Warsaw Java User Group

I wrote a chapter The Root of All Evil for Tomek Kaczanowski's book Bad Tests, Good Tests (you can download digital copy for free here)

Together with Piotr Jagielski, I wrote a small book about Spring Security framework, and got it published.

Together with six other guys, I became an organizer of Warsaw Java User Group meetings. We were responsible for keeping our regular lectures interesting, and a few mundane tasks, like the web page, sponsors and so on.

### 2012

*Test Driven Traps* - Given at Topconf conference in Tallinn

*Don't write in Java. You know better languages even if you're not aware of it yet* - Given at Confitura conference, with Tomasz Przybysz

*Beautiful failures, when good things go bad, a few case studies* - Given at a Birds of Feather session at 33rd Degree Conference in Krakow and at Agile Warsaw group (slides)

I wrote an article for Methods & Tools, titled Test Driven Development Traps

I got invited to the Program Committee of 4developers conference, where I helped a bit finding interesting speakers and choosing talks from Call For Papers

### 2011

*Winter go home, a gentle introduction to Spring Framework* - Given at Warsaw Java User Group

*Teamwork in software development* - A lecture for students at Faculty of Mathematics, Informatics and Mechanics, University of Warsaw

*Hack your company: what a developer can do, to get fun and money from learning* - A Birds of Feather session at 33rd Degree Conference in Krakow

*Spring Security & Spring Social: how to integrate Google and Facebook in a Java web application* - Given at Warsaw Java User Group

*Animating Developers* - Given at Agile Warsaw group

I was a trainer and organizer of Agile Development Day, one day open meeting for those who want to share their experience with Agile methods

## 2010

*Software Craftsmanship* - A workshops at Warsaw Design Patterns Study Group, and a talk at Warsaw Java User Group

*How to prevent code biodegradation* - Given at Javarsovia conference in Warsaw

I led a panel about team building and quality at COOLuary (unconference part of NYAC conference) in Krakow
