---
title: "So your sales team just sold something you can't build"
description: "When a deal promises the impossible, replace anger or heroics with facts, options, and governance."
date: 2025-02-05
---

It usually starts with a Slack message: "Quick sync! New customer signed! They need real-time eligibility verification by next month. Congrats everyone!"

Your stomach drops because you know "real-time" does not exist in your current architecture. You have a flaky overnight batch process, poorly documented by a three-year old confluence page someone who has now left the company created as a draft. You told them it would take six months to build the real thing. They sold it anyway. I have been in this situation at least six times that I can think of across three companies. I got it wrong four out of those six times: burned out teams, shipped brittle systems, or still missed the promise.

Here are a few thoughts on what I have learnt. 

## Get the facts in writing

Before any technical planning, establish exactly what was promised: contract or SOW, proposal or RFP response, demo recordings, email trail. In healthcare in particular, "real-time" can mean "24 hours," "15 minutes," or "sub-second" depending on who you talk to. Figure out what you are actually on the hook for.

## Be honest with yourself

Can you deliver what was promised?

1. Yes, fully (rare; just do it).
2. Yes, but with unacceptable technical debt (you will pay for years).
3. Partially, with clear tradeoffs (valuable, but not everything).
4. No, not in the timeframe (possible, but not in weeks).
5. No, not with current architecture (needs foundations you do not have).
6. No, not ever (violates physics, regulation, or dependencies you do not control).

The biggest danger is pretending #5 is #3. I did that twice. We burned months, burned people, and still missed the commitment or lost credibility.

## Offer options, not ultimatums

Walking in with "we cannot build what you sold" makes you the blocker. Instead, develop 3-4 options with clear tradeoffs:

- **Option A:** Deliver exactly what was promised. Timeline: 6 months. Cost: 4 engineers full-time; delays roadmap by 2 quarters. Customer impact: everything promised, delayed launch.
- **Option B:** Deliver 80% in the promised timeframe. Timeline: 2 months. Tradeoff: batch processing (4 hours, not 2 seconds), manual edge-case review. Customer impact: core use case works; some workflows need adjustment.
- **Option C:** MVP now, full later. Timeline: Phase 1 in 2 months; Phase 2 in 4 more. Tradeoff: customer adopts in stages. Customer impact: quick start, full capabilities later.
- **Option D:** Renegotiate. Go back to the customer with an honest assessment and revise the contract. Risk: customer might walk. Impact: honest conversation about what is possible.

Frame it as: "Here is what was promised. Here is what is possible. Here are our options. What matters most: timeline, completeness, or quality?"

## Bring data to the conversation

The people who need to be there are the person who made the commitment, engineering leadership with authority to commit resources, product leadership for roadmap tradeoffs, and customer success to manage the relationship. Do not do this in Slack or email. Bring the commitment docs, your technical assessment, the options with tradeoffs, and your recommendation.

## Negotiate within reality

Things you can negotiate: timeline, feature completeness, resource allocation, scope of MVP. Things you cannot negotiate: technical feasibility, safety or compliance, team health (no 80-hour weeks for months), debt that will cripple you later.

You will likely be under pressure from your leadership, but stick to what is possible: "If we promise something impossible and fail, we lose the customer anyway and we burn out the team. Let me show you what we can deliver."

## Fix the process so it stops happening

Once you navigate the immediate crisis, fix the system:

1. **Technical review before contracts:** Engineering reviews commitments before they go into contracts, with authority to flag risks.
2. **Sales training on boundaries:** Practical training on what the product can and cannot do; when to involve engineering.
3. **Standard contract language:** Define "real-time," include phased delivery schedules and success criteria, and a change-control process.
4. **Blameless retrospective:** How did this get sold without technical input? What incentives drove it? Document and propose process changes.

Overselling stops when the incentives and the process change. Until then, lead with facts, options, and a refusal to pretend the impossible is feasible on a whim.
