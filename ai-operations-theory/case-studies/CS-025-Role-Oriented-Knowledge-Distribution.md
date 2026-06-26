# CS-025 Role-Oriented Knowledge Distribution

## Overview

Once operational roles became specialized, another operational challenge emerged.

Not every role required the same information.

Providing every operational role with the entire repository increased cognitive load, while providing too little information reduced decision quality.

Instead of distributing information uniformly, information was allocated according to each operational role's responsibilities.

---

## Background

Initially, all operational knowledge was effectively shared across the project.

As the repository expanded, this approach became increasingly inefficient.

Different operational roles repeatedly required different kinds of information.

This observation led to an important operational principle:

> Information should be distributed according to operational responsibility rather than completeness.

---

## Observation

Two different dimensions of information gradually became apparent.

The first concerned **information lifetime**.

* Persistent operational knowledge
* Temporary runtime state

The second concerned **operational responsibility**.

Different operational roles required different combinations of these information types.

The goal was not to maximize information availability.

The goal was to maximize decision quality while minimizing unnecessary cognitive load.

---

## Information Allocation

The resulting operational model was as follows.

| Operational Role | Persistent Knowledge | Runtime State |
| ---------------- | -------------------- | ------------- |
| Research         | ✓                    | ✓             |
| Operations       | —                    | ✓             |
| Strategy         | ✓                    | ✓             |
| Protocol         | ✓                    | —             |

Each allocation reflected operational necessity rather than organizational hierarchy.

---

## Why the Allocation Worked

### Research

Research required both long-term knowledge and current operational context.

It continuously evaluated whether new observations remained consistent with previous knowledge.

---

### Operations

Operations focused on execution.

Current drafts, pending work, runtime context, and immediate tasks were essential.

Historical operational knowledge was generally unnecessary for day-to-day execution.

---

### Strategy

Strategy required both perspectives.

Long-term repository structure provided direction, while runtime information allowed strategic decisions to reflect the project's current state.

---

### Protocol

Protocol focused on operational governance.

It evaluated incidents, operational rules, constitutional consistency, and repository evolution.

Current runtime tasks were generally unnecessary.

Instead, Protocol evaluated operational outcomes after they occurred.

---

## Operational Principle

The objective was never to provide every role with every piece of information.

Instead, each role received only the information necessary to perform its operational responsibility effectively.

Reducing unnecessary information became just as important as preserving necessary information.

---

## Key Insight

Information architecture should be designed around **decision responsibility**, not information ownership.

Different operational roles require different information lifecycles.

Providing identical information to every role may increase cognitive overhead without improving decision quality.

---

## Relation to AI Operations Theory

This observation extended the previous organizational evolution.

Once operational roles had emerged (CS-024), information architecture naturally evolved alongside them.

Operational specialization was therefore accompanied by information specialization.

The repository evolved not only through new knowledge, but also through increasingly effective information distribution.

---

## Key Takeaways

* Operational roles do not require identical information.
* Information should be distributed according to operational responsibility.
* Persistent knowledge and runtime state serve different operational purposes.
* Reducing unnecessary information improves operational efficiency.
* Information architecture evolves together with organizational structure.
