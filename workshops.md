---
layout: page
title: Workshops
permalink: /workshops/
---

I have given commercial workshops for developers since 2012, most of them via [Bottega IT Minds](https://bottega.com.pl/). 

My focus is on Software Architecture, Test/Behavior Driven Development, Domain Driven Design, Spring, Reactive Programming and craftsmanship.

With 98 commercial workshops so far, 1-5 days long, on-line and on-site in Europe, Africa and Asia, plus another dozen for free, I feel I cannot call it a hobby anymore. Let's call it "my side project".

Below you'll find details of some of them. All available in English and Polish.

--------

## Designing architecture for modular, distributed, and event driven systems; a pragmatic approach

Duration: 3 days. Description available also [in Polish](https://bottega.com.pl/szkolenie-projektowanie-systemow-modularnych-i-rozproszonych)

This workshop teaches a sane and practical approach to architecture of three popular classes of systems: a modular monolith, a distributed synchronous system, and a distributed asynchronous system driven by events. 

You'll learn how to approach architecture, what drives it, what you need to consider to get it right (including team dynamics), which style solves which problems better, how to visualize your architecture, how to verify it, what tools to use, and finally you'll learn heuristics to use when designing modules & microservices.

I'll give a lot of real life examples, you will design a system in 3 different flavors, and we will review those designs in detail, fixing all the problems as we go.

While the workshop is programming language agnostic (doesn't matter if you are on .NET, JVM, PHP or Perl), it is not technology agnostic. We will design assuming a public cloud (i.e.: with kubernetes), Apache Kafka as a message bus and persistent transaction log, and different database choices.

### Synopsis

How to organize architecture in the company. What all those "solution", "software", "enterprise" really mean in the architect position description. How to work with different teams, depending on their maturity level.

Tools and notations: C4 Model, Sequence diagrams, diagram as code.

How do we verify the architecture. ArchUnit. Consumer Driven Contracts

What drives architecture, and what can you optimize for. What are the consequences of each optimization. How to calculte SLA, availability, maintenability, flexibility etc. Trade-offs.

How to design a modular monolith. What are modules. What are the benfits and when you should never use it. How to deal with high risk of deployment. How to change your thinking about modules (moving from data oriented to process oriented). Large exercise in design.

How to design a synchronous, distributed system, a.k.a microservices. How do we test distributed systems in practice. How to deal with networking disefficiences. Communication and control: Orchestration versus Choreography. Why Saga is just both a pattern and an antipattern. How to use it the right way. How do we deal with errors. How to provide performance. Data locality and read models. How to optimize for high SLA, and what does SLA even mean in a distributed system. Typical errors in designing such systems.

How to design an Event Driven system. What are the 3 different types of messages you can send. How do process streams, ensure ordering, deal with multiple consumers and producers. How Kafka works internally, and what a persistent transaction log allows us to easily design. Topics, partitions, consumer groups, compacted topics and read models, transactional publishing. When should we use all of that, and when a synchronous communication makes more sense. Typical errors in desigin such systems.

Finally, how large heterogeneous systems work in real life, and which style is the best when.

--------

## Well designed applications in Spring framework

Duration: 3 days.

This is a zero-to-hero type of a workshop: no prior knowledge of Spring framework required.

In this workshop I teach the best practices of working with Spring framework, while at the same time explaining all the core features. This workshop is designed not only to show you how to do things, but how you should approach development with Spring to build easy to maintain software, and what features you should avoid.

Together we will build a modular app, using Test & Behavior Driven Development (with Spock), hexagonal architecture and make the process easy using all the best practices. Examples are in Java, Groovy and Kotlin.

I will cover:

### Boot & Core
1. What is Spring Boot, how it works.
1. Boot events and bootstrap
1. Setting up and autoconfiguration
1. Tuning autoconfiguration
1. Component scan gotchas
1. Ways Dependency Injection works in Spring: JavaConfig vs @Autwired vs Functional configuration (including examples in Kofu straight from production)
1. Ports&Adapters / Hexagonal Architecture
1. Properties, Profiles, Conditions
1. Spring Actuator: endpoints, security
1. Testing your app

### Spring MVC
1. How it works: Dispatcher, Request Mapping
1. Defining controllers: arguments & return values
1. Building URIs, RESTafaranism
1. Controller Advices, Handling Exceptions
1. Serving errors & static content
1. Locales, Session & Request scopes
1. Spring MVC testing
1. HATEOAS
1. Spring MVC vs Spring WebFlux

### Spring Data
1. What it is, how to use it
1. Repositories, fine tuning
1. Nested properties
1. Query creation anatomy & Native Query
1. Page, Slice, Sort
1. Custom logic in repository implementation
1. Default methods & additional logic in repository
1. Populating the database & bootstraping
1. Auditing
1. Criteria/Specification
1. Testcontainers and in-memory databases

### Spring Data JPA & transactions
1. Transaction management & attributes
1. Isolation & Propagation
1. Declarative Transactions
1. Manual Transactions
1. Patterns: where to start transaction
1. DDD Aggregates and JPA misconceptions
1. NoSQL + SQL, best of both worlds

### Spring AOP
1. Aspect Oriented Programming nomenclature
1. LoadTimeWeaving vs CompileTimeWeaving vs Proxy
1. practical usage with examples

--------

## Reactive programming with Project Reactor

Duration: 2 days.

Reactive programming is fun and efficient, but creates a lot of confusion at first, because you have to switch your way of thinking. In this workshop we look into why & how to use it. We will create a reactive application from the ground up and dig a bit deeper into how the concurrency works in here. Because changing the way of thinking is the crucial part here, most of this workshop is actual coding.

Synopsis:
0. Why we need reactive programming
1. Reactive theory: backpressure and JVM foundations
2. Landscape of libraries
3. The problem of not reactive http and solutions (reactor-netty, rsocket)
4. Basics of Mono/Flux
5. How to think about reactive programming (declaration versus execution, cold vs hot)
6. How to test reactive code
7. Reactive operations
8. How to handle synchronous resources (RDBMS, etc.) from reactive code
9. Webflux and full reactive stack
10. Advanced Reactor features
11. When NOT to use reactive programming
12. Communication via RSocket
13. R2DBC
14. Fibers (Project Loom) vs Reactor

--------

## Test & Behavior Driven Development

Duration: 2 or 3 days.

This is a hands-on workshop for developers and QAs on how to build systems using Test & Behavior Driven Development. You will also learn Hexagonal Architecture, a bit on modularity and a lot on working with requirements. We will use the Spock test framework, but all the knowledge is ready to apply in all the other frameworks and languages.

Synopsis:
1. what are the alternative methods to TDD & BDD
1. what types of tools we can use
1. how to work with requirements, use cases, user stories, define acceptance scenarios, behavioral scenarios, think about corner cases
1. how to design test cases
1. an anatomy of a test, and best practices
1. setting the system up in unit and integration test, cleaning up afterwards
1. mocking, stubbing and spying
1. how to work with databases using testcontainers, in memory DBs, dedicated DBs, how some people test with a production copy and why you shouldn't
1. how to organize test, how to keep them clean and maintainable 
1. the power of Domain Specific Languages, and how to use them to make complex scenarios obvious and easy
1. what is the role of QA in most agile teams using TDD/BDD
