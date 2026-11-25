
# Gonzalo Montero · Arquitectura Simbiótica (AS)

What happens when we work with people, AI, agents, and tools, but it becomes increasingly difficult to understand what is happening, what has changed, or how to intervene?

A task can begin with a simple intention and pass through many decisions, actions, and transformations. Different participants use tools, produce results, and leave information that others need to continue the work.

Along the way, difficulties can arise: losing context, not knowing what has been verified, being unable to stop an operation, or not understanding how a result was reached.

Arquitectura Simbiótica is my research and design practice for addressing problems like these and building more habitable environments: spaces where people and systems can find their bearings, act, understand what is happening, and retain the ability to intervene and continue.

This space brings together part of that research: experiments, structural mechanisms, execution systems, protocols, and tools addressing specific problems. Some are completed experiments preserved for examination; others are executable or reusable mechanisms. Each repository allows visitors to explore their behavior, results, and limitations.

---

## Explore the Work

**Where to start:** [Run a STOPPER example](https://github.com/gamc-core/STOPPER#try) to see what happens when a stop is requested, [examine evidence with AWR](https://github.com/gamc-core/AWR-AI-WORK-RECEIPT), or [explore CPR's regulation experiments](#cpr--conditions-of-operational-regulation).

---

| Area | Question addressed |
|---|---|
| [**CE**](#ce--conditions-of-executability) | How can persistent structures be recorded, closed, and continued? |
| [**CPR**](#cpr--conditions-of-operational-regulation) | When should an intervention occur, withdraw, or be reconsidered? |
| [**AF**](#af--artifact-qualification) | What conditions allow an artifact to be recognized and validated? |
| [**ENDO**](#endo--execution-history) | How can the trajectory of an execution be preserved and reconstructed? |
| [**AWR**](#awr--ai-work-receipt) | What can be independently checked about delegated work? |
| [**STOPPER**](#stopper--cooperative-stopping) | What actually stopped after a stop request? |

Each area retains its own scope. They do not constitute a mandatory technical sequence.

---

## Published Artifacts

Dates indicate documented development or execution periods, not necessarily publication dates on GitHub.

### CE — Conditions of Executability

Mechanisms for recording, closing, and continuing structures while preserving their history.

**Recording → closure → continuity**

| Artifact | Question | Type | Developed |
|---|---|---|---|
| [CE-01](https://github.com/gamc-core/CE01-executable-structural-cell) | How can a persistent, verifiable unit be recorded? | Persistent structural unit mechanism | Mar 2026 |
| [CE-02](https://github.com/gamc-core/CE02-Deterministic-Cycle-Engine) | How can a set of units be closed under an explicit condition? | Deterministic cycle engine | Mar 2026 |
| [CE-03](https://github.com/gamc-core/CE03-Generational-Structural-Runtime) | How can execution continue without modifying what has already been closed? | Generational structural runtime | Mar 2026 |

---

### CPR — Conditions of Operational Regulation

Experiments examining how a regulator responds to different operational states in a real Windows environment.

**Intervention → withdrawal → recovery → saturation → reconsideration**

| Artifact | Question | Type | Developed |
|---|---|---|---|
| [CPR-006](https://github.com/gamc-core/CPR-006-Homeostatic-regulation-with-structural-distinction) | Where should an intervention occur when the dominant cause must not be modified directly? | Operational regulation experiment | Feb 2026 |
| [CPR-009](https://github.com/gamc-core/CPR-009-Baseline-relative-withdrawal) | When should an intervention be withdrawn? | Operational regulation experiment | Feb 2026 |
| [CPR-013](https://github.com/gamc-core/CPR-013-Confirmed-recovery-dissipative-memory) | When can a system be considered recovered? | Operational regulation experiment | Feb 2026 |
| [CPR-014](https://github.com/gamc-core/CPR-014-Operational-Saturation-Clamp) | When does continued intervention cease to make sense? | Operational regulation experiment | Feb 2026 |
| [CPR-015](https://github.com/gamc-core/CPR-015-Post-clamp-meta-regulation) | When should a previous halt be reconsidered? | Operational regulation experiment | Feb 2026 |

---

### AF — Artifact Qualification

Conditions for recognizing a unit as an artifact and verifying whether those conditions are satisfied.

**Protocol → validation**

| Artifact | Question | Type | Developed |
|---|---|---|---|
| [AF01](https://github.com/gamc-core/AF01-Artifact_Structural_Protocol) | What conditions must a unit satisfy to qualify as an artifact? | Structural qualification protocol | Apr 2026 |
| [AF02](https://github.com/gamc-core/AF02-Artifact-Validator-Engine) | How can those conditions be verified deterministically? | Python structural validator | Apr 2026 |

---

### ENDO — Execution History

An observable window into a persistent execution system with generational closure. Each generation preserves records, states, and derived artifacts without modifying what has already been closed.

The public repository allows its execution history and reconstruction paths to be examined.

**Recording → generation → trajectory**

| Repository | Question | Type | Developed |
|---|---|---|---|
| [ENDO](https://github.com/gamc-core/ENDO) | What can be reconstructed from an execution after it has been recorded and closed? | Preserved execution history | Mar–Jun 2026 |

---

### AWR — AI Work Receipt

An experimental format and offline verifier for examining evidence of AI-assisted and other delegated work.

It distinguishes what can be checked, what is recorded, and what remains unknown, without requiring access to the original working environment.

**Delegated work → evidence → verification**

| Repository | Question | Type | Developed |
|---|---|---|---|
| [AWR](https://github.com/gamc-core/AWR-AI-WORK-RECEIPT) | What can be independently checked about delegated work? | Evidence format and offline verifier | Sep 2026 |

---

### STOPPER — Cooperative Stopping

A small Python library developed from problems observed while building and testing DOJO, an environment within Arquitectura Simbiótica.

STOPPER distinguishes a request to stop, the worker's response, and what actually happened. Five executable examples allow these differences to be examined through controlled operations.

**Stop request → cooperation → observable outcome**

| Repository | Question | Type | Developed |
|---|---|---|---|
| [STOPPER 0.1](https://github.com/gamc-core/STOPPER) | What actually stopped after a stop request? | Cooperative-stop Python library | Nov 2026 |

---

## Scope

This collection is a public, examinable part of Arquitectura Simbiótica. It does not represent the entirety of its research and practice.

Private records and materials remain outside this publication.

The published constructions serve different purposes and have different degrees of independence. They are not necessarily components of a single integrated system.

---

**GAMC · Lima, Peru**

[LinkedIn](https://www.linkedin.com/in/gonzalo-montero-69285645/)
