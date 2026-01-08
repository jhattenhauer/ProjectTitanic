# Project Titanic #

## Overview

**Project Titanic** is a year-long internal restructuring initiative aimed at transforming **IcebergASV** into a more formal, well-distributed, and sustainable engineering design team. The project addresses long-standing technical, organizational, and knowledge-transfer issues that currently limit progress, scalability, and continuity.

The core philosophy of Project Titanic is **resilience**:
- Resilience against member turnover
- Resilience against hardware failures
- Resilience against undocumented systems
- Resilience against loss of institutional knowledge

By the end of the project, IcebergASV should function as a team where:
- No single person is a point of failure
- Systems are reproducible and testable
- Knowledge is documented and shared
- New members can onboard efficiently
- The team can sustain itself year-over-year

---

## Core Objectives

Project Titanic focuses on the following major areas:

- Bulletproofing the hardware system for consistent testing and development
- Increasing training and knowledge distribution in firmware and operational software
- Developing robust testing, simulation, and visualization tools
- Overhauling and modernizing the main autonomy codebase
- Revamping the team’s online presence and public-facing materials
- Cleaning, restructuring, and formalizing the GitHub organization

Each section below outlines the motivation, problems, and intended outcomes.

---

## Bulletproofing Hardware ##

### Problem Statement
One of the most significant barriers to consistent progress is **unreliable and inconsistent hardware setup**. Hardware configurations change between testing sessions, undocumented wiring or settings are lost, and failures often halt development entirely.

This creates:
- Inability to reproduce bugs
- Delays in testing software
- Knowledge silos around hardware setup
- Risk during competition preparation

### Goals
- Establish a **known-good, repeatable hardware baseline**
- Ensure the ASV can be powered on and tested reliably
- Reduce downtime caused by avoidable hardware issues

### Planned Actions
- Create a **complete hardware inventory**, including:
  - Sensors
  - Compute units
  - Power systems
  - Networking equipment
  - Actuators and propulsion
- Define a **standardized hardware configuration** for:
  - Bench testing
  - Dry runs
  - On-water testing
- Document:
  - Wiring diagrams
  - Power budgets
  - Connector types
  - Mounting locations
- Label and organize physical hardware
- Create checklists for:
  - Pre-test setup
  - Post-test teardown
  - Fault diagnosis

### Expected Outcome
Hardware becomes a **stable foundation**, not a recurring obstacle, enabling consistent firmware and software development.

---

## Firmware ##

### Problem Statement
Firmware and low-level system knowledge is currently concentrated in very few individuals. Electrical and hardware-oriented students often lack exposure to the full control stack, resulting in bottlenecks and underutilized manpower.

### Goals
- Distribute firmware and system-level knowledge across multiple members
- Empower electrical students to actively contribute beyond wiring and assembly
- Reduce dependency on any single firmware expert

### Planned Actions
- Structured training on:
  - Pixhawk configuration and tuning
  - MAVLink and vehicle communication
  - Thruster control and calibration
  - Networking (WiFi bullets, radios)
  - Jetson setup, flashing, and system management
- Documentation of:
  - Firmware flashing procedures
  - Configuration backups
  - Common failure modes
- Assign firmware ownership to **small sub-teams**, not individuals
- Encourage cross-training between electrical and software members

### Expected Outcome
Firmware becomes **maintainable, understandable, and resilient**, with multiple team members capable of diagnosing and fixing issues.

---

## Testing Tools ##

### Problem Statement
Testing is currently ad-hoc, manual, and poorly visualized. Bugs are often discovered late, and diagnosing failures requires deep system knowledge.

### Goals
- Enable faster iteration
- Improve observability of system behavior
- Catch failures earlier in development

### Planned Actions
- Develop internal tools for:
  - Telemetry visualization
  - Sensor data playback
  - Log inspection and analysis
- Improve simulation and dry-testing workflows
- Create scripts for:
  - Automated startup checks
  - Health monitoring
  - Regression testing
- Standardize data logging formats
- Provide simple dashboards for non-software members to understand system state

### Expected Outcome
Testing becomes **repeatable, data-driven, and accessible**, allowing the team to debug systematically instead of reactively.

---

## Rewriting Code ##

### Problem Statement
The current autonomy codebase is tightly coupled, poorly documented, and understood by only one former member. This represents a critical failure point and prevents meaningful contributions from new developers.

While a full rewrite is expensive in time and effort, continuing to build on an opaque system is unsustainable.

### Goals
- Eliminate single-person knowledge ownership
- Create a modular, documented, and maintainable codebase
- Enable new contributors to make meaningful changes quickly

### Planned Actions
- Audit the existing codebase to identify:
  - Core functionality worth preserving
  - Dead or redundant components
- Define a **clear architecture** for:
  - Autonomy
  - Perception
  - Navigation
  - Control
  - Interfaces
- Rewrite components incrementally where possible
- Emphasize:
  - Modularity
  - Clear interfaces
  - Strong documentation
- Require documentation alongside new code
- Ensure at least two members understand every major subsystem

### Expected Outcome
The autonomy stack becomes a **team-owned system**, not a legacy artifact, enabling faster progress and safer iteration.

---

## Revamping Our Socials ##

### Problem Statement
IcebergASV’s public presence does not accurately reflect the team’s current activity, professionalism, or ambitions. Outdated websites and inactive socials limit recruitment, sponsorship, and outreach.

### Goals
- Present IcebergASV as a serious, active engineering team
- Improve recruitment and visibility
- Strengthen sponsor and university relationships

### Planned Actions
- Retire or rebuild the existing website
- Create a clean, modern web presence with:
  - Team overview
  - Project highlights
  - Sponsorship information
  - Contact details
- Refresh Instagram content with:
  - Build progress
  - Testing updates
  - Competition highlights
- Increase presence at:
  - Public demos
  - University events
  - Outreach activities

### Expected Outcome
IcebergASV becomes **visible, credible, and approachable**, supporting growth beyond technical development.

---

## Github Code ##

### Problem Statement
The GitHub organization has accumulated legacy repositories, abandoned branches, and undocumented tools, creating confusion and slowing onboarding.

### Goals
- Make GitHub the central source of truth
- Improve clarity, maintainability, and collaboration
- Preserve institutional knowledge

### Planned Actions
- Remove or archive obsolete repositories
- Delete legacy and unused branches
- Standardize repository structure and naming
- Enforce:
  - README files
  - Documentation folders
  - Clear build instructions
- Adopt a formal Git workflow:
  - Protected branches
  - Pull requests
  - Code reviews
- Use GitHub Issues and Projects for task tracking
- Introduce basic CI checks where possible

### Expected Outcome
GitHub becomes a **reliable engineering platform**, not a historical dumping ground.

---

## Final Outcome

Project Titanic is not just a technical overhaul — it is a **cultural shift** toward documentation, redundancy, professionalism, and sustainability. By executing this plan, IcebergASV will transition from a fragile, personality-driven team into a **robust, scalable engineering organization** capable of long-term success.
