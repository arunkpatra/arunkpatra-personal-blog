---
title: "Choosing a Public Cloud Platform"
description: "What questions to ask while choosing a cloud platform?"
date: 2020-06-08
draft: false
toc: false
images:
author: Arun Patra
categories:
  - technology
tags: 
  - technology
  - cloud
---

## Do I know why and if I need Cloud?

I recently heard a statement from someone in the IT industry saying "We got to do cloud, cloud is everything". 
When probed why, the answer came in - "Arun, you need to update yourself. Don't you know that everybody has adopted it 
and didn't you see the hype curve?". I repeated politely, "Still my question". Pat came the answer, "Please talk to the 
engineering team". I walked away muttering, "Okay, I think I know what you mean".

I would think, that unless I understand fully my workload and what type of services those workloads need, and what pain 
I would be solving by using PaaS or IaaS, I am not ready yet to make a decision - I am just not qualified yet! I also 
need to know what are my scalability, availability and reliability needs. If I do not understand these terms, I am not 
qualified to make my decision - the decision would most likely be a bad one. I also need to think from the perspective 
of operations and monitoring, logging, continuous deployment, rolling updates and painless rollbacks. If I do not 
understand these terms and don't yet understand as how far these aspects go towards total cost of ownership and 
business agility, I would most probably be digging a grave for myself by making a wrong decision. In essence, I must 
ask all the right questions. The answers are only meaningful if the questions are relevant and contextual to my 
workloads, for now and for the foreseeable shelf life of the software - not those questions and fancy terms that the 
cloud sales guys and marketing brochures listed. However, more often than not, brochures are an excellent source 
of great information to start with.

## What I need v/s what the cloud provider is selling?

Do I know what are the top three priorities for my application/system? In the sales pitch, the sales guy listed two 
dozen services and took all the contacts from me of my IT decision makers working with different technologies who are 
trying to solve different problems. His only goal was sales, sales and sales(and one should be totally fine with 
that - that's the primary job of the sales team after all). "But what about me? What about my developer who is facing 
some real issues - this service is just not fit for my needs, and the weekly status call is not helping much." This 
happened to me. There was another provider, whose sales guy told me this after seeing my demo - "Arun, honestly, you 
are using a very expensive service of ours and you can very easily meet your application needs by using a far cheaper 
and far simpler service, go ahead and try that." I said - "God bless you - you are a gentleman". Yet another provider 
asked me rather bluntly, "How tightly is your application coupled with our services?". Promptly I replied, 
"errr... actually my app is very tightly coupled with your services"... What I did not tell them, was "Please stop 
looking at me as if I am an imbecile, you are actually painting a very bad picture of yourself".

## How mature is the service again?

Is the service I am wanting to use GA or is it a beta/preview release which the cloud provider is essentially 
providing to use for free (BTW, there's nothing called a free lunch)? Such a provider is probably gathering very 
valuable usage data, error log data, crash reports from me to improve their own product - and they had mentioned 
this in the fine print, which you agreed to. However they probably don't worry much at the beta/preview stage as 
what pothole you hit by using a beta product(that's the very definition of beta?) - that can severely hurt developer 
morale sometimes though. Among the top public cloud providers, there is one who rarely releases any beta/preview 
service at all. They release a new service only when they are sure that it meets or exceeds the absolute best standards 
in the market - and they don't care whether a competitor launches a competing service before them. They don't care even 
if they don't have a ton of features to start with - they just care about that it should "just work" and the 
documentation is 100 percent updated/correct. For them customer obsession is the single most important thing. There 
is another cloud provider whose almost every single service starts life as a public beta(of course with the 
disclaimer/warning in all fairness). And personally speaking, sales folks from this provider have actively urged me 
to try out their beta, and sometimes going to the extent of saying that, the feature I am looking for is only available 
in the beta and that is the recommended technology to use/and the future as of now. This has left me with heartache 
and pain and substantially higher number of hours in office.

## What does it cost me - Pricing model please?

In the money making business, ethics sometimes might get overlooked or de-prioritized albeit temporarily, 
much driven by cut-throat competition - I think that's just unfair. For some however, ethics and integrity are 
sacrosanct. One provider's pricing model was designed in such a way, that whether I like it or not, a particular 
"size" of the service only allows "up to a certain max throughput". Beyond that, I need to switch to the next level 
manually myself. BTW, the sales guy did tell me I can do some form of automation to do that switch, for which the 
documentation was so archaic, obscure and outdated that it felt really helpless. There is another provider however, 
who sold one of their services with a pricing model that is simply based on total messages getting into the system. 
It's charged based on per millions of messages. Everything else and the heavy lifting and auto-scaling is internal to 
the service. If I needed to a particular max level of throughput in PROD, I just had to raise a simple request and they 
updated the limits, at the very same pricing model. Remember the service was priced on millions of messages and not the 
"hardware" tier I was using - BTW there was no such thing even as a hardware tier for this service with these guys. 
It was just plain and simple and I was able to move ahead confidently without the fear of avoidable cost overruns due 
to mis-configuration to a large extent.

## Business model and business ethics

One provider might sometimes take an approach of repackaging and rebranding a failed service. To the humble coder, 
it might appear, the provider deals with the poor uptake and the negative feedback by rebranding the service - 
probably without making any substantial change or even without fully addressing the existing issues - with a new 
UI perhaps. Another provider has rarely had the need to kill a service because it was designed with at least a ten 
year roadmap with lot of thought and foresight put into it. It started years ago, its adoption has only gone north 
and the feature set just becomes better with every release.

## I am a human, I commit mistakes

I am a human, I commit mistakes. Treat me like a human, I will thank you for that. I am also a customer, 
if you want my loyalty, you got to work towards it and not just get into a volume licensing agreement at an 
organizational level. There was one provider whose business/sales strategy appeared to be signing a deal at the 
topmost levels of the organization and not being worried too much at a project or program level - kind of one size 
fits all. Again there was another provider who actually waived off 16,000 USD when a developer's keys were stolen and 
a hacker spun up the most expensive VMs in all the regions in which the services were offered. This provider just 
asked me, to convince them that I have now put everything in place to ensure to mitigate such breaches in the future 
and have ensured the team is well-trained to avoid mishaps. Narrow escape, but they treated me as a human being.

## Conclusion

Folks, I think on one hand this world has day traders out there to make a quick buck(well again, that's what a day 
trader's job is, isn't it?). On the other hand there are the guys who are in here for the long run who's business 
model is customer obsession. Both of these two extremes and everyone in between is doing perfectly legal business 
and they are entitled to do business the way they want while following regulation in the countries where they sell 
their services. None of them is forcing you to sign the purchase order. It is up to us to ask the right questions, 
the questions that really matter to us, choose the right partners with high business standards, and make the right 
decisions - as if our life depends on it. Let's pledge we will do everything in our capacity to make our own lives 
easier and save money/time along the way, even if we have to debate with the largest corporations in the world.

Code and build with joy, do the right thing, choose smart, partner with the best, may the best guy win, do your part 
to weed out mediocrity, save money and save time for yourself and the planet.