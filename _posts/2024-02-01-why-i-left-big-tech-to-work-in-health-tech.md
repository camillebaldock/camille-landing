---
title: "Why I left big tech for health tech"
description: "From personal crisis to confronting the mess of US healthcare's incentives."
date: 2024-02-01
---

I didn't plan to become obsessed with the American healthcare system. I was perfectly happy building scalable systems at big tech companies, solving fun distributed systems problems that make engineers geek out at conferences.

Then my kid got sick.

Not catastrophically, thank god. But bad enough that we needed multiple specialists and so overnight I became a parent trying to navigate the spectacular absurdity of the US healthcare system.

I can't point to one single thing that broke me, but slowly and surely it happened. It started out with the indignities of having to navigate what counts as 'good' software. I opened nine free trials for online fax services because that's apparently how you authorize medical record transfers in 2024. I paid $47 to overnight a CD-ROM to myself, just to drive it to a specialist because systems "couldn't talk to each other". I had a prepared printout of my kid's full medical history summary, customized per specialist, that I bought to every visit because it sure as hell was better than whatever their EHR could tell them. 

This was all happening in major hospital systems in Massachusetts and California, both claiming to use "modern" electronic health records. Both had spent millions on their IT infrastructure. I've built systems that process billions of events per day. I've designed data pipelines that sync across multiple continents in seconds. And here I was, opening my ninth free fax trial, functioning as physical middleware between two systems that were supposedly interoperable.

Then there was the billing nightmare. Random amounts would arrive via email and paper mail, sometimes both for the same service. A $347 bill for a lab test. Then two weeks later, an adjusted bill for $223 for the same test. Then an explanation of benefits saying I owed $53. Then another bill for $223 again.

Hours went to billing calls where the provider said "ask insurance" and insurance said "ask the provider." No one had the whole picture. I had all the bills, all the EOBs, all the payment confirmations, and I still couldn't reconcile them. We had "good" insurance through a tech company. This was the "good" experience.

I think what really lit a fire within me is when I realized we were not some weird exception. I met other families in waiting rooms dealing with the same chaos, just with fewer resources to absorb it. Parents who'd taken time off work they couldn't afford to take, navigating eligibility processes to government programs or charity care that seemed at best disorganized, at worst diabolical. Families trying to navigate the same fragmented care and billing nightmare while working jobs that didn't give them the flexibility to spend hours on hold.

My fury became real when I started studying more deeply what was going on and trying to follow the money. Finding high level information was very easy, but the more I dug, the murkier it got and the more mysterious things seemed. And I learned that where there is mystery, there is profit. Most of the money wasn't going to actual care, but to the administrative labyrinth. The prior authorization process. The claims disputes. The coordination failures. The redundant tests because records didn't transfer. The emergency room visits that could have been prevented if the primary care doctor had access to the specialist's notes.

Insurers profit from friction. EHR vendors profit from lock-in. PBMs profit from rebate opacity. Hospitals profit from volume, not outcomes. Everyone optimizes locally; patients get crushed globally. We spend roughly $12,500 per person on healthcare in this country that I am proud to call my home, double what peer nations spend. We are not paying for better medicine; we are paying for administrative friction.

The US healthcare system isn't broken because the technical problems are hard. It's broken because the incentive structures are misaligned at every level, and the technology has been designed to reinforce those misalignments. Every technical decision is downstream of business models that benefit from friction. Patient portals instead of true interoperability. AI on top of garbage data that doesn't match across systems.

I'm working in health tech now because I can't not work on this. I don't have a master plan. I don't have all the answers, but I am trying to educate myself and surround myself by people who care about those problems as well. I'm trying to meet people who see the same problems and refuse to accept that they're unsolvable. Engineers who've built serious systems in other domains and can't unsee the dysfunction. Clinical leaders who are tired of fighting broken tools. Policy people who understand that technology and incentives are inseparable. Patients and families who've lived this nightmare and know exactly what needs to change.

Fixing this needs everyone. The incentives are entrenched, the problems are massive, but we have to start somewhere. We have built harder things. The question is whether we will build infrastructure that challenges the incentive structures instead of reinforcing them. If you're working on this and want to connect, reach out. This is too big to solve alone, and too important not to try.
