---
title: "Your 3 am problem was engineered six months ago"
description: "Incidents are bills coming due; contain first, then fund the fixes before the next pager."
date: 2025-04-15
---

I used to think the worst part of a 3 am page was the alarm. I was wrong. The worst part is trying to rebuild a mental map of a complex system while half-awake. When a system fails at scale, you are almost never fighting a new bug. You are fighting a decision someone made months ago.

Some years ago, a data misconfiguration took down our primary service. The fix was straightforward: a single configuration change. But at 3 am, with customers locked out and the incident channel filling with messages, the technical fix was the easy part. The hard part was managing the room.

I am on a rotation of incident commanders and have held similar roles across companies. Not every organization trains people to run the room when things break. Responders join a crisis call with adrenaline and a deep need to be useful. My job is not to solve the problem faster; it is to stop ten smart people from solving it ten different ways. Breathe. Open the runbook. Focus on containment, not root cause. We will discuss what went wrong when everyone has slept.

No one wants to hear this. Everyone wants to be the person who spotted the real issue, who pushed the clever fix, who saved the day. But any line of code written under 3 am pressure is guaranteed to introduce a new, fascinating bug that we will discover next week. Our job is to stick to the pre-approved list of actions wherever possible, no matter how boring that feels.

The other thing I am managing, the thing I cannot say out loud on the incident call: I know exactly why this happened. Six months ago, we chose the quick implementation over the robust one. We knew the trade-offs. We told ourselves we would come back and fix it properly later. This incident is just the bill coming due, with compound interest and a wake-up call.

Once the system stabilizes, everyone wants to move on. The fire is out, let's go ship features. This is where most organizations fail. The pressure to return to normal is immense. Product wants their roadmap back. Leadership wants to announce the all-clear. The people who just spent four hours on a bridge call want to sleep and forget this ever happened.

But the incident itself is just expensive theater until the real work starts in the retrospective, when we are rested and no longer running on adrenaline. We document not just what broke, but what we knew might break and built anyway. We update the runbooks with the specific things we learned at 3 am that we never want to learn again. We turn the late-night panic into next quarter's process.

This is unglamorous work. No one gets promoted for writing better runbooks. But the alternative is predictable: six months from now, someone else gets paged at 3 am to fight the same fire, because we were too busy shipping features to pay down the debt.

## Quantify the bill, then fund the fix

If you are leading a high-stakes environment, the goal is to make operational risk visible and quantifiable for the entire organization. Here are two actions that have worked for me:

**Quantify the systemic cost of failure, then fund the fix.** After our data misconfiguration incident, we calculated the real cost: 47 engineering hours across the incident and follow-up work, estimated customer impact from the four-hour outage, and roughly 15 percent of our weekly support ticket volume for the following month dealing with fallout. We used that total, a number large enough to make leadership uncomfortable, to justify dedicating two engineers for several sprints to fix the configuration system properly. For your next post-incident review, dedicate time to calculate the full cost of the outage: engineering hours spent, lost opportunity cost, and the estimated loss of customer trust. Use that number to justify allocating a percentage of your next feature budget to improve the failure modes of the service that broke. This transforms maintenance or KTLO into a risk mitigation investment.

**Systematize the hard reset conversation.** Identify one legacy dependency or architectural choice that is demonstrably adding friction to development or reliability. Begin a formal, business-aligned process to sunset it. This requires quantifying the capacity gain you will realize when that friction is gone. The highest return comes from removing the single biggest piece of architecture that makes everything else harder, freeing up capacity across the organization.

Mature organizations are not defined by uptime; they are defined by the week after an incident and whether the next engineer paged at 3 am finds a runbook that actually helps.
