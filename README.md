
# Gonzalo Montero · Arquitectura Simbiótica (AS)

> Experimental mechanisms for execution, verification, continuity, and reconstruction.

I am interested in how intentions take form, undergo transformations, and continue without losing their history.

Part of my research involves building and testing mechanisms to record executions, verify their conditions, and preserve enough information to understand what happened, what changed, and how to continue.

The problem is not merely producing a result. When the history of how it was produced is lost, decisions become difficult to review, systems become difficult to maintain, and work becomes difficult to continue.

The published mechanisms explore how to preserve and verify these conditions through executable prototypes, bounded experiments, and evidence of their results and limitations.

---

## An Evolving Research Effort

The published families reflect different questions that have gradually expanded the research.

Each family addresses a specific dimension of the problem, with its own experimental mechanisms and conditions.

| Family | Question Addressed |
|---|---|
| [**CE**](#ce--conditions-of-executability) | How can persistent structures be recorded, closed, and continued? |
| [**CPR**](#cpr--conditions-of-operational-regulation) | When should an intervention occur, withdraw, recover, or be reconsidered? |
| [**AF**](#af--artifact-qualification) | What conditions allow an artifact to be recognized and validated? |
| [**ENDO**](#endo--execution-history) | How can the trajectory of an execution be preserved and reconstructed? |

These families do not constitute a mandatory technical sequence. Each retains its own scope, and its results correspond to the conditions under which it was executed.

Together, they form part of a broader exploration: **how to bring together people, AI, agents, and tools to create, intervene, verify, and continue work without losing orientation, boundaries, or the capacity to make decisions.**

The research also continues through mechanisms and environments that are not yet part of this publication.

---

## Published Artifacts

### CE — Conditions of Executability

Minimal mechanisms for recording, closing, and continuing structures while preserving their history.

**Recording → closure → continuity**

| Artifact | Question |
|---|---|
| [CE-01](https://github.com/gamc-core/CE01-executable-structural-cell) | How can a persistent, verifiable unit be recorded? |
| [CE-02](https://github.com/gamc-core/CE02-Deterministic-Cycle-Engine) | How can a set of units be closed under an explicit condition? |
| [CE-03](https://github.com/gamc-core/CE03-Generational-Structural-Runtime) | How can execution continue without modifying what has already been closed? |

---

### CPR — Conditions of Operational Regulation

Experimental executions to observe how a regulator responds to different operational states.

The artifacts preserve conditions observed in a real Windows environment.

**Intervention → withdrawal → recovery → saturation → reconsideration**

| Artifact | Question |
|---|---|
| [CPR-006](https://github.com/gamc-core/CPR-006-Homeostatic-regulation-with-structural-distinction) | Where should an intervention occur when the dominant cause must not be modified directly? |
| [CPR-009](https://github.com/gamc-core/CPR-009-Baseline-relative-withdrawal) | When should an intervention be withdrawn? |
| [CPR-013](https://github.com/gamc-core/CPR-013-Confirmed-recovery-dissipative-memory) | When can a system be considered recovered? |
| [CPR-014](https://github.com/gamc-core/CPR-014-Operational-Saturation-Clamp) | When does continued intervention cease to make sense? |
| [CPR-015](https://github.com/gamc-core/CPR-015-Post-clamp-meta-regulation) | When should a previous halt be reconsidered? |

---

### AF — Artifact Qualification

Conditions and mechanisms for determining whether a unit qualifies as an artifact and verifying that qualification.

**Protocol → validation**

| Artifact | Question |
|---|---|
| [AF01](https://github.com/gamc-core/AF01-Artifact_Structural_Protocol) | What conditions must a unit satisfy to qualify as an artifact? |
| [AF02](https://github.com/gamc-core/AF02-Artifact-Validator-Engine) | How can those conditions be verified deterministically? |

---

### ENDO — Execution History

An observable window into the history recorded by a persistent execution system with generational closure.

Each generation preserves records, states, and derived artifacts without modifying what has already been closed.

**Recording → generation → trajectory**

| Repository | Question |
|---|---|
| [ENDO](https://github.com/gamc-core/ENDO) | What can be reconstructed from an execution after it has been recorded and closed? |

---

## Scope and Limitations

The published artifacts remain accessible in the state in which they were closed.

This public layer brings together mechanisms, executions, and evidence obtained under specific conditions.

**It does not represent the complete architecture of Arquitectura Simbiótica, nor does it constitute a collection of finished products.**

The documented results correspond to their execution contexts. They do not establish general validity or guarantee the same behavior in other environments.

Other families and mechanisms remain under research, documentation, or preparation for publication.

---

**GAMC · Lima, Peru**

[LinkedIn](https://www.linkedin.com/in/gonzalo-montero-69285645/)
