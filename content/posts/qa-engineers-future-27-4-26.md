+++
draft = false
date = 2026-04-27T18:53:06+02:00
title = "Are QA & Test Engineers Safe in the Age of AI?"
description = ""
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++
# Are QA & Test Engineers Safe in the Age of AI? Some Honest Thoughts from QonfX Berlin

Last week I attended [QonfX in Berlin](https://www.thetesttribe.com/qonfx/berlin/) — a fantastic event, full of good talks, great speakers, and genuinely talented people in the testing space.

But let's talk about the elephants in the room.

Amid all the enthusiasm, one question kept hovering, unasked or unanswered: **Do we — QA and test engineers — still have a future?**

Here's my honest take. The answer isn't one-size-fits-all. **It depends heavily on where you currently sit in the testing landscape.**

---

## 🔴 High Risk: UI Automation Engineers

If your work is solely focused on UI automation, **the risk is real and it's moving fast.** AI is taking increasingly confident strides toward owning this space entirely. If this is you, the time to start learning proper programming — and pivoting toward other testing disciplines — is **now, not later.**

## 🔴 High Risk: Mobile Test Engineers

Whether you are focused on manual mobile testing or automation using tools like Appium, XCUITest, or Espresso — **the risk is high.** Mobile UI automation is following the exact same trajectory as web UI automation, and general mobile testing without strong programming skills leaves very little to stand on. The platform is different; the threat is the same.

## 🟡 Medium Risk: API Testing Engineers

API testing carries real risk, but less than UI automation. It still requires understanding **business logic, data contracts, and system behavior** in ways that are genuinely nuanced — areas where AI is not yet fully reliable. That said, complacency here is dangerous. **Deepening your programming skills and staying close to AI tooling is essential.**

## 🟡 Medium Risk: Framework & Test Infrastructure Engineers

Those who build custom test frameworks on top of language-specific tools (like pytest, for example) are in a comparatively safer zone — for now. AI still struggles to grasp the full context and complexity of large, real-world codebases. But **"safer" doesn't mean comfortable.** You need to actively learn AI tooling to keep up with productivity expectations and the growing demands from management.

## 🟡 Medium Risk: Security & Penetration Test Engineers

Adversarial thinking, creative attack surface exploration, and the ability to chain vulnerabilities in unexpected ways are still beyond what AI can reliably do. That said, AI is already being used to assist with vulnerability scanning and fuzzing, so **staying sharp and continuously evolving your skill set is essential.**

## 🟢 Lower Risk: Embedded & Hardware Test Engineers

Testing firmware, IoT devices, and physical systems involves constraints — hardware variability, real-world environments, physical signaling — that AI cannot yet operate in autonomously. **This is one of the safer spots in the profession today.**

---

Before we talk about what to do, it is worth doing an **honest check on where you actually stand today.** The risk tier you fall into matters — but so do your daily habits. Some patterns are warning signs regardless of your specialization.

## ⚠ An honest self-check: traits that should worry you

Regardless of your specialization, if you find yourself doing several of these consistently — it's time to reflect:

1. **Repeating the same tasks** with no evolution or improvement
2. **Running tests without reading the code** underneath them
3. **Using tools as black boxes** — Selenium, Cypress, AI tools — without understanding the underlying logic
4. **Never questioning test coverage** — accepting what exists without asking what's missing
5. **Avoiding programming** — staying comfortable in low-code or record-and-playback territory
6. **Not knowing the business domain** — testing features without understanding why they matter
7. **Waiting to be told what to test** — no proactive thinking about risk or quality
8. **Ignoring AI tooling entirely** — pretending the landscape hasn't changed
9. **Copy-pasting test cases** with no strategic thinking behind them
10. **Never reviewing** anyone else's code or tests — staying siloed with no cross-functional involvement

The more of these that apply to you, **the higher your personal risk** — regardless of which category above you fall into.


Knowing where the risks are and recognizing the warning signs is only half the battle. **The more important question is what to actually do about it.**

## So what's the path forward?

### 1. Invest seriously in programming skills — more than ever.

We will absolutely work with AI — but we shouldn't depend on it to build scalable solutions. In fact, as AI generates more and more code, **the need for strong programming skills actually increases.** We need to be capable of properly reviewing AI-generated code, catching subtle logic errors, architectural weaknesses, and edge cases that AI confidently gets wrong. A test engineer who cannot code at a high level will not be able to meaningfully review what AI produces. And here's the often-overlooked flip side: **more AI-generated code means a higher demand for skilled human reviewers.** That's not a threat to our profession — it's potentially an argument for why strong test and QA engineers remain very much needed, just with a sharper, more programming-heavy skill set than before.

### 2. Specialize in niche, high-complexity domains.

Every specialized field adds a layer of complexity that current AI models are not yet reliably equipped to handle — at least in the medium term. **Specialization is an extra layer of job security.** Some of the strongest areas to go deep in right now:

- **Database internals** — understanding query execution, indexing behavior, and data integrity at a deep level
- **Performance & load testing** — modeling real-world traffic, identifying bottlenecks, and interpreting system behavior under stress
- **Chaos & resilience engineering** — deliberately breaking systems to expose weaknesses in ways that require deep systems intuition and creative thinking
- **AI model validation & red teaming** — ironically one of the safest bets; testing AI systems requires adversarial creativity that AI itself struggles to apply reliably against itself
- **Compliance & regulatory testing** — HIPAA, GDPR, ISO 26262 and similar frameworks require human legal accountability and interpretive judgment that AI cannot be held responsible for



These are my personal opinions. They are shaped by years of working in this field, the conversations I had at [QonfX](https://www.thetesttribe.com/qonfx/berlin/), and honestly, a lot of thinking out loud. I also want to mention that **this post was written with AI assistance!** It helps me stay productive. If you see it differently — if you think I got something wrong, missed something important, or if you just want to push back — please do. That's exactly the kind of conversation I want to have. **Feel free to reach out directly on [LinkedIn](https://www.linkedin.com/in/hagarmohamed/).**


#QualityEngineering #SoftwareTesting #AIinTesting #TestAutomation #CareerDevelopment #QA
