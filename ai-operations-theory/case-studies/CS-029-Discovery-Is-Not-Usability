# CS-029 Discovery Is Not Usability

## Overview

After establishing the Repository, the project began exploring how AI could assist with knowledge discovery.

External AI systems were assigned the role of **Scout**, responsible for finding opportunities to introduce repository content to relevant communities.

Initially, Discovery was treated primarily as a search problem.

However, long-term operation revealed that successful discovery did not necessarily produce usable operational outcomes.

This case documents how the project distinguished **Discovery** from **Usability** as separate operational stages.

---

## Initial Assumption

The original operational model was relatively simple.

```text
Search
        ↓
Relevant Post
        ↓
Comment
        ↓
Repository Discovery
```

The underlying assumption was straightforward.

If relevant discussions could be found, repository dissemination would naturally follow.

---

## Operational Reality

Actual operation revealed a different reality.

Many discovered candidates could not be used despite being topically relevant.

Examples included:

* Archived Reddit posts
* Locked comment sections
* Previously processed discussions
* Weak contextual relevance
* Unverified comment availability
* Situations where repository introduction would appear unnatural

Discovery frequently succeeded.

Operational deployment frequently failed.

---

## Observation

The project gradually recognized that Discovery consisted of multiple operational stages rather than a single activity.

```text
Search
        ↓
Candidate Discovery
        ↓
Requirement Verification
        ↓
Usable Candidate
        ↓
Operational Deployment
```

Search alone was insufficient.

Candidates required operational verification before they became usable.

---

## Failure Patterns

Two recurring failure patterns emerged.

### Requirement Failure

The Scout successfully located relevant discussions.

However, explicit operational requirements were not satisfied.

Example:

**Requirement**

> Only return posts that are still open for comments.

**Observed Result**

* Archived discussions included
* Locked discussions included
* Comment availability uncertain

Discovery succeeded.

Requirement verification failed.

---

### Discovery Duplication

Previously processed discussions were repeatedly returned as new recommendations.

Although discovery technically occurred, no new operational opportunity was created.

The project therefore distinguished:

```text
New Discovery

and

Repeated Discovery
```

Only the former generated operational value.

---

## Decision Context

These observations changed how the Scout role was defined.

Originally, the Scout was expected to maximize discovery.

After operational experience, its objective became different.

The Scout should maximize **usable discoveries**, not discovered candidates.

Operational success therefore depended on both:

* Discovery quality
* Requirement satisfaction

---

## Relation to AI Operations Theory

AI Operations Theory separates Repository from Discovery.

This case further suggests that Discovery itself contains multiple operational layers.

```text
Discovery
        ↓
Verification
        ↓
Operational Use
```

Discovery should therefore be viewed as an operational workflow rather than a simple search function.

---

## Working Observation

> Discovery should be evaluated by usable operational outcomes rather than the number of discovered candidates.

Finding information does not necessarily produce operational value.

Operational value emerges only after discovered information satisfies the requirements necessary for practical use.

---

## Key Takeaways

* Discovery and Usability are different operational stages.
* Search success does not guarantee operational usefulness.
* Requirement verification is part of Discovery operations.
* Duplicate discoveries reduce operational efficiency.
* Scout responsibilities include verification, not only discovery.
* Operational success should be measured by usable outcomes rather than candidate quantity.
