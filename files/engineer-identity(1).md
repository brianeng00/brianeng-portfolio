# Brian Eng — Engineer Identity Reference

> Use this doc at the start of every session to understand who Brian is as an engineer, what kind of work he does best, and how to tailor role evaluations, application answers, and job search strategy to his actual background.

---

## The One-Sentence Version

Brian is a **browser-layer platform engineer** who has spent 11+ years at the intersection of real-time data, hostile integration environments, and developer tooling — building the infrastructure other engineers and end-users depend on.

---

## Career in Three Chapters

### Chapter 1: Consumer Attention Research (2013–2019)
**Companies:** EyeTrackShop → Sticky → Tobii (Sticky was acquired by Tobii)
**Industry:** Market Research / Consumer Insights — B2B SaaS for enterprise research teams

Sticky and Tobii built webcam and hardware eye-tracking platforms. The product captured where people literally look on a screen — gaze coordinates, facial coding, real-time video streams — and surfaced that into dashboards and heatmaps for Fortune 500 brands (P&G, Nielsen, Ipsos, iMotions). Brian built the UI that made raw biometric data understandable to researchers and brand strategists.

This is where his core instincts formed. Not marketing copy or CRUD apps — wiring a UI into hardware capture devices, managing real-time data streams, integrating with third-party survey platforms (SurveyGizmo, Qualtrics, ConfirmIt), and ensuring cross-browser fidelity under measurement conditions where precision mattered. Stakes were scientific validity, not clicks.

Key work: mobile/tablet device simulator with live camera eyetracking, reusable AngularJS templates for cross-device data collection, E2E automation with Selenium/BrowserStack/Jenkins/AWS, integration layer documentation between UI and capture hardware.

### Chapter 2: Performance Marketing Infrastructure (2019–2026)
**Company:** Wunderkind (formerly BounceX)
**Industry:** AdTech / Identity Resolution / Autonomous Marketing — e-commerce revenue recovery

Wunderkind runs as an embedded JavaScript tag on client websites. It identifies anonymous visitors using a proprietary identity graph, then fires triggered email/SMS at the moment of highest intent to recover abandonment and drive conversions. Brian was on the integration engineering side — the team responsible for deploying that tag across hundreds of client environments without breaking anything.

This is where his specialization sharpened. Third-party scripts running in someone else's DOM, in browsers he doesn't control, under performance budgets he can't negotiate. He built the deployment library, set the engineering standards, and created the internal tooling that made that work faster and more reliable for the entire team.

Key work: Internal platform that eliminated a manual workaround entirely (10-20 min process reduced to seconds, 80% efficiency gain — no docs, dug into data models and override logic from scratch), React-based Chrome extension for real-time live visualization/testing (70% integration testing speed increase), zero CWV degradation on client sites, reusable code deployment library, WCAG compliance standards, ramp-up documentation that cut new engineer onboarding time by 20%.

### Chapter 3 (Emerging): Platform / DX Engineering
The thread connecting both chapters is that Brian has always been the person building the infrastructure *other people depend on* — whether a research platform, a deployment library, or internal tooling. He is now consciously moving toward making that the explicit job: Platform Engineer, DX Engineer, Frontend Infrastructure.

---

## Industries Worked In

| Industry | Company | Years | What Was Built |
|---|---|---|---|
| Market Research / Consumer Insights | Sticky / Tobii | 2013–2019 | Eye-tracking SaaS, real-time biometric dashboards, survey platform integrations |
| AdTech / Performance Marketing | Wunderkind | 2019–2026 | Embedded JS scripts, identity resolution integrations, deployment infrastructure, internal tooling |

Both industries are data-intensive, real-time, and B2B. Both required deep care about what happens in the browser under load.

**Adjacent industries with high narrative overlap:** e-commerce, developer tooling, observability/analytics platforms, data visualization products, ML/AI tooling with non-technical end-users.

---

## Defining Engineer Characteristics

**Works at the boundary.**
Every job has put Brian at the integration layer — between a platform and a client's site, between hardware and a browser, between an ML engine and a non-technical user. He's comfortable in territory other engineers hand off.

**Builds for hostile environments.**
Third-party scripts in client DOMs, real-time streams from physical capture devices, cross-browser compatibility under scientific measurement conditions. He doesn't control the environment, so he writes defensively by default. Zero degradation is a hard constraint, not a goal.

**Builds tools that make people faster.**
The Chrome extension, the deployment library, the documentation that cut ramp-up 20% — he consistently reaches for "build the tool" over "do the thing manually." Platform engineering instinct, not just productivity.

**Translates complexity for humans.**
Eye-tracking heatmaps for researchers, performance dashboards for marketers — his whole career has been making high-dimensional, real-time data actionable for people who aren't data scientists or engineers. This maps directly to data visualization, ML tooling, and observability product roles.

**Cares about craft.**
WCAG compliance, zero CWV degradation, TDD — these show up unprompted across every job. They're values, not checkboxes. Completed Udacity Web Accessibility course (ud891); treats a11y as a first-class constraint when building.

---

## Technical Identity

**Core strengths (battle-tested):**
- Embedded JavaScript in third-party environments
- DOM manipulation and browser API expertise
- Real-time data streams and WebSocket-driven UI
- Performance engineering (Core Web Vitals, bundle optimization, render budgets)
- Component libraries, deployment libraries, shared infrastructure
- Micro-frontend architecture and integration patterns
- Cross-browser compatibility and defensive coding
- WCAG accessibility compliance

**Currently building depth:**
- React (fresh/recent — strong DOM/JS fundamentals, Ember background, actively deepening)
- TypeScript (listed in skills; building demonstrated proficiency)
- Data visualization (D3.js adjacent via DOM expertise; Recharts territory)

**Framework history:** jQuery → AngularJS → Ember.js → React. Framework-agnostic by nature — understands the browser layer, not just the abstraction on top of it.

**Bonus context for role matching:**
- AdTech background is a differentiator for any role touching e-commerce, conversion, or performance marketing
- Eye-tracking/research background is a differentiator for data visualization roles and ML tooling with non-technical users
- Integration engineering experience maps to: SDK work, external platform APIs, third-party script delivery, developer-facing tooling

---

## Core Values (Verified from Application Answers)

- **Craft over convenience.** Will push back on decisions that compromise accessibility, security, or UX foundations, even when it means conflict. Builds evidence first, argues second.
- **Build the tool, not the workaround.** Default instinct is to solve the root problem. Both signature projects (Chrome extension, Ember platform feature) started from watching teammates struggle with something that could be fixed.
- **Show, don't argue.** When advocating for a position, builds a demo or produces evidence rather than arguing the point. (Accessibility / focus trap conflict: built test experience, recorded demo, gave manager a live environment.)
- **Teammates first.** Habitually unblocks colleagues. Turns blocked moments into whiteboard sessions. Has always been the last to log off.
- **Growth is personal responsibility.** Outside of work, independently learning React, building with the Claude API, exploring local LLM setups. Growth is not waiting for an employer to define it.
- **AI accelerates, not replaces, understanding.** Treats AI output as a first draft. Reviews, understands, and owns everything that ships. Believes engineers who skip the understanding will pay for it in debugging debt.

---

## How to Use This Doc

When evaluating a role for Brian:
1. Check if the role values browser-layer depth over framework familiarity
2. Check if the product involves real-time data, complex dashboards, or making ML/data legible for non-technical users
3. Check if there's a platform, DX, or infrastructure dimension — not just feature work
4. Flag roles where the primary value is framework proficiency alone (React shops that don't care about the browser layer)
5. The AdTech and research backgrounds are narrative assets — surface them when the role touches performance marketing, e-commerce, or data visualization

**Strongest role archetypes for Brian:**
- Web Platform / Frontend Platform engineer
- Developer Experience (DX) engineer
- Frontend Infrastructure engineer
- Data visualization / observability frontend engineer
- Integration or SDK-focused frontend engineer
- Any product where making complex data intuitive for non-technical users is the core problem
