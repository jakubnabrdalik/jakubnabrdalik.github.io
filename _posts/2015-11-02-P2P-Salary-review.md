---
layout: post
title: P2P salary review
---

How and why I have implemented a Peer-2-Peer salary review in a corporation: a case study.

## Goal: optimize for fairness

A CEO raised his company's minimum wage to £45,000 a year, and some employees quit because of it [link](https://www.businessinsider.com/dan-price-gravity-payments-employees-leave-2015-7?IR=T). Do you know why? Because the hard working, highly educated staff were pissed off that someone who slacks off all the time and had not invested much in their own development, earns the same money.

An interesting thing about salaries and having people happy, is that the absolute amounts are much less important than the relative fairness of the system. And that’s a bit counter-intuitive.

Imagine this: when hard times come, we have a war or an economic crisis, most people are fine with having to cope with those difficulties, when they know it’s a shared burden. On the other hand, they get angry very fast, when they see stupid, incompetent, corrupt people driving fancy cars and living in luxury villas.

Fairness is the most important aspect of a salary system. Fairness is what we should optimize for.

Bear in mind that your company is a part of a bigger system (the industry). Which means that no matter how fair you are, you cannot pay shit to your people. You have to be fair and competitive. Otherwise, the fairness of the larger system, also known as “getting a better job”, will bite your ass.

## Embrace your ignorance


It’s quite easy to evaluate the people you work with, when you have a team of up to 5 +/- 2. However, beyond the number of seven, you can only have a dim idea of how people are doing. One level deeper (49) and you have no chance at all.

When I became the Head of a 12 people branch, which I’ve grown to around 50, it’s been clear right from the start that I don’t want to be the person to evaluate everyone.
It would be unfair, logically invalid, and still take way too much of my time.

What other options did I have?

People are split into small, self-organized, interdisciplinary teams. You could give the power to evaluate people to one of the special roles, like a Team Leader, or a Product Owner, or a Scrum Master. However, both Scrum Master and Product Owner do not have enough technical knowledge to evaluate developers properly, they are biased towards soft-skills which is just half of the picture. The Team Leader is biased in the opposite direction. And going with either would still leave me with having to evaluate those “special” roles myself.

But the biggest problem is, that once you put the power of deciding about your money in the hands of another person, you will not treat the person the same way anymore. So my self-organized, coherent teams would gravitate towards a “Project Manager with his minions”.

That’s the old way of centralized, report & control, zero-trust, competition over cooperation, UK management style.

> “I’ve also noticed that different countries and cultures place different values on control. Some (e.g. the UK) value control and the restraint that it brings whereas others (e.g. Scandinavia) value empowerment and motivation.” [Software Architecture for Developers; Simon Brown; Leanpub 2014]

I don’t like that. It’s very ineffective.

### Client, market, and stakeholders

If not a Product Owner, not a Scrum Master, and definitely not a manager, who can do the evaluation? Who can verify whether people work hard, efficiently, whether they are competent and valuable?

Theoretically, our clients or the market could tell us that. We could analyze, whether people do bring us money, or bring us closer to our target. This however, can only work if the team can decide on what they work on, which business opportunities they are after. And even then, it would probably be unfair. You don’t want to punish people for taking risk, and failing. In this line of work, you want them to feel safe to innovate, fail and learn from it. At least as long as they do not put you out of the business.

If they wanted to risk the evaluation of the market, they would start their own companies.

I work in a corporation. Decisions about the products we work on are done at the Executive Committee level. Evaluating my developers based on whether ExCo ideas are profitable would be very unfair.

## P2P


That leaves us with only one option really. Peer-to-peer evaluation. We have a system, where everybody has some data and a bias, nobody has the full picture. Let’s get all the data together, and do some data mining on it!

Our constraints:

For an employee, the whole process can take up to 30min, but should stay below 15 most of the time. And that’s for evaluating ALL the employees. Otherwise, the cost is huge, since every single employee has to do it (and it’s boring).

On the manager side, gathering and analyzing all the data should not take longer than a day.

The system should not be hacked (and we do have some pretty smartass hackers in here), or should be hacked in a positive way

It would be cool if the system brought us more than just the money levels. It would be cool if the system told each of our guys, what they should do, in order to get more money next time. And that needs to be as specific as possible.

## Impact


Cool, we have constraints. Now what do we actually evaluate to be fair?

Hard work? This is not a treadmill. I don’t want my people to work hard. This is a software house. It’s creative work. I want them to work smart!

Results? What results? Results of a company. i.e.: money, brings us back to market evaluation, which is wrong. Results of the tasks taken by an individual, brings us back to hard work evaluation, I don’t want that. Perhaps dedication? That would make all the dedicated idiots very rich, but not help us much, so maybe that’s not the way?

How about evaluating IMPACT a given individual has on the company? Would that make sense? If we review the impact, and connect it with the money, the system should be fair.

You work hard every day to move us further? You learn at home as well, because you are passionate? And your code works in production? Perfect. Money for you, good sir!

You jerk off all day, but have brilliant ideas in the evening, that you implement in the morning, that solve a lot of problems for everyone and bring us closer to where we want to be? Why not, jerk off again, it’s fine with me. Just use the bathroom, please. And here, wipe your dick with those euros.

You are a genius, ego the size of a planet, you read all the books, you could move mountains with your infinite knowledge and expertise, you have a PhD on Agile Node.js Extreme Reactive microESB, but somehow you cannot really work with people and thus none of your solutions get into production? And you antagonize teams? People don’t want to work with you? Sorry, that’s no impact or even negative impact. No monies here.

Right, but measuring real impact is hard. And even more, could be unfair. This is a team sport, so your best people could get screwed by show stoppers, other poor people, business changes... you know, shit happens. Real impact, like the market evaluation, will feel unfair, when your best people get trashed by things they have no control of.

The problem here is also the solution. You should measure the potential impact (without show stoppers), and verify it against the real history (because your perception of potential feedback may be wrong), to find out, and work out, why the potential is not used in practice.

## Skillsets

How does one evaluate potential impact of others? In software development potential impact is based on someone’s skills. The better the skills, the more potential impact, though both are not equal (more on that later). So how do you measure skills in a timely and meaningful manner?

Fortunately, I’ve already solved that problem once. While hiring people in TouK company, by doing a full day pair-programming (a very good, though costly method), I came to the conclusion that to be able to make a salary recommendation, I want to to present new people by comparing them with existing ones, on 6 skill groups, which I find important in software development.

These groups are:

### Hard Programming Skills 

including: programming skills in relevant language, OOP/FP, frameworks, methods like XP, TDD, DDD etc.

### Hard DevOps Skills 

including: Linux administration, deployment/build pipelines, JVM/GC tuning, database tuning, etc.

### Communication 

How easy it is to communicate? Do you like cooperating with that person? Are you irritated by the guy? Does he/she read your mind?

### Understanding 

How fast can one understand new, complex stuff. How fast does one learn?

### Self-sufficiency 

Can one pretty much do anything about the software development, or does one need a lot of help and attention? Can I throw any problem at them and it will get resolved? This includes domain knowledge, broad set of skills, goal orientation, self-retrospection and adaptability.

### Focus & Motivation 

Some people can move mountains with their sheer will. They are self-driven and have intrinsic motivation. You just need to remove blockers and let them shine. Others are easily distracted, lack self-motivation or sense, constantly need pointing the direction, waste time on facebook, or in the worst case scenario, need a lot of control & reporting

It may surprise you that hard skills take only ⅓ of the evaluation. But my experience suggests that most developers can handle rocket science mentally if you give them enough time. The problem is, that a large number of them will drop due to a lack of focus, some due to digging themselves up in just one branch, and not being able to handle the rest (self-sufficiency), for some I cannot afford the amount of “enough time” (understanding) and a large portion of the rest will never be able to communicate their knowledge properly.

So yeah, sorry, but software development is not only about programming. At least when you have to work in a team. Programming is crucial, but it’s not enough alone.

But this is cool, because if you skip those 2 hard skills, you can also use the same groups to evaluate Product Owners and Scrum Masters. That makes the whole process easier.

## Round 1: Comparison

Human beings are bad at absolute values. We are good at comparison though. So my first iteration was to ask people to draw a line for each of the skillsets, and then start putting small stickers with people’s names, relatively to each other (bottom: worse, top: better). No absolute numbers whatsoever.

Since you do not work with everyone, you should only evaluate the people you feel you can. And only in the skillsets that you feel you can.

The outcome looks something like this.

![_config.yml]({{ site.baseurl }}/images/P2P-Salary-review/firstskillset.jpg)

Great, we have some data. Time to clean the noise.

## Round 2: Explanation and refinement

After that, I would take every single person to a one-on-one, and ask them to explain their picture to me. We would talk about the bottom and top 20%. About all the issues they have with other people (usually communication). I would ask them how the person evaluated could improve their situation. I would gather feedback.

Then I would do normalization and clustering, to [-2..+2]. Like this:

![_config.yml]({{ site.baseurl }}/images/P2P-Salary-review/secondskillset.jpg)


Manual normalization and clustering of data took me a lot of time even at 20 people, so this part doesn’t scale.

For the second time, I decided to put absolute values: 0 to 4, and use google forms to gather feedback. I was afraid that without continuous scale, people would have a lot of trouble with comparison. Turned out, I didn’t need to worry. These is IT crowd, they understand clusterization perfectly. Discrete numbers are totally fine.

I have also added a “Note” textbox under each skillset, so that people could write down their thoughts on top/bottom 20% themselves the moment they make the decision.

![_config.yml]({{ site.baseurl }}/images/P2P-Salary-review/googleforms.jpg)


The field “Who has similar skill...” is there to help people self-verify their feelings.

Still, I had a one-on-one meeting with everyone. A completely automated system could be easily hacked. A system where you have to explain yourself to a biological creature is much harder to break. And much more humane. So while my people did clusterization of data automatically, I did normalization and verification myself.

## Round 3: Analyzing data

So what do we end up with? Lots of numbers.

![_config.yml]({{ site.baseurl }}/images/P2P-Salary-review/excel.jpg)


Each column is a person. Each row describes level. Each cell represents number of votes for a given skill at a given level. The color is based on value, so you can easily spot high numbers.

A simple spreadsheet formula, and you have a number for each skillset for each person. You can even sum this up to a single number. A single number describing someone is very tempting. That represents how good the person is, right?

Not so fast.

While numbers are great, it’s the distribution that you should analyze. Why is this guy hated by everyone but 3 people (communication)? Who are those people? What is their work relation? Why are those 3 people also evaluated badly in this skillset? Why does the other guy have no estimates in Focus & Motivation? Is he acting? Is he passive-aggressive? How about this girl, so good at pretty much everything, except DevOps? Is she still running Windows at work?

I don’t know if it’s possible to automate this, but I wouldn’t even try. The distribution tells you stories. When you add additional verbal and written feedback, you get to understand the dynamics of your teams a bit better.

And you can always ask. If you want to dig deeper somewhere, you can. The beauty of this system is that you know where to dig. Understanding the situation plays a big role in normalization of the feedback.

## Impact != P2P skill review

Skills are the base for potential feedback. But how about that girl over there, that never bitches about the work, never panics, even in a dire situation, with a job that nobody wants, but that needs to be done, you will just hear a soft sigh, and she’ll get it done. It’s helpful. It’s calming. Her stoic attitude, her gentle voice, and behaviour gets all the hectic boys through the hard times. There is a lot of extra value in it.

But it doesn’t get evaluated in a P2P skills review.

That’s because Impact and P2P skills review, are not equal.

To make it simple, my formula for Impact is

*Impact = normalized peer-to-peer skill review + personal traits*

## Traits

Traits are simple. Traits can be both negative and positive. Let me give you some examples, you will get it in a second:

Positive:

- Performance/Security expertise we need once a year very much
- Public Relations (blogs/open source libs lure more good devs in)
- Assertiveness (helps keep quality while negotiating with the client)
- Iron Willpower (not braking mentally in any circumstances)

Negative:

- Submissiveness (can be dominated by the client, and fail due to that)
- Low Willpower (panic!)

You should be able to identify those yourself. Like in a good role playing game, traits define a character. I know a lot of great developers, what makes them stand out, are their interests and traits.

Traits modify the outcome of skill clustering. They usualy give cumulative +1, -1 to the final cluster the person is in.

## Applying salaries

Now back to the goal of optimizing salaries for fairness. We have clustered skills, modified by traits, that describe the potential impact a person has on the company. On the way, we have found a lot of interesting information about team dynamics, and we dug up all the not so obvious. After everything said and done, we have reduced the data to a single number (cluster). People in the same cluster have about the same impact. Time to apply money to this.

The problem in many corporations is that salaries are not public. At least not officialy. This is a very stupid leftover from the previous era, when an employeer wanted to pay as little as possible to his employees. But it makes no sense? Why would I, as an employeer, want to pay as little as possible? The goal of the employeer is to make as much money as possible, if I have to pay more, to get more, it makes perfect sense. So paying less to the people makes no sense. Finding the sweet spot, when the money that people make gives the highest benefit, that makes sense.

Some will argue, that money is not a motivator, after certain amount. True, that Notch (the author of minecraft) with all his billions of euros, doesn’t seem to care about another million. But Notch is not a standard employee, and people who say money is not a motivator, usually have a lot already. Looking at the market of developers though, most of them are also motivated with money. It’s not the only factor, but it’s important enough, to make them change their jobs, but the amount that would make them not care about money anymore, is never reached throughout their lifetimes. Anybody with kids can tell you that, whatever you think is enough, will probably be wrong.

So what can we do in a corporation, where we are not allowed to publish salaries?

While we cannot publish salaries, we can publish anchor points. Lots of job comparison sites (nofluffjobs.com for example) require a salary range. If your clustering ended up with 5 different clusters, you can probably come up with some names for those levels (junior/mid/senior developer, architect, senior architect, principal senior executive architect, etc.). Now all you need to do, is publish those job offers, with the money (either as a salary range or fixed), and people can compare their own situation to the whole picture.

Make a strong commitment, to always keep salaries together linked with job titles and linked with the potential impact. Promise to keep it fair for the people. And now, because titles are public, everybody knows what the salary of everyone else is.

More or less. More if you have only one number for a cluster, less if it’s a range. Still, people will be able to see the whole picture, and tell you if they think it’s fair.

To make the commitment strong, I had to fire someone, who had much more money than their position (he was a much better negotiator than an employee), and rise the salaries for all the bad negotiators. If negotiation skills are valuable to you, make them another skill group, or add them to Traits.

## Benefits

There are good things and bad things about this system. First the good things.

I don’t have to be the judge. I don’t have to play an omnipotent being. It changes our cooperation a lot, the moment people realize, they don’t need to make a good impression on me. It makes them more open.

People don’t need to convince me, when they need more money. They have to convince their peers. This means we can have a honest discussion about what to improve, how to make their potential impact into the real one, or how to increase their skills. Or the perception of their skills in other people. When someone thinks he has much higher skills than other poeple think, it’s usually about the problem with communication. Or ego. It’s something you can work on. Though egos are hard to fix. But even then, you have hard data.

If it's a problem with communication, it's no more "my boss doesn't like me". Now it's "have a look, all your peers say you are bad at communication". You cannot ignore all the people. You even cannot get angry at all the people. You finally have to understand that the problem is on your side.

It takes 15 min per developer, and 1 day per manager. On average, because it varies with how much digging up you have to do.

After investigation it gives you tons of feedback, which you can give back to people. And people want that feedback. I’ve been doing it every half a year, because we had a salary review in corpo in summer, and then a bonus review in the winter. People asked me to do it more often, even knowing that I won’t change anything about the money, because they wanted to get the feedback. More feedback is better.

And it can be used for Devs, POs, SMs, QAs, System Engineers… Basically everyone who has peers.

## Caveats

Beware, there are some obvious downsides.

Peer-to-peer review doesn’t work for people, who work alone. It also doesn’t work well if your teams never mix, and stay in the same setup for years. You will soon find out, that people can review only their team members. But if you have a medium sized company, and people do not cooperate too much between teams, do not share their knowledge, perhaps you have a completely different problem to solve?

It’s tempting to dehumanize (turn people into numbers) fast. Don’t do that. Let the distribution tell you stories, and dig into it. Otherwise, your system will be unfair, and unfair systems get hacked much faster. Social justice, I guess.

You cannot compare salaries between different roles (QA/dev/PO) due to different market levels. This doesn’t sound bad, but since you have promised to be fair, what happens if someone changes his position from a better paid role to less paid? Scrum Master to PO, for example? Small problem if the person can still do their old duties (potential impact is still high), but if they can’t?

Or how about someone who learns nothing for a few years? In a fast changing world of software development, skills deteriorate fast. Since the salary can never get lower, and the majority of people who still work on their skills will rise the new base (average), the same salary for years may become more and more unfair.

Sometimes, due to fairness of the system, you will have to fire someone, who otherwise does his/her job.

It’s also hard to explain to non IT people (CEO, HR) that someone can make an improvement of +40% in a year. They may not like to give such a salary rise. But it happens in IT. Well, at least you now have some hard data on it.

Another mistake I made, was giving not enough anchor points. I've published two salary ranges (mid and senior), because it was very difficult to get my corpo to agree on anything oficially. At that time, I had 5 clusters from P2P review. Some people who just got promoted or hired to senior level, expected to get the top range of this position, while the truth was, 70% of seniors were at the beginning of this salary range. My clusters and published anchor points were not one-to-one, and that was confusing to people. Fortunately, people trusted me enough for this to not be a problem. I just had to do some explaining.

But all of that is nothing, compared to the biggest benefit of P2P salary reviews.

And the biggest benefit is: I had this system running for two years and people liked it.

At least that was the overwhelming feedback that I got. And that makes me happy.