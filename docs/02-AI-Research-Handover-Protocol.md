# AI Research Handover Protocol (ARHP)

## Abstract

AI Research Handover Protocol (ARHP) is a practical framework for transferring research continuity between humans, AI systems, and future collaborators.

The protocol was developed through observations gathered during long-term Human-AI research collaboration. ARHP addresses the AI Replacement Problem: research often depends on participants that may disappear, change, or lose access to prior context.

ARHP proposes that successful handover does not require transferring memory. Instead, it requires transferring recoverable context.

---

# 1. The AI Replacement Problem

Research programs frequently outlive individual AI sessions, AI systems, and human work sessions.

A common failure pattern occurs when a new collaborator receives information but cannot reconstruct the context necessary to continue work.

ARHP therefore focuses on continuity rather than memory persistence.

---

# 2. Design Principles

## Principle 1: Continuity over Memory

Long-term collaboration should not depend on preserving the internal memory of a specific participant.

## Principle 2: Recoverability over Storage

Large amounts of stored information are less valuable than information that can be efficiently reconstructed.

## Principle 3: Repository-Centered Collaboration

Repositories should function as collaboration infrastructure rather than simple storage locations.

## Principle 4: Context Externalization

Critical context should be externalized into artifacts that survive participant replacement.

---

# 3. Minimum Handover Package

ARHP adopts the Minimum Context Unit proposed by HACTT.

A successful handover should include:

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

## STATUS

Describes current progress and active work.

## Research Log

Preserves important decisions, observations, and reasoning.

## NEXT_ACTION

Defines recommended continuation steps.

## Handover Document

Provides a concise summary intended for incoming collaborators.

---

# 5. Handover Workflow

## Human → AI

Human
↓
Repository
↓
AI

## AI → Human

AI
↓
Artifact
↓
Human

## AI → AI

AI A
↓
Repository
↓
AI B

## Human → Future Self

Present Self
↓
Artifact
↓
Future Self

---

# 6. Handover Quality Levels

## Level 0: No Context

Only isolated information is available.

Continuation is unlikely.

## Level 1: Partial Context

Some context components are available.

Continuation is possible but expensive.

## Level 2: Recoverable Context

Goal, State, History, and Next Action are available.

Continuation is achievable with moderate effort.

## Level 3: Research Continuity

The incoming collaborator can resume productive work with minimal reconstruction.

---

# 7. Failure Modes

## Missing Goal

Work continues without direction.

## Missing State

Current progress becomes unclear.

## Missing History

Important reasoning and decisions become difficult to reconstruct.

## Missing Next Action

Continuation becomes uncertain.

## Repository Drift

Documentation and actual project state diverge over time.

---

# 8. Relationship to HACTT

HACTT explains what must be transferred.

ARHP explains how that transfer should be organized.

HACTT
↓
What must move?
↓
ARHP
↓
How should it move?

---

# 9. Protocol Checklist

Before concluding a research session:

- Is the project goal documented?
- Is the current state documented?
- Is relevant history preserved?
- Is the next action identified?
- Are artifacts updated?
- Can a new collaborator continue the work?

---

# Conclusion

A successful AI handover does not require transferring memory.

It requires transferring recoverable context.

ARHP provides a practical framework for preserving continuity across humans, AI systems, repositories, and future collaborators.