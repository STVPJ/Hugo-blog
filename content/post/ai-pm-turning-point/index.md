---
title: "🤖 Product Management at the AI Turning Point: Why the Next Age Demands a New Role"
description: "AI won’t just change our products, it will change what ‘work’ is. Drawing on Carlota Perez, Mik Kersten, Paweł Huryn, Miqdad Jaffer, Marty Cagan and others, here’s how Product Managers must adapt."
author: "Steve James"
date: 2025-09-28
tags: ["AI", "Product Management", "Technological Revolutions", "Carlota Perez", "Mik Kersten", "Pawel Huryn", "Miqdad Jaffer"]
categories: ["Product Strategy", "Artificial Intelligence"]
draft: false
image: "header.png"
comments: true
---

## Intro

Every few decades, the world crosses a **turning point**, a moment when old paradigms no longer work and entire industries, organisational models, and roles are upended. In *Technological Revolutions and Financial Capital*, Carlota Perez maps how each major innovation wave (steam, railways, electricity, mass production, information) passes through an **Installation Period**, then a crisis-ridden **Turning Point**, and finally a **Deployment Period** when the new paradigm becomes the operating system of the economy. Companies that reorganise around the new paradigm survive, those that cling to the old rules fade. [Buy Perez (Amazon UK)](https://www.amazon.co.uk/Technological-Revolutions-Financial-Capital-Dynamics/dp/1843763311)

Mik Kersten’s *Project to Product* extends this lens to modern software and beyond. He argues that at the turning point, organisations must rethink how they create value, not by adding a tool or two, but by overhauling how work is organised, funded, and measured. As he summarises (paraphrased), at the turning point, businesses either master the new means of production or become relics of the last age. [Buy Kersten (Amazon UK)](https://www.amazon.co.uk/Project-Product-Networks-Transform-Business/dp/1942788398)

It’s not surprising then that this is dominating conversation. A quick Google search for “Product Management and AI” returns tens of thousands of results across blogs, newsletters, and LinkedIn posts. The sheer volume of writing on the subject is a signal that product leaders everywhere are grappling with the implications of this paradigm shift, wondering what parts of their role will endure and which will be automated away.

**This post argues** we’re living through such a turning point with AI. But unlike prior shifts, AI targets **cognitive work itself**. That means Product Managers (PMs) can’t just adopt “a framework”, they must operate at a new altitude, because AI will swallow many junior-level tasks. Drawing on Perez, Kersten, Paweł Huryn & Miqdad Jaffer’s *AI PRD*, plus Marty Cagan, Lenny Rachitsky and others, here’s a practical, grounded take on the new PM role.

---

## 1) Turning points mean overhaul, not tweaks

Perez shows each revolution reconfigures the economy’s rules: capital flows, institutions, and the organisation of production all change. Companies that handled electricity like “just a new machine” lost to those that redesigned factories, supply chains, and skills for continuous, scalable power. The lesson carries forward: **you don’t “install” a revolution, you rebuild around it.**

Carlota Pérez puts it starkly:  
> “Societies are profoundly shaken and shaped by each technological revolution and, in turn, the technological potential is shaped and steered as a result of intense social, political and ideological confrontations and compromises.” — Carlota Pérez  

This is the scale of what we face with AI. It is not a feature set, it is a societal shift that will demand structural responses.

---

## 2) Why the AI turning point is different

In prior ages, machines replaced muscle, digitisation replaced paper, and software scaled logic. AI now automates and scales **analysis, drafting, synthesis, and decision support**. The consequences:

- **Human-centred responsibilities become automatable.** Research synthesis, competitive scans, early wireframes and copy, call triage, contract pre-review, first-line support, large chunks can be handled by AI agents.  
- **Barriers to entry collapse.** Small, AI-augmented teams can rival large incumbents on output speed and variety.  
- **Feedback loops compress.** AI cycles through ideate, build, measure faster, enabling “learn before launch” and rapid iteration.  

Marty Cagan has noted the magnitude of this shift:  
> “What makes this discussion so hard is that almost every day things are changing … AI is a goldmine of opportunity. It’s also the biggest threat to how we do products.” — Marty Cagan  

Paweł Huryn, in collaboration with Miqdad Jaffer (Product Lead @ OpenAI), cautions that most failures come from **treating AI like a bolt-on feature** rather than a system requiring new alignment, risk thinking and evaluation. Their widely shared **AI PRD Template** forces teams to consider business case, failure modes (for example hallucinations), and guardrails up front, because skipping AI-specific considerations is exactly how teams ship clever demos that don’t survive contact with reality.

> “Given the hype around AI, many implement AI without a clear, justified business case… AI-specific considerations are often overlooked.” — *Product Compass (AI PRD, Huryn & Jaffer)*

Read it here: [AI PRD Template — Product Compass](https://www.productcompass.pm/p/ai-prd-template)

---

## 3) What changes for Product Managers (and why junior tasks vanish)

For years, junior PMs climbed by doing **repeatable, tactical** work:

- Writing user stories and acceptance criteria  
- Summarising interviews and clustering insights  
- Competitive analysis and teardown decks  
- Drafting copy and low-fi wireframes  
- Pulling analytics and building dashboards

AI agents can already handle large portions of this. Huryn and Jaffer both emphasise *AI literacy* and *AI intuition* as the new baseline: understanding probabilistic behaviour, non-determinism, error analysis, and how to iterate prompts, retrieval and context.

Marty Cagan captures the enduring essence of PM work:  
> “The most important thing to remember about product management is that it’s not your job to make things happen, it’s your job to make sure things happen.” — Marty Cagan  

This distinction is even sharper in the AI era. PMs must orchestrate, align, and decide, not write all the tickets themselves.

Lenny Rachitsky echoes this: AI will automate some PM activities, while amplifying others (influence, judgement, storytelling, prioritisation). PMs are **well positioned** if they move up-stack to what cannot be automated: [Why PMs Are Best Positioned to Thrive in the AI Era](https://www.lennysnewsletter.com/p/why-pms-are-best-positioned-to-thrive)

---

## 4) A possible playbook to adapt (now)

Turning theory into practice requires Product Managers to rethink *how* they do their day-to-day work. The skills below are not “optional extras”, they are becoming the baseline. Here’s how each can be approached differently in the age of AI, with examples of what this might look like.

### Build AI literacy and “AI product sense”

You don’t need to become a data scientist, but you do need to understand how AI systems behave in practice. Concepts like **embeddings**, **retrieval-augmented generation (RAG)**, **fine-tuning**, **hallucination**, and **model drift** should feel as familiar to you as “MVP” or “retention curve”. Without this fluency, it’s difficult to make credible product decisions or challenge technical trade-offs.

**Example:** Instead of just accepting an engineering estimate, a PM could prototype a feature themselves using a no-code tool like LangChain or a custom GPT. This hands-on experiment helps them understand whether the model reliably returns accurate results. They can then have an informed discussion with engineering about latency, cost per API call, and what failure handling will look like.

---

### Use AI-augmented discovery (but validate with people)

Discovery is still about learning what customers need, but AI lets you accelerate early steps. Large language models can cluster survey responses, identify patterns in support tickets, and even suggest unmet needs. But this is a *starting point*, not a substitute for talking to customers.

**Example:** Imagine you receive 1,000 pieces of open-text feedback from beta users. Instead of reading them all, you feed them into an AI model to generate clusters: “speed issues”, “confusing navigation”, “missing integrations”. The PM then validates those categories by calling five users in each cluster to ask: *“Tell me more about when this slows you down.”* AI accelerates pattern recognition, humans still validate what matters most.

---

### Redesign metrics for outcomes, not outputs

Traditional product metrics, velocity, number of tickets closed, or features shipped, are less meaningful when AI can generate outputs instantly. Instead, focus on **outcomes**: do customers *trust* the AI? Are they *retaining*? Do they *get value faster*?

**Example:** A team launches an AI-powered writing assistant. Instead of reporting “we shipped 12 features”, the PM tracks **Time to Value (TTV)**, how quickly a new user produces their *first useful draft*. If TTV drops from 20 minutes to 3 minutes after redesigning onboarding, that’s evidence the AI is working. Similarly, tracking **Time to Learn (TTL)** (for example how fast the team can validate whether a new prompt-engineering change reduces hallucinations) becomes central to iteration speed.

---

### Treat safety, ethics and explainability as product requirements

AI systems behave probabilistically, they can and will fail in unexpected ways. If PMs ignore ethical risks, bias, or explainability, they risk reputational damage or regulatory pushback. Treat these as *first-class features* in your roadmap, not afterthoughts.

**Example:** A PM working on an AI-powered recruitment tool might add a requirement: *“The system must provide a plain-language rationale for why a candidate was shortlisted.”* This could take the form of an “explain” button showing which parts of the CV matched the role description. Rather than being an extra feature, explainability is part of the core product requirement, because trust is the product.

---

### Lead operating-model change (not just roadmaps)

AI is not just a product feature, it changes how organisations must work. PMs need to step into a leadership role, helping decide how teams are structured, how budgets are allocated, and where human oversight is required.

**Example:** At a SaaS company, a PM notices multiple teams are experimenting with their own AI chatbots, duplicating work. Instead of letting each team go their own way, the PM champions the creation of a **shared AI platform team**. This avoids duplicated infrastructure costs and ensures consistent guardrails for safety. In doing so, the PM is not just managing a feature, they are helping re-architect the operating model.

---

### Become the narrative architect

With AI products, much of the PM’s influence comes from explaining *why this AI matters*, *how it works*, and *what guardrails are in place*. Engineers, executives, sales, and customers all need confidence. A good PM turns technical complexity into a story people can rally around.

**Example:** A PM launching an AI-powered financial advisor doesn’t just say “it uses GPT-4 for recommendations”. Instead, they frame it as: *“Our AI helps you make decisions in seconds that used to take hours. It suggests options but always gives you the source so you can double-check. Think of it as a co-pilot, not a replacement for your judgement.”* This framing reassures compliance teams, inspires marketing, and sets realistic customer expectations.

---

## Final Thoughts

Perez and Kersten remind us that turning points don’t reward half-measures. You can’t “install” a technological revolution, you **rebuild around it**. AI isn’t just another wave inside the Age of Software, it’s a fundamental shift in **how cognitive work is done**. That means roles, operating models, and industries are up for renegotiation.

For Product Managers, the implication is clear:

- The tactical ladder is disappearing as AI handles junior-level tasks.  
- The new job is judgement, orchestration, ethics, metrics, and organisational change.  
- The winners won’t be the teams that “adopt a framework”, but the ones that **overhaul how they operate**, anchored in outcomes and trust.

The turning point is here. **Adapt now, or be reshaped by the next age.**

---

## References & Further Reading

- [Mik Kersten, *Project to Product* (Amazon UK)](https://www.amazon.co.uk/Project-Product-Networks-Transform-Business/dp/1942788398)  
- [Carlota Perez, *Technological Revolutions and Financial Capital* (Amazon UK)](https://www.amazon.co.uk/Technological-Revolutions-Financial-Capital-Dynamics/dp/1843763311)  
- [Paweł Huryn — Product Compass](https://www.productcompass.pm/)  
- [Paweł Huryn & Miqdad Jaffer (Product Lead @ OpenAI) — AI PRD Template](https://www.productcompass.pm/p/ai-prd-template)  
- [Paweł Huryn — AI Glossary](https://www.productcompass.pm/p/ai-product-manager-glossary)  
- [Paweł Huryn — The Ultimate List of Product Metrics](https://www.productcompass.pm/p/the-ultimate-list-of-product-metrics)  
- [Marty Cagan (SVPG) — AI Product Management](https://www.svpg.com/ai-product-management/)  
- [Marty Cagan (SVPG) — Creating Intelligent Products](https://www.svpg.com/creating-intelligent-products/)  
- [Lenny Rachitsky — Why PMs Are Best Positioned to Thrive](https://www.lennysnewsletter.com/p/why-pms-are-best-positioned-to-thrive)  
- [Lenny Rachitsky — How AI Will Impact PM](https://www.lennysnewsletter.com/p/how-ai-will-impact-product-management)  
- [Aakash Gupta — The AI PRD](https://www.news.aakashg.com/p/ai-prd)