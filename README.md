# Designing an AI coach for a 90-day cohort

A design record from an early-stage AI product for founders that I worked on in 2025 and 2026. My part was to map the experience the AI coach would sit inside and write the specification of what it could and couldn't do. This was an internal design exercise on a prototype, and nothing here shipped. The example is rewritten from scratch with the same structure, so no real project details or people are in it.

| File | What it is |
|---|---|
| [`experience-map.html`](experience-map.html) | The 90-day experience, stage by stage, with every touchpoint classified as human-essential, an AI opportunity, or already built |
| [`SPEC.md`](SPEC.md) | The behavior specification: 5 principles, 7 interaction patterns, 5 hard boundaries, and the decisions deliberately left open |

## The problem

Every review of the prototype turned into an argument about tone, and every argument was two people's preferences with nothing to check them against. "The coach shouldn't do that" was a claim nobody could test. So the first thing I needed wasn't a better prototype. It was something to judge one against.

## Why the map comes first

You can't decide what an AI should do inside an experience you haven't written down. The map has one rule: every touchpoint gets classified as human-essential, AI opportunity, or already built. Making that call one touchpoint at a time is what surfaces the hard cases. It's easy to say "AI can help with onboarding." It's much harder to look at "meet everyone for the first time" and argue that a model belongs anywhere near it.

The map also records what people actually did, not personas: most read, far fewer comment; attendance is highest at kickoff and never again. A design decision can rest on sentences like those.

## Why the boundaries matter most

The specification has principles and patterns, like most do. The part that took longest is the list of five things the coach can't do: replace peer connection, enforce accountability, make introductions, provide cultural context, or build confidence. A language model can imitate every one of them well enough that a user might not notice. That's why they're written down. A model that does something badly isn't the risk; a model that does it convincingly when it shouldn't is.

## What internal testing showed

Before anyone outside the team saw it, three people on the internal team tried the prototype, whose AI responses were pre-scripted. They completed the guided flow and rated it clear, but rated the AI's usefulness lower. Their feedback described the AI as a feedback-giver, not a collaborator. That's a design finding, not a tuning problem. With three testers, I describe the numbers instead of printing them.

## What's left open on purpose

Ten or more technical decisions, like model choice, memory, escalation and how far to personalize, are written down as open, pending user research. Recording a deferral matters: skip it, and the question gets settled silently by whoever builds that part first.

---

More of my work: [github.com/amijach1103](https://github.com/amijach1103) · MIT license
