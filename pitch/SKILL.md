---
name: pitch
description: Write and review Shape Up pitches from framing documents, shaping artefacts, breadboards, transcripts, notes, or a developed project idea. Use when the user asks to create, draft, improve, validate, or prepare a pitch or potential bet for a betting table using Shape Up.
---

# Shape Up Pitch

Compose a pitch — a self-contained write-up that presents shaped work as a potential bet. The pitch captures the shaping already done and makes it legible to people who weren't in the room.

A pitch is a presentation, not a specification. It is the bridge between private shaping and a public betting decision.

## Principles

- A pitch always presents a problem and a solution together. A solution without a problem has no test of fitness. A problem without a solution is unshaped work.
- Appetite is a constraint, not an estimate. It limits what kind of solution is acceptable.
- The pitch must be rough enough to leave room for designers and programmers to exercise judgement. Never produce wireframes, task lists, acceptance criteria, or implementation plans.
- The pitch must be solved enough that a reader can see the core elements of the approach and how they connect. It should not push research or open design questions down to the build team.
- The pitch must be bounded — it shows where the team should stop.

## 1. Check That Shaping Is Done

The pitch writes up work already completed. It does not do the shaping.

Before drafting, confirm that these exist in the source material:

1. **A specific problem with a baseline** — a story or use case showing how the status quo breaks down for a real or representative user.
2. **An appetite** — a stated time budget (typically six weeks or a small-batch duration) that constrains the solution.
3. **A shaped solution** — core elements at the right level of abstraction: concrete enough to understand, rough enough to leave room.
4. **De-risked rabbit holes** — tricky details the shaper already investigated and made a call on.
5. **Intentional exclusions** — things deliberately left out to fit the appetite or keep the problem tractable.

If any of these are absent:

- Do not fabricate or pad the missing ingredient with plausible prose.
- Tell the user what is missing, why the pitch is not yet ready, and what the smallest upstream step is to resolve it (frame the problem, set the appetite, shape the solution, spike a technical unknown, or explicitly declare what's out).

Accept whatever combination of inputs the user supplies — framing documents, shaping documents, breadboards, spike results, transcripts, notes, screenshots, or conversation. Read the minimum needed.

## 2. Write The Five Ingredients

### Problem

Present a specific baseline story that shows why the status quo doesn't work. The reader should be able to picture the situation and feel the pain without yet knowing the proposed solution.

How much detail depends on the audience. When readers share deep context with the shaper, a few sentences may suffice. When the audience is broader, use evidence — screenshots, usage data, verbatim quotes, or video — to make the case vivid.

Do not lead with the feature. Establish the problem first so readers have a basis for judging whether the solution fits.

### Appetite

State the time budget briefly — one or two sentences. Singer treats appetite as near-metadata: "Note the one-week appetite. This was a Small Batch project."

The appetite tells readers what class of solution to expect and prevents unproductive "but we could also..." conversations. It is part of the problem definition: we want to solve this use case *in this much time*, not more.

Do not write an essay justifying the appetite. Do not express it as an estimate of how long the described scope will take.

### Solution

Present the core elements and how they connect, in the order the reader needs to understand them. Show how the solution changes the baseline outcome from the problem section.

**Visuals — only when there's a linchpin.** Ask: is there a part of the concept that readers cannot understand from words alone? If yes, that part is a linchpin and deserves a visual — go one level more concrete *only for that part*. If no linchpin exists, no visual is needed.

When a visual is needed:

- Prefer an embedded sketch or annotated fat-marker sketch that shows the linchpin element in just enough spatial context.
- A simplified breadboard (places, key affordances, connections) works when the concept is a flow rather than a visual arrangement.
- Evidence visuals (data charts, screenshots of the current state) support trade-off arguments.

Always:

- Keep visuals deliberately rough. If a sketch includes layout decisions that are illustrative rather than essential, say so explicitly — remind designers they should feel free to find a different design.
- Never paste exhaustive affordance tables, engineering breadboards, or wiring diagrams into the pitch. Simplify for the audience.
- Never produce wireframes or high-fidelity mockups.

When no visual is needed, omit the section entirely.

### Rabbit Holes

Call out the tricky details worth knowing about — things that could trip up the team or waste time if not addressed up front.

A rabbit hole in a pitch is brief. Sometimes it is one sentence: "URLs won't live on custom domains for v1." Sometimes it is a short paragraph explaining a specific call the shapers made about a thorny interaction or technical constraint.

Each rabbit hole should state the danger and the decision or patch. Do not turn this into a risk register or formal taxonomy. Do not list every possible concern — only the ones material enough that a team member or betting-table reader needs the heads-up.

### No-Gos

List anything specifically excluded from the concept — functionality, use cases, or fidelity levels intentionally not covered. Connect each to the appetite or the narrowed problem when the rationale isn't obvious.

No-gos prevent scope creep. They tell the team and the betting table: "We know someone might expect X. We're deliberately not doing X."

## 3. Review The Draft

After writing, check:

**Problem:**
- Does it present a specific baseline situation, not a generic benefit statement?
- Can a reader evaluate the problem independently of the solution?
- Is the evidence proportional to the audience's existing context?

**Appetite:**
- Is it stated as a brief constraint, not an estimate or justification?

**Solution:**
- Can a reader see the core elements and how they connect?
- Does the solution clearly improve the baseline from the problem section?
- Is it rough enough that designers and programmers have room to make decisions?
- Is it free of task lists, implementation slices, acceptance criteria, and pixel-level direction?

**Visuals:**
- If there's a linchpin, does the visual make it understandable?
- If there's no linchpin, is the pitch free of unnecessary illustrations?
- Are visuals rough, labelled, and disclaimed where they could bias implementation?

**Rabbit holes:**
- Is each one brief — danger plus decision — not an open question?

**No-gos:**
- Are exclusions concrete enough to prevent reasonable scope expansion?

**Overall:**
- Can this pitch be read and understood asynchronously by someone who wasn't in the shaping sessions?
- Does the pitch present a potential bet, or does it try to argue for a commitment? (The pitch presents; the betting table decides.)

## 4. Return The Result

Return the pitch as a clean standalone document.

If the pitch is not ready because an ingredient is missing or unshaped, return:

1. What is missing
2. What upstream step resolves it
3. Do not hide the gap inside a polished draft
