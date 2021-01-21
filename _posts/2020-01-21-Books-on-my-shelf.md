---
layout: post
title: Books on my shelf
---

After yesterday's talk (in PL: https://www.youtube.com/watch?v=AaGxEn8fGJY)  I got a lot of questions about IT books on architecture. I thought I’d make a list but there are such lists out there already from people with much more experience and reading much more than I do. Here is an example:
https://architectelevator.com/architecture/architect-bookshelf/

Considering my limited expertise in the matter (the percent of the books on the market I have read) I decided not to do a list, but instead to write a few words on the books I can recommend and the reasons why. You see, a good book is not something everyone should read, each has its intended target, and what works for me might not work for you. 

For example, Josh Long latest book “Reactive Spring” is a very well written book, but:

1. It’s not a book to learn reactive programming in Reactor from (Reactor docs are much more detailed and just as well written)
1. It’s not a book to learn hot to design reactive systems (that would be Reactive Design Patterns by Dr Roland Kuhn)
1. It’s a book for people who need an overview of how Spring ecosystem of libraries support reactive programming, without any prior knowledge. And it excels at that. But that’s a very specific group. 

It’s the same problem I had with “Cloud Native Java” by Josh Long and Kenny Bastani. The docs for each project mentioned there are a much better source of information, but you have to start somewhere, and if you have nothing to start with, this is an excellent book. Otherwise, you might be disappointed, because due to its nature, it skims over too many things without going into the details.

So instead of “a list of books you should read”, here’s my short list of books on architecture I can recommend and when

Reactive Design Patterns by Dr Roland Kuhn - when you want to understand what reactive systems are about, how to design them, and what options do you have. You will not, however, learn reactive programming from this book. Code samples are in Java and Scala, and 200 pages are just patterns, so this is not for someone starting in software development or design.

Designing Event-Driven Systems by Ben Stopford - when you want to learn how to design asynchronous distributed business oriented systems and what persistent event logs allow you to do. This book is for free, because it is sponsored by Confluent, the company behind Kafka. Due to that, all the examples focus on Kafka. Nonetheless, it’s a very good book even if you don’t use Kafka, because most (if not all) the patterns described there are usable in a wide variety of systems. They just may take a bit longer to implement. Also be careful, because it suggests you can use persistent event logs as an outside-in database, without explaining when you shouldn’t do it (watch the presentation “Event Sourcing You are doing it wrong” by David Schmitz https://www.youtube.com/watch?v=GzrZworHpIk)

Software Architecture for Developers by Simon Brown - This book is the first book you should probably read when you want to take the architecture seriously. This is the kind of book every university curriculum should include: it’s easy on the reader, it assumes no prior knowledge, and it sorts all the basics out. It’s safe for beginners, and often eye opening for people with 30+ years of experience, like the fact that you should be verbose about what you optimize your system for. This alone does miracles, and I’ve rarely seen systems where devs made conscious decisions based on that goal (and measured it). Hint: if you do not know what to choose, take maintainability, and make all decisions to lower that sucker down.
But it may also be boring, because it goes over all the basics, and there’s nothing tricky or complex in there.

This is getting long and I need to get back to work. So even though I told you there are much better sources of a recommendations, here’s a list of books on my “Architecture” shelf

1. Domain-Driven Design: The First 15 Years: Essays from the DDD Community
1. Thinking in Promises (Burgess)
1. Category Theory for Programmers (Milewski)
1. A Teal Doctrine of Quality: The case of Teal self-organization (Blikle)
1. Design It! From Programmer to Software Architect (Keeling)
1. Anti-fragile ICT Systems (Khole)

And because the hardest thing in software architecture is people this shelf includes:
1. Behave: The Biology of Humans at Our Best and Worst (Sapolsky)
1. The Brain: The Story of You (Eagleman)
1. On Intelligence (Hawkins)
1. Living Nonviolent Communication (Rosenberg)
1. Thinking: fast and slow (Kahneman)
1. The case against reality: why evolution hid the truth from our eyes (Hoffman)
1. Visual Intelligence (Hoffman) - that was a bitch to find
1. The Psychopath Code - Cracking The Predators That Stalk Us (Hintjens)
1. Culture & Empire - Digital Revolution (Hintjens)

And of course the old but golden (which means I use them often to get a nice quotation for a slide):
1. Domain-Driven Design: Tackling Complexity in the Heart of Software (Eric Evans)
1. Implementing Domain Driven Design (Vernon)
1. Extreme Programming Explained (Beck, Andres)
1. Peopleware (DeMarco & Lister)
1. Test Driven Development (Beck)
1. Clean Architecture (Martin)
1. Continuous Delivery (Humble, Farley)
1. Management 3.0 (Apello) - yeah, sorry but that matters