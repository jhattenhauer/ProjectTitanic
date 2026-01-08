# Hardware Review #

## Current State

At present, IcebergASV’s hardware systems suffer from **minimal redundancy, limited familiarity across the team, and insufficient documentation**. Much of the existing system knowledge left with former members, leaving behind hardware that functions but is poorly understood.

This creates several risks:
- Inability to quickly recover from failures
- Heavy dependence on a small number of people
- Slow onboarding of new members
- Testing delays caused by uncertainty in setup and wiring

---

## Long-Term Goal

The end goal of the hardware system should be **rapid, repeatable, and well-documented assembly**.

Specifically:
- A complete electrical and compute system should be assembled and made operational in **~1 hour**, excluding mechanical assembly of hulls or enclosures
- Any new or returning member should be able to understand:
  - What each component does
  - Where cables are routed
  - How systems are powered and interconnected
- The system should be **simple, robust, and easy to reason about**

If the team is serious about long-term preservation and growth, the next **1–2 years** must focus on creating a hardware platform that is **sustainable**, not optimized solely for short-term performance.

**Simplicity is a feature.**  
A minimal number of components, connections, and failure points is preferable to a complex system that only works when assembled by its original designers.

---

## Electrical Simplicity ##

### Motivation

A consistent and reliable electrical setup is the foundation of all testing. When systems fail intermittently or behave unpredictably, it blocks progress across firmware, autonomy, and operations.

Equally damaging is the absence of team members who fully understand the system. Even functional hardware becomes unusable if no one knows how to diagnose it.

### Key Principles
- Favor **known-good configurations** over experimental complexity
- Minimize:
  - Cable types
  - Connector types
  - Adapters and converters
- Standardize power distribution and networking layouts
- Treat electrical design as a long-term asset, not a one-off build

### Proposed Changes
- Re-evaluate manpower allocation between:
  - Physical hardware fabrication
  - Electrical wiring and system integration
- Transition electrical students into ownership of:
  - Pixhawk setup, configuration, and tuning
  - Wireless communication systems
  - Thruster control and signal routing
  - Jetson power, boot, and networking
- Ensure at least **two students** fully understand every electrical subsystem

### Expected Outcome
Electrical systems become **predictable, reproducible, and well-understood**, enabling faster testing and fewer last-minute failures.

---

## Hardware Dependability ##

### Current Challenge

Hardware work tends to follow a **boom-or-bust cycle**:
- Periods of extreme pressure during hull or enclosure builds
- Long stretches of inactivity once a functional platform exists

This leads to underutilized team members and loss of momentum.

### Proposed Direction

Once a **strong baseline system** has been assembled for the year, hardware members should be encouraged to expand into:
- Electrical system ownership
- Integration and diagnostics
- System reliability improvements
- Maintenance and documentation

This approach:
- Keeps hardware members engaged year-round
- Improves cross-discipline knowledge
- Reduces silos between mechanical, electrical, and software teams

### Expected Outcome
Hardware becomes a **continuous contributor** rather than a seasonal bottleneck, increasing overall system reliability and team resilience.

---

## Summary

A dependable hardware system is not defined by how advanced it is, but by:
- How quickly it can be assembled
- How easily it can be understood
- How reliably it performs
- How well it is documented

By prioritizing simplicity, documentation, and shared ownership, IcebergASV can build a hardware platform that supports not just the current team, but many future ones as well.
