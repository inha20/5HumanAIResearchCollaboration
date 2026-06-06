# AI Research Handover Protocol (ARHP)

> **Paper Integration Note**
> This document has been integrated into `paper.md` (Sections 8.11–8.13).
> It is preserved here as an independent reference for potential future extraction or standalone use.

---

## Abstract

AI Research Handover Protocol (ARHP) is a practical framework for transferring research continuity between humans, AI systems, and future collaborators.

The protocol was developed through observations gathered during long-term Human-AI research collaboration. ARHP addresses the **AI Replacement Problem**: research often depends on participants that may disappear, change, or lose access to prior context.

ARHP proposes that successful handover does not require transferring memory. Instead, it requires transferring **recoverable context**.

Building upon Human-AI Context Transfer Theory (HACTT), ARHP focuses on the operational question of how context should be organized, documented, and transferred in order to preserve continuity across participants and time.

---

# 1. The AI Replacement Problem

Research programs frequently outlive individual AI sessions, AI systems, and human work sessions.

A common failure pattern occurs when a new collaborator receives information but cannot reconstruct the context necessary to continue work.

Examples include:

- An AI session reaching its context limit.
- A researcher returning after weeks or months.
- Migration between AI systems.
- Repository ownership changes.
- Long-term research programs involving multiple collaborators.

ARHP therefore focuses on **continuity** rather than memory persistence.

---

# 2. Design Principles

## Principle 1: Continuity over Memory

Long-term collaboration should not depend on preserving the internal memory of a specific participant.

Continuity should emerge from externalized artifacts rather than persistent memory.

## Principle 2: Recoverability over Storage

Large amounts of stored information are less valuable than information that can be efficiently reconstructed.

The objective is not maximum storage but **minimum reconstruction cost**.

## Principle 3: Repository-Centered Collaboration

Repositories should function as collaboration infrastructure rather than simple storage locations.

A repository should help future collaborators understand:

- Why the project exists.
- What has been completed.
- What remains unfinished.
- What should happen next.

## Principle 4: Context Externalization

Critical context should be externalized into artifacts that survive participant replacement.

Knowledge that exists only inside a participant represents a continuity risk.

---

# 3. Minimum Handover Package

ARHP adopts the Minimum Context Unit proposed by HACTT.

A successful handover should include four elements.

## Goal

Why does the project exist?

## State

What is the current condition of the project?

## History

How did the project reach its current state?

## Next Action

What should happen next?

A handover missing any of these elements increases reconstruction cost.

---

# 4. Required Artifacts

## README

Provides project purpose and high-level orientation.

A collaborator should understand the project's purpose within minutes.

## STATUS

Describes current progress and active work.

STATUS answers: *Where are we now?*

## Research Log

Preserves important decisions, observations, failures, and reasoning.

Research logs reduce repeated investigation.

## NEXT_ACTION

Defines recommended continuation steps.

NEXT_ACTION reduces ambiguity and startup cost.

## Handover Document

Provides a concise summary intended specifically for incoming collaborators.

A handover document functions as an entry point into the larger repository.

---

# 5. Handover Workflow

## Human → AI

```
Human
  ↓
Repository
  ↓
AI
```

Humans externalize context into artifacts. AI reconstructs context from those artifacts.

## AI → Human

```
AI
  ↓
Artifact
  ↓
Human
```

AI-generated outputs become context-preserving artifacts.

## AI → AI

```
AI A
  ↓
Repository
  ↓
AI B
```

Continuity emerges from transferred context rather than direct memory transfer.

## Human → Future Self

```
Present Self
     ↓
  Artifact
     ↓
Future Self
```

Future-Self Collaboration is a special case of handover.

---

# 6. Handover Quality Model

The quality of a handover can be evaluated according to the amount of recoverable context available to the incoming collaborator.

## Level 0 — No Context

Only isolated information exists. Continuation is unlikely without substantial independent reconstruction.

*Example:* "Work on the project."

## Level 1 — Goal Only

The purpose of the project is known. Current state and continuation path remain unclear.

*Example:* "Build a Human-AI collaboration theory."

## Level 2 — Goal + State

The purpose and current condition are known. Reconstruction remains expensive because historical reasoning is missing.

## Level 3 — Goal + State + History

Past decisions can be reconstructed. However, future direction remains uncertain. The incoming collaborator understands what happened but not what should happen next.

## Level 4 — Recoverable Context

Goal, State, History, and Next Action are all available. A new collaborator can recover sufficient context to continue work.

**Recoverable Context represents the minimum target level recommended by ARHP for any research transition.**

## Level 5 — Executable Continuity

The incoming collaborator can immediately perform productive work with minimal reconstruction effort.

Characteristics include:

- Clear and navigable repository structure.
- Documentation that is current and consistent with actual project state.
- Explicit and actionable next steps.
- Accessible and cross-referenced supporting artifacts.
- No significant reconstruction required before productive contribution can begin.

**Executable Continuity represents the highest practical handover quality.**

---

# 7. Failure Modes

## Missing Goal

Work continues without direction. Participants may remain active while progress stalls.

## Missing State

Current progress becomes unclear. Work may be duplicated or abandoned unnecessarily.

## Missing History

Important reasoning and decisions become difficult to reconstruct. Participants may repeat previously rejected approaches.

## Missing Next Action

Continuation becomes uncertain. Projects often stall despite having sufficient information.

## Repository Drift

Repository Drift occurs when documentation no longer accurately represents the actual state of the project.

```
README  ≠  Current Project State
```

As Repository Drift increases:

- Reconstruction cost increases.
- Handover quality decreases.
- Collaboration efficiency declines.

Preventing Repository Drift is therefore a critical maintenance activity in long-term Human-AI collaboration.

---

# 8. Real Handover Cases

## Multi-AI Research Continuity

A research program may continue across multiple AI systems when context is externalized into repositories and handover artifacts.

```
ChatGPT
   ↓
Repository
   ↓
Claude
   ↓
Repository
   ↓
ANTIGRAVITY
```

The continuity of the research program depends less on any individual AI system and more on the quality of transferred context.

## Human → Future Self Collaboration

Researchers frequently create notes, logs, TODO lists, research summaries, and repository documents for future versions of themselves.

ARHP interprets these artifacts as handover mechanisms across time.

Future-Self Collaboration is therefore a special case of Human-AI Context Transfer.

---

# 9. Relationship to HACTT

HACTT explains **what** must be transferred. ARHP explains **how** that transfer should be organized.

```
HACTT
  ↓
What must move?
  ↓
ARHP
  ↓
How should it move?
```

The two frameworks are complementary. HACTT provides theoretical foundations. ARHP provides operational guidance.

---

# 10. Protocol Checklist

Before concluding a research session:

- [ ] Is the project goal documented?
- [ ] Is the current state documented?
- [ ] Is relevant history preserved?
- [ ] Is the next action identified?
- [ ] Are artifacts updated?
- [ ] Can a new collaborator continue the work?
- [ ] Has Repository Drift been minimized?

If the answer to any question is "No," handover quality may be reduced.

---

# Conclusion

A successful AI handover does not require transferring memory.

It requires transferring **recoverable context**.

ARHP provides a practical framework for preserving continuity across humans, AI systems, repositories, and future collaborators.

The ultimate objective of ARHP is not documentation itself, but the achievement of **Executable Continuity**: a state in which productive collaboration can continue despite participant replacement.
