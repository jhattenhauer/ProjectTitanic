# My Home #

## This Is My Area of Familiarity ##

The current codebase was built by one person, for one person, moving very fast under competition pressure. While it was effective at the time, it was never designed to be learned, extended, or maintained by outsiders.

The result is a system that is:
- Highly fragmented
- Heavily framework-dependent
- Difficult to reason about without deep prior context

In addition, much of the codebase contains legacy paths, unused tools, and experimental branches that were never cleaned up. This is not a criticism of the original author (love you, Grace ❤️) — it is a predictable outcome of building under extreme time pressure without a mandate for long-term maintainability.

From the perspective of a new or returning member, reading the code often leads down **rabbit holes that are no longer relevant**, making learning unnecessarily intimidating.

---

## Document, Document, Document ##

At present, there is no:
- System architecture overview
- Formal description of component interactions
- User or developer manual
- Clear ownership of subsystems

The framework that currently exists has **no documented outline**, and many niche command-line tools and testing scripts are effectively unusable because no one knows when or why to use them.

To fix this, the system must be treated as a **collection of interacting components**, not a monolithic block of code.

### Proposed Direction

- Formally define each major subsystem:
  - Purpose
  - Inputs and outputs
  - Dependencies
  - Failure modes
- Assign **clear ownership**:
  - Each component has one or two responsible people
  - Ownership includes:
    - Writing code
    - Testing functionality
    - Maintaining documentation
- Require documentation to be written *alongside* code, not after the fact

No single person should be expected to understand the entire system. However, **every part of the system should be fully understood by at least two people**.

---

## Why Allocation Matters ##

Poor allocation in the past created two unhealthy extremes:
- Some people became **critical single points of failure**
- Others had nothing meaningful to work on

When I first joined the team, I was hesitant to ask for work — not because I didn’t want to help, but because I was afraid of breaking something, slowing someone down, or stepping on invisible boundaries.

Clear task ownership and defined responsibilities reduce this friction. When everyone knows:
- What they own
- What they are allowed to change
- Who to ask questions to

…the entire team becomes more confident and more effective.

This principle applies to every sub-team, but it is **absolutely essential in software**.

---

## Other People Can Use Computers Too ##

Historically, “software” on the team has meant both:
- Writing code
- Dealing with hardware-adjacent tasks like networking, configuration, and system setup

This is inefficient.

### Proposed Shift

I propose that **electrical and hardware-focused members take ownership of the hardware-facing aspects of software**, including:
- Networking
- Onboard system configuration
- Navigation hardware setup
- Physical wiring and interfaces

This allows:
- Software developers to focus on **development, algorithms, and architecture**
- Electrical students to take ownership of systems they are better positioned to maintain

Before I left, there was interest in making this transition, but I was not in the right headspace to properly support it at the time. That is on me.

The core idea is simple:
> Let more people help with the heaviest system on the boat — the software — and let software people actually write software.

---

## Closing Thought ##

The goal is not to rewrite code for the sake of cleanliness.  
The goal is to build a system that:
- Can be learned
- Can be trusted
- Can be handed off

Software should be a **force multiplier**, not a gatekeeper.
