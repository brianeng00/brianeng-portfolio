# Brian Eng — Voice, Values & Application Answers

> This document captures Brian's authentic voice in his own words, drawn from real application answers. Use this when drafting cover letters, application responses, or any written work that needs to sound like him. Do not rewrite these in a generic direction. Preserve the specificity, the personal detail, and the earned confidence.

---

## The Through-Line

Brian's career started with WordPress on a LAMP stack, building sites for a personal portfolio, a small Flash game team, and his first startup. That scrappy, hands-on approach stuck. He debugs by going deep, fully understanding the problem before jumping to a solution.

He grew through a startup, its post-acquisition transition, and a midsize corporation, both in marketing technology. That world shaped everything: building embedded JavaScript in third-party environments he didn't control, on pages he couldn't predict, where a single uncaught error could break a client's site. High stakes, defensive code, pixel-perfect delivery.

He is now ready to build features at a much greater capacity, with full ownership, at product-level depth.

---

## What Motivates Him (In His Words)

"My dev journey actually started with WordPress. Over 10 years ago I was building sites for my personal portfolio, a small Flash game team I collaborated with to build games, and my first startup role. All of it on a LAMP stack, just figuring things out as I went. That scrappy, hands-on approach stuck with me and still defines how I work today: I debug by going deep into the details, fully understanding the problem before jumping to a solution."

"I've hit a ceiling in the scope of those roles and field. I'm looking to contribute, own, and build features at a deeper level. From pushing updates to a legacy EmberJS platform to building a React-based Chrome extension as an internal dev tool, I took ownership of these features end to end, picking up whatever was needed along the way."

---

## When He Feels Happiest at Work (In His Words)

"I feel happiest when building from zero to one. The whole journey of blocking out the work, hitting milestones, and venturing into something entirely new is what excites me most. I thrive on that sense of discovery, and web development keeps feeding it. The landscape never sits still, and neither do I. I'm always learning something new and finding better ways to build. Just seeing how the feature slowly renders out at each step of development makes me want to share the wonder and excitement with my teammates."

---

## When He Feels Least Fulfilled (In His Words)

"I feel least fulfilled when architectural decisions get made that prioritize short-term convenience over the end user's experience. Especially when those choices introduce security risks, compromise accessibility, or erode the UI/UX foundations and guidelines the team has already established. I've been in situations where I've had to push back on decisions like that, and it's frustrating when the tradeoffs aren't weighed honestly. I care too much about what ships to be comfortable cutting those corners."

---

## His Collaboration and Conflict Style (In His Words)

"At Wunderkind, a client requested an experience that would overtake their site on the very first page load. My manager didn't see an issue with what seemed like a straightforward request. But I knew from experience that this kind of implementation had serious ramifications."

"I couldn't let it slide, but I also knew that just explaining the problem verbally wasn't going to land the way it needed to. So I built a test experience and recorded a demo that showed exactly what happens when these overlays collide. I walked my manager through the recording and gave them the test environment to see the issue firsthand along with solutions we can do instead to avoid the issue outright. Once they could actually see the focus lock happening in real time, the concern clicked."

"I'll always advocate for the end user, even when it means pushing back on a request that seems simple on the surface. The best way I've found to do that isn't by arguing the point, it's by showing the evidence."

---

## His Values Around Helping Teammates (In His Words)

"Throughout my career, I always noticed teammates getting blocked at points where things could be worked around or solved a different way. I made it a habit to jump in, whiteboard solutions together, and turn those moments into quick brainstorming sessions. Sometimes that meant just talking through the problem, reviewing the specs and getting all the perspectives. Other times it meant actually building something to fix it."

"That instinct is exactly what led me to build a React-based Chrome extension internal dev tool to enable real time live testing on site, and to take ownership of design feature updates on the legacy EmberJS platform that eliminated a manual workaround and improved efficiency by 80%. Both started from seeing teammates struggle with something I knew I could make better."

---

## His Opinion on AI and Engineering Craft (In His Words)

"AI-generated code is making engineers worse at debugging. Engineers lean on Copilot or ChatGPT to generate a solution, ship it, and then have no idea what to do when it breaks. They skip the step of actually understanding what the code is doing and why."

"I've spent my career building experiences for client sites where we can't afford any errors. In that world, you can't just accept whatever the AI hands you. You need to understand every line, know how it interacts with the DOM, and be ready to debug it when something goes sideways."

"I'm not against AI as I use these tools and they genuinely make me faster. But I treat them like a first draft, not a finished answer. Everything still gets reviewed, understood, and owned by me. The engineers who will thrive long-term are the ones who use AI to accelerate work they already understand, not to skip the understanding entirely."

---

## What Is Most Important in His Next Role (In His Words)

"What matters most to me is end-to-end ownership over systems that other engineers depend on. I've spent my career at the integration boundary, building the deployment libraries, internal tooling, and shared infrastructure that teams ship on, and I want that to be the whole job, not a side project I carve out between tickets."

"After years of client-facing integration work, I'm drawn to product-side platform engineering, where the output compounds. When I take something from problem definition to production thoughtfully, the output multiplies across everyone who depends on it. That leverage is what I find most meaningful."

---

## Signature Project: Wunderkind Ember Platform Feature (Canonical Version)

**The setup:** A legacy internal platform built on EmberJS that designers used to build creatives for embedded experiences deployed to client websites. Designers had to manually copy styling changes whenever they needed to create variations. No way to apply adjustments at a category-wide level across groups of creatives. The feature had never been built, and there was zero documentation on the platform.

**His role:** Took full ownership. Dug deep into the codebase to understand how the data models and styling layers were structured.

**The core tradeoff:** Figuring out how to apply bulk styling changes without breaking the override logic that individual creatives relied on. Category-level updates needed to cascade down while still respecting one-off customizations designers had already made.

**The result:** Built the feature so that multitudes of creatives could be updated with a single click. Eliminated a manual workaround that had plagued designers for hours. Improved workflow efficiency by roughly 80%. Hosted a walkthrough meeting with the design lead and managers.

**One-sentence version (confirmed accurate):**
"I built an internal platform feature at Wunderkind that eliminated a manual workaround designers relied on to make category-wide styling changes across creative assets. What previously took 10 to 20 minutes of repetitive work now takes seconds, and the workaround is completely gone."

---

## Signature Project: React Chrome Extension

**What it was:** A React and TypeScript Chrome extension built as an internal dev tool to enable real-time live testing of embedded top bar experiences on client sites. Publicly available at: https://github.com/brianeng00/top-bar-automator

**Why it was built:** Teammates were blocked by slow, manual integration testing. Testing embedded experiences required a painful manual setup process. Brian saw the problem and built a solution that let engineers inject, configure, and test experiences live on any client site directly from the browser.

**Tech stack:** React (functional components, hooks), TypeScript, custom Webpack multi-entry config for Chrome extension build pipeline, Chrome Extension API (content scripts, background scripts), CSS injection via DOM manipulation.

**The Webpack angle:** Chrome extensions require a specific Webpack configuration to handle multiple entry points (popup, content script, background service worker) and output them as separate bundles the extension manifest can reference. The custom webpack.config.js handles this build pipeline including TypeScript compilation. This is publicly visible in the repo root.

**The result:** Reduced integration testing time by 70%.

---

## Growth Mindset (In His Words)

"The recent Winter Olympics really struck a chord with me, specifically Alysa Liu's story. She stepped away from competitive skating, came back on her own terms, and won gold. What got me wasn't just the comeback itself, it was the idea that growth doesn't have to follow someone else's timeline or structure."

"My role at Wunderkind has been very siloed and structured. The work was meaningful, but my capacity to explore new technologies and grow beyond my immediate responsibilities was strictly limited... I needed to take ownership of my own development. So I did. Outside of work, I started exploring and learning more about React, building my own tools with the Claude API, exploring local LLM setups, and pushing myself into areas I hadn't touched before."

"That shift in mindset, that my growth is my responsibility and not just my employer's to define, has changed how I think about my career and what I want from my next role."

---

## Core Values Summary (Synthesized)

- **Craft over convenience.** Will push back on decisions that compromise accessibility, security, or UX fundamentals.
- **Build the tool, not the workaround.** Default instinct is to solve the root problem, not work around it.
- **Show, don't argue.** When advocating for a position, builds a demo or produces evidence rather than arguing the point.
- **Teammates first.** Habitually unblocks colleagues. Has always been the last to log off.
- **Growth is personal responsibility.** Doesn't wait for an employer to define his development path.
- **AI accelerates, not replaces, understanding.** Treats AI output as a first draft. Reviews, understands, and owns everything that ships.

---

## Writing Style Notes

- Direct and personal. No corporate softening.
- Uses specific technical details (EmberJS, Chrome extension, CWV, DOM, focus trapping) to earn credibility.
- Leads with the human problem before the technical solution.
- Avoids adverbs and filler qualifiers.
- Uses "I" confidently. Doesn't hedge ownership.
- References real company names, real teammates, real contexts.
- Ends arguments with evidence or outcome, not opinion.
