# Abstract

Long-term Human-AI collaboration presents challenges that extend beyond the capabilities of either human memory or AI memory alone. While recent research has focused primarily on model performance, prompt engineering, and short-term task completion, relatively little attention has been given to research continuity across extended periods of time.

This study investigates long-term Human-AI research collaboration through a multi-repository research program involving multiple AI systems, repository infrastructure, documentation artifacts, and external memory mechanisms. The study is based on observations collected during the development of a research program consisting of interconnected repositories, including mathematical theory development, structure recognition research, and Human-AI collaboration analysis.

The findings suggest that successful long-term collaboration depends heavily on the preservation, restoration, and transfer of research context. Several key concepts emerged during the study, including Externalized Memory, Distributed Research Memory, Context Transfer, Human-AI Working Agreements, and Future-Self Collaboration. Together, these concepts describe mechanisms through which research continuity can be maintained despite context-window limitations, token constraints, session boundaries, and transitions between AI systems.

The study further examines repository-centered research workflows, AI-to-AI handover practices, and the role of documentation as a context transfer mechanism rather than a simple storage medium. The results indicate that research continuity emerges from interactions among humans, AI systems, repositories, documentation artifacts, and reminder systems rather than from any single memory source.

Based on these observations, the study proposes that long-term Human-AI collaboration is fundamentally a problem of research continuity. Effective collaboration depends not on perfect memory, but on the construction of systems that preserve and transfer context across time, sessions, and participants.

Keywords: Human-AI Collaboration, Externalized Memory, Distributed Research Memory, Context Transfer, AI-to-AI Handover, Research Continuity, Knowledge Management, Long-Term Research Programs

# 1. Introduction

## 1.1 Motivation

Recent advances in Large Language Models (LLMs) have enabled new forms of Human-AI collaboration.

Most existing discussions focus on short-term interactions, task completion, or isolated conversations.

However, many real-world research projects extend across months or years and require continuity beyond a single session.

In such environments, neither human memory nor AI memory alone is sufficient to preserve the complete research context.

This raises a fundamental question:

> How can humans and AI systems collaborate effectively in long-term research programs?

The present study emerged from a multi-repository research program involving mathematical theory development, repository-based knowledge management, and collaboration with multiple AI systems.

Throughout this process, challenges related to memory preservation, context loss, token limitations, and AI transitions repeatedly appeared.

These observations motivated a systematic investigation of long-term Human-AI collaboration.

---

## 1.2 Research Problem

Long-term research differs significantly from short-term problem solving.

Research continuity requires the preservation and restoration of knowledge across:

- Time
- Sessions
- Devices
- Repositories
- AI systems

Existing AI systems operate within finite context windows and are unable to maintain complete long-term memory.

Human researchers face similar limitations due to forgetting, interruptions, and cognitive constraints.

As a result, long-term collaboration requires mechanisms that extend beyond the memory capabilities of individual participants.

This study investigates how such mechanisms emerge and how they support research continuity.

---

## 1.3 Research Questions

This study addresses the following questions.

### RQ1

How can research context be preserved across long-term Human-AI collaboration?

### RQ2

How can context be transferred across different AI systems, sessions, and time periods?

### RQ3

What role do repositories, documentation, and handover artifacts play in research continuity?

### RQ4

How do collaboration protocols emerge during long-term Human-AI interaction?

---

## 1.4 Contributions

This study makes four primary contributions.

### Contribution 1

It presents a real-world case study of long-term Human-AI collaboration conducted over multiple repositories and AI systems.

### Contribution 2

It introduces the concept of Externalized Memory as a framework for understanding context preservation beyond human and AI memory.

### Contribution 3

It identifies Human-AI Working Agreements as recurring collaboration protocols that support memory preservation and context recovery.

### Contribution 4

It proposes a model of Distributed Research Memory in which research knowledge is distributed across humans, AI systems, repositories, documentation, and reminder systems.

---

## 1.5 Scope

This study does not attempt to evaluate the intelligence of AI systems.

Instead, it focuses on collaboration processes.

The primary objective is to understand how research continuity can be achieved despite memory limitations and context fragmentation.

Accordingly, the emphasis is placed on:

- Knowledge preservation
- Context transfer
- Collaboration protocols
- Repository-based research management
- Long-term Human-AI interaction

rather than model performance benchmarks.

---

## 1.6 Overview of the Study

The remainder of this paper is organized as follows.

Chapter 4 introduces the concept of Externalized Memory.

Chapter 7 describes the architecture of long-term research programs.

Chapter 8 presents empirical case studies collected during the development of the Minor Thesis research program.

Chapter 9 discusses the implications of these observations for Human-AI collaboration research.

Finally, Chapter 10 summarizes the findings and proposes directions for future work.

# 2. Background

## 2.1 Human-AI Collaboration

Recent advances in Large Language Models (LLMs) have enabled new forms of Human-AI collaboration.

AI systems are increasingly used for:

- Writing assistance
- Software development
- Data analysis
- Research support
- Knowledge management

Most existing discussions focus on task completion, productivity gains, or conversational performance.

However, relatively little attention has been given to long-term research collaboration extending across multiple sessions, repositories, and AI systems.

This study focuses specifically on that long-term perspective.

---

## 2.2 Context Window Limitations

Modern AI systems operate within finite context windows.

As conversations become longer, earlier information may become unavailable or difficult to recover.

This creates challenges for long-term projects.

Examples include:

- Loss of historical decisions
- Repeated explanations
- Reconstructed reasoning
- Context fragmentation

As project duration increases, context preservation becomes increasingly important.

The present study treats context limitations not merely as technical constraints but as collaboration constraints.

---

## 2.3 Knowledge Preservation

Long-term research depends on the preservation of knowledge.

Historically, researchers have relied on:

- Laboratory notebooks
- Research journals
- Technical reports
- Reference archives

These artifacts preserve information beyond the limits of human memory.

The emergence of AI-assisted research introduces new challenges because knowledge must now be preserved not only for humans but also for AI systems participating in the research process.

---

## 2.4 Repository-Based Research

Software engineering has long relied on repositories for preserving code and project history.

Repositories provide:

- Persistent storage
- Version control
- Collaboration support
- Historical traceability

In this study, repositories expanded beyond their traditional role.

GitHub repositories became:

- Knowledge archives
- Research memory systems
- Handover platforms
- Collaboration interfaces

As a result, repository infrastructure played a central role in sustaining research continuity.

---

## 2.5 Human-AI Memory Asymmetry

Humans and AI systems possess fundamentally different memory characteristics.

Human researchers typically possess:

### Strengths

- Long-term experiential memory
- Intuition
- Goal persistence
- Conceptual understanding

### Limitations

- Forgetting
- Incomplete recall
- Cognitive overload

AI systems typically possess:

### Strengths

- Rapid retrieval within active context
- Large-scale text processing
- Pattern recognition

### Limitations

- Session boundaries
- Context window limits
- Lack of persistent memory

Long-term collaboration therefore requires mechanisms that compensate for both types of limitations.

---

## 2.6 Multi-Agent Research Environments

The research program examined in this study involved multiple AI systems.

Examples included:

- ChatGPT
- Claude
- ANTIGRAVITY

Each system participated at different stages of the research process.

The involvement of multiple AI systems introduced additional challenges:

- Context transfer
- Knowledge consistency
- Handover management
- Documentation quality

These challenges motivated the development of structured collaboration practices.

---

## 2.7 From Information Storage to Context Transfer

Traditional knowledge management often focuses on information storage.

However, observations from this study suggest that storage alone is insufficient.

The critical problem is not whether information exists.

The critical problem is whether context can be restored when needed.

As a result, the study emphasizes Context Transfer rather than simple information retention.

Under this perspective:

- README files
- Research logs
- Handover documents
- Repository structures
- Reminder systems

are viewed primarily as context transfer mechanisms.

---

## 2.8 Research Gap

Existing Human-AI collaboration literature frequently investigates:

- Task performance
- User satisfaction
- Prompt engineering
- Human oversight

However, fewer studies examine:

- Long-term collaboration
- Research continuity
- AI-to-AI handover
- Future-self collaboration
- Repository-centered research workflows
- Distributed research memory

The present study addresses this gap through a case study of a multi-repository, multi-AI research program.

---

## 2.9 Conceptual Foundation

Three concepts provide the foundation for this study.

### Externalized Memory

Research context preserved outside both human memory and active AI context.

### Distributed Research Memory

Research memory distributed across humans, AI systems, repositories, and artifacts.

### Context Transfer

The process through which research context moves across time, sessions, systems, and collaborators.

These concepts are developed further in subsequent chapters.

# 3. Research Environment

## 3.1 Overview

This study was conducted within an active long-term research program involving a human researcher, multiple AI systems, repository infrastructure, and external memory artifacts.

Unlike controlled laboratory experiments, the research environment emerged organically during the development of multiple interconnected research projects.

The objective of this chapter is to describe the components that participated in the collaboration process.

---

## 3.2 Human Researcher

The central participant was a human researcher responsible for:

- Defining research goals
- Identifying research problems
- Evaluating hypotheses
- Organizing repositories
- Coordinating AI systems
- Preserving long-term objectives

Although AI systems contributed extensively throughout the research process, strategic direction remained under human control.

The human researcher also functioned as the primary integrator of knowledge generated across multiple systems.

---

## 3.3 AI Systems

Multiple AI systems participated in the research program.

Each system contributed different capabilities.

### ChatGPT

Primary functions included:

- Research discussion
- Theory development
- Conceptual analysis
- Research planning
- Context integration

ChatGPT frequently acted as a coordination layer connecting ideas originating from different repositories and conversations.

---

### Claude

Primary functions included:

- Repository organization
- Documentation refinement
- Structural editing
- Research asset management

Claude was often used for repository-scale operations and document restructuring.

---

### ANTIGRAVITY

Primary functions included:

- Large-scale repository analysis
- Bulk document processing
- Long-form generation tasks

ANTIGRAVITY was frequently utilized when processing large collections of files and repositories.

---

### Future AI Systems

The research architecture was intentionally designed to remain compatible with future AI systems.

Consequently, documentation practices emphasized portability and system-independent knowledge preservation.

---

## 3.4 Repository Infrastructure

GitHub repositories served as the primary persistent storage environment.

The repository structure gradually evolved into a research program architecture.

Major repositories included:

### Research Repositories

1. 1KMapStructureInvariance
2. 2SymmetricBooleanFunctionMinorThesis
3. 3VariableRearrangementInvarianceMinorThesis
4. 4StructureRecognitionTheory
5. 5HumanAIResearchCollaboration

### Supporting Repositories

- Research Portfolio
- ANTIGRAVITY

Together, these repositories formed the persistent knowledge infrastructure of the research program.

---

## 3.5 Documentation Systems

Documentation artifacts played a central role in preserving research continuity.

Examples included:

### README Files

Provided repository-level context.

### Handover Documents

Enabled context transfer between AI systems.

### Research Logs

Recorded observations and progress over time.

### Status Reports

Summarized the current state of ongoing work.

### Repository Descriptions

Provided high-level explanations of repository purpose and relationships.

These documents collectively formed a large portion of the Externalized Memory system.

---

## 3.6 Project Memory Systems

Project-based memory systems were used to preserve recurring observations and research insights.

Examples included:

- Research hypotheses
- Collaboration observations
- Structural discoveries
- Long-term plans
- Working agreements

These memory systems reduced the need for repeated reconstruction of important concepts.

---

## 3.7 Reminder Systems

Reminder systems functioned as temporal extensions of memory.

Examples included:

- Scheduled reminders
- Task notifications
- Future prompts
- Research follow-up triggers

These mechanisms helped maintain continuity across interruptions and long time intervals.

---

## 3.8 Handover Infrastructure

The research program repeatedly involved transitions between:

- AI systems
- Sessions
- Repositories
- Research phases

To support continuity, handover infrastructure was developed.

Examples included:

- AI handover files
- Repository summaries
- README documents
- Portfolio repositories

These artifacts reduced context loss during transitions.

---

## 3.9 Human-AI Working Agreements

A unique aspect of the research environment was the emergence of recurring collaboration protocols.

Examples included:

- "또 날 위해 출력해줄 거 있어?"
- "저장할 거 저장해줘."
- "연구 프로그램 관점에서 보면?"
- "지금 내가 놓치고 있는 것은?"

These interactions gradually became stable mechanisms for:

- Context restoration
- Research planning
- Knowledge preservation
- Discovery of missing connections

As a result, collaboration protocols became part of the research environment itself.

---

## 3.10 Environment Characteristics

Several characteristics distinguished this research environment from conventional Human-AI interaction settings.

### Long-Term Duration

The research program extended across many sessions and repositories.

### Multi-AI Participation

Multiple AI systems participated throughout the project lifecycle.

### Persistent Artifacts

Research context was continuously preserved through repositories and documentation.

### Future-Self Collaboration

The future version of the researcher functioned as an indirect collaborator through artifact-mediated communication.

### Distributed Memory

Research memory was distributed across humans, AI systems, repositories, documentation, and reminder systems.

These characteristics collectively formed the environment in which the observations presented in this study emerged.

# 4. Externalized Memory

## 4.1 The Memory Problem

Long-term research inherently involves memory limitations.

Human researchers gradually forget details over time, while AI systems are constrained by context windows, session boundaries, and token limitations.

As a result, neither humans nor AI systems can reliably preserve complete research context over extended periods.

This creates a fundamental challenge for long-term Human-AI research collaboration.

---

## 4.2 Externalized Memory

This study defines Externalized Memory as:

> Externalized Memory is research context stored outside the biological memory of the researcher and outside the active context window of AI systems.

Under this definition, memory does not need to reside exclusively within either a human researcher or an AI system.

Instead, memory can be preserved through external artifacts that remain accessible over time.

Externalized Memory serves as a mechanism for preserving research continuity despite interruptions, system changes, and memory limitations.

---

## 4.3 Forms of Externalized Memory

Throughout the research program, several forms of Externalized Memory emerged.

### Repository-Based Memory

- GitHub Repositories
- Research Portfolio Repositories
- Research Hub Repositories

Repositories functioned as persistent storage systems for research context.

### Documentation-Based Memory

- README files
- Handover Documents
- Research Reports
- Status Summaries

Documentation preserved information that would otherwise be lost between sessions.

### Conversation-Based Memory

- Project Memory Systems
- Saved Research Insights
- AI Conversation Histories

These systems provided partial continuity across discussions.

### Reminder-Based Memory

- Scheduled Tasks
- Notifications
- Future Reminders

Reminder systems helped restore research context at later points in time.

Together, these artifacts formed an external memory infrastructure for the research program.

---

## 4.4 Context Transfer

The primary function of Externalized Memory is Context Transfer.

Research context can move between different participants, systems, and points in time through external artifacts.

One common pattern observed during the research was:

Present Self
↓
Artifact
↓
AI System
↓
Future Self

In this process, the artifact acts as a carrier of research context.

A second pattern involved AI-to-AI transfer:

AI System A
↓
Handover Document
↓
AI System B

In this case, documentation enables continuity despite changing AI systems.

Therefore, documents function not merely as records but as mechanisms for transferring context.

---

## 4.5 Future-Self Collaboration

One notable observation was that the future version of the researcher effectively became another participant in the collaboration process.

The present researcher frequently created artifacts intended to assist future research activities.

Examples included:

- README files
- Status Reports
- Handover Documents
- Research Logs
- Repository Structures

These artifacts allowed future versions of the researcher to restore context and resume work with reduced reconstruction effort.

Under this interpretation, documentation becomes a collaboration interface between present and future selves.

---

## 4.6 Distributed Research Memory

Research memory was not concentrated within a single participant.

Instead, memory became distributed across multiple entities.

Examples included:

- Human Researcher
- ChatGPT
- Claude
- ANTIGRAVITY
- GitHub Repositories
- Documentation Systems
- Reminder Systems

Each component retained a portion of the overall research context.

Consequently, the research program operated through a distributed memory system rather than a centralized memory system.

Research continuity emerged from the interaction of these distributed memory components.

---

## 4.7 Human-AI Working Agreements as Memory Structures

Long-term collaboration produced recurring interaction patterns that supported memory preservation.

Examples included:

- "또 날 위해 출력해줄 거 있어?"
- "지금 내가 놓치고 있는 것은?"
- "연구 프로그램 관점에서 보면?"
- "저장할 거 저장해줘."

These phrases functioned as more than conversational expressions.

They became procedural triggers that activated specific collaborative behaviors.

For example:

- Identifying missing connections
- Generating future research tasks
- Preserving important observations
- Restoring lost context

Over time, these working agreements became part of the distributed memory system itself.

Thus, memory preservation depended not only on documents but also on stable collaboration protocols between humans and AI systems.

---

## 4.8 Externalized Memory Hypothesis

# 5. AI-to-AI Handover

## 5.1 Introduction

Long-term Human-AI research programs frequently involve transitions between AI systems.

These transitions may occur because of:

- Model availability
- Token limitations
- Platform changes
- Cost considerations
- Specialized capabilities

Each transition introduces the possibility of context loss.

This chapter examines how research continuity was maintained across multiple AI systems through structured handover mechanisms.

---

## 5.2 The Handover Problem

In traditional human collaboration, handovers occur when responsibilities are transferred from one person to another.

A similar challenge emerges in Human-AI collaboration.

When an AI system is replaced or supplemented by another AI system, important information may be lost.

Examples include:

- Research goals
- Previous discoveries
- Repository structures
- Project history
- Working assumptions

Without a handover mechanism, a new AI system may need to reconstruct context from the beginning.

This process is costly and often incomplete.

---

## 5.3 AI System Transitions

The research program involved multiple AI systems.

Examples included:

### ChatGPT

Frequently used for:

- Theory development
- Research planning
- Concept integration

### Claude

Frequently used for:

- Repository management
- Documentation restructuring
- Organizational tasks

### ANTIGRAVITY

Frequently used for:

- Large-scale repository analysis
- Long-form generation
- Bulk processing

Because no single AI system participated continuously in every activity, transitions became a routine part of the research workflow.

---

## 5.4 Handover Artifacts

Several forms of artifacts emerged to support AI-to-AI handover.

### README Files

Provided repository-level orientation.

### Repository Descriptions

Summarized repository objectives and relationships.

### Handover Documents

Explicitly described project status and future tasks.

### Research Summaries

Condensed previous discussions into transferable knowledge.

### Portfolio Repositories

Provided a high-level view of the overall research program.

Together, these artifacts reduced dependency on any single AI system.

---

## 5.5 Repository-Based Handover

One of the most effective handover mechanisms involved repositories.

Repositories preserved:

- Research outputs
- Documentation
- Historical decisions
- Organizational structures

As a result, a newly introduced AI system could reconstruct substantial portions of project context by reviewing repository contents.

The repository itself functioned as a handover interface.

---

## 5.6 Handover Workflow

A recurring workflow emerged during the research program.

Research Activity
↓
Documentation
↓
Repository Storage
↓
AI Transition
↓
Context Reconstruction
↓
Continued Research

This process transformed handovers from exceptional events into routine operations.

---

## 5.7 Context Compression

An important observation was that effective handovers required context compression.

The complete research history was often too large to transfer directly.

Instead, context was compressed into:

- Summaries
- README files
- Research logs
- Status reports
- Repository maps

Compression reduced transfer cost while preserving essential information.

The quality of the handover depended heavily on the quality of this compression process.

---

## 5.8 AI Independence Through Documentation

A significant benefit of handover artifacts was reduced dependence on individual AI systems.

Knowledge became attached to artifacts rather than specific models.

Consequently:

- AI systems became replaceable.
- Research continuity improved.
- Context recovery became faster.
- Long-term sustainability increased.

This observation suggests that successful Human-AI collaboration should avoid excessive dependence on any single AI model.

---

## 5.9 Handover as Context Transfer

Traditional documentation is often viewed as information storage.

The observations in this study suggest a different interpretation.

The primary purpose of handover artifacts is not storage.

The primary purpose is transfer.

A handover document succeeds when it enables another participant to reconstruct the context necessary for continued work.

Under this perspective, handovers become specialized forms of Context Transfer.

---

## 5.10 AI-to-AI Handover Hypothesis

Based on the observations presented in this chapter, the following hypothesis is proposed.

> Long-term multi-AI collaboration becomes possible when research context can be transferred through persistent artifacts that remain independent of any individual AI system.

Under this hypothesis, continuity depends less on preserving access to a specific AI model and more on preserving transferable research context.

Based on the observations presented in this study, the following hypothesis is proposed.

> Long-term Human-AI research collaboration becomes possible when research context is externalized into persistent artifacts that support context transfer across time, sessions, and AI systems.

Under this hypothesis, successful long-term collaboration depends less on maintaining continuous memory within a single participant and more on constructing reliable systems for context preservation and transfer.

The case studies presented in Chapter 8 provide empirical examples supporting this hypothesis.


# 6. Token Constraints and Context Loss

## 6.1 Introduction

Long-term Human-AI collaboration is constrained not only by human memory limitations but also by the computational limitations of AI systems.

One of the most significant constraints observed during the research program was token availability.

Token limitations directly affected:

- Conversation length
- Context retention
- Repository analysis
- Document processing
- Research continuity

This chapter examines how token constraints influenced collaboration and how researchers adapted to these limitations.

---

## 6.2 Token Constraints as Research Constraints

Token limits are often viewed as technical restrictions.

However, observations from this study suggest a broader interpretation.

In practice, token limitations functioned as research constraints.

When token resources became limited, researchers were forced to:

- End conversations
- Compress information
- Create summaries
- Transfer context
- Reconstruct lost knowledge

Consequently, token limitations influenced both the pace and structure of research activities.

---

## 6.3 Context Loss

Context loss occurred whenever information could no longer be efficiently accessed within an active interaction.

Common causes included:

### Session Boundaries

Research conversations ending before completion.

### Context Window Limits

Older information becoming inaccessible during long discussions.

### AI System Changes

Transitions between different AI systems.

### Repository Growth

Research assets becoming too large to review in a single interaction.

These factors repeatedly disrupted research continuity.

---

## 6.4 The Cost of Context Reconstruction

One of the most important observations was that rebuilding context often required substantial effort.

Context reconstruction commonly involved:

- Reviewing repositories
- Reading README files
- Examining handover documents
- Revisiting previous discussions
- Re-establishing research objectives

In some cases, reconstructing context required more effort than generating new content.

This suggests that context reconstruction should be treated as a major research activity rather than an administrative task.

---

## 6.5 Compression Strategies

To reduce reconstruction costs, multiple compression strategies emerged.

### README-Based Compression

Repository READMEs condensed large amounts of information into accessible summaries.

### Handover-Based Compression

AI handover documents captured essential project knowledge.

### Portfolio-Based Compression

Research portfolio repositories summarized relationships among projects.

### Status Reports

Periodic summaries preserved the current state of research.

These compression artifacts enabled efficient transfer of large amounts of context.

---

## 6.6 Repository Analysis and Token Consumption

Repository analysis frequently required significant token resources.

Typical workflow included:

- Reading file names
- Inspecting repository structures
- Reviewing documentation
- Analyzing relationships among repositories
- Generating summaries

As repository size increased, the token cost of analysis increased as well.

This created an incentive to improve repository organization and documentation quality.

Well-structured repositories reduced token consumption during context reconstruction.

---

## 6.7 Images, Documents, and Token Usage

The research program also involved analysis of images, repository screenshots, and large document collections.

A recurring observation was that AI systems often performed iterative cycles such as:

- Reading image lists
- Examining file names
- Matching files to content
- Rechecking repository structures
- Verifying interpretations

These repeated operations consumed substantial token resources.

As a result, efficient documentation frequently reduced overall token expenditure.

---

## 6.8 Token Exhaustion and Workflow Adaptation

Repeated encounters with token limitations led to workflow adaptations.

Examples included:

### Creating Summaries Before Context Expired

Important observations were documented before conversation limits were reached.

### Building Persistent Repositories

Knowledge was moved into repositories rather than remaining inside conversations.

### Maintaining Handover Documents

Transfer documents reduced reconstruction costs after interruptions.

### Preserving Key Insights

Important discoveries were explicitly externalized into memory artifacts.

These adaptations gradually became standard components of the research process.

---

## 6.9 Context Preservation as Optimization

An important observation was that preserving context often reduced future token consumption.

For example:

Poor Documentation
→ Large Reconstruction Cost
→ High Token Usage

Good Documentation
→ Small Reconstruction Cost
→ Lower Token Usage

Thus, documentation quality directly influenced collaboration efficiency.

Context preservation functioned as an optimization strategy rather than merely a record-keeping activity.

---

## 6.10 Token Constraints and Externalized Memory

Token limitations contributed directly to the emergence of Externalized Memory practices.

Because neither humans nor AI systems could reliably retain all research context internally, external artifacts became necessary.

Examples included:

- Repositories
- README files
- Handover documents
- Research logs
- Reminder systems

These artifacts allowed context to survive beyond active conversations.

As a result, token constraints became a driving force behind the development of distributed research memory systems.

---

## 6.11 Token Constraint Hypothesis

Based on the observations presented in this chapter, the following hypothesis is proposed.

> As research duration increases, the cost of context reconstruction becomes a dominant factor in Human-AI collaboration.

Under this hypothesis, successful long-term research depends not only on generating knowledge but also on minimizing the cost of restoring that knowledge after interruptions.

Consequently, documentation, repositories, handovers, and external memory systems become essential components of sustainable Human-AI collaboration.

# 7. Building a Long-Term Research Program

## 7.1 Introduction

Long-term research programs face challenges that are uncommon in short-term projects.

These challenges include:

- Memory limitations
- Context loss
- Research continuity
- Knowledge preservation
- AI system transitions
- Token constraints

To address these issues, a structured research program architecture was gradually developed.

This chapter describes the mechanisms that enabled the continuation of the Minor Thesis research program over an extended period of time.

---

## 7.2 Research as a Persistent System

Traditional research is often viewed as a sequence of isolated tasks.

However, long-term Human-AI collaboration requires research to function as a persistent system.

In a persistent system, knowledge survives beyond:

- Individual conversations
- Individual AI sessions
- Individual researchers' memory states
- Individual software platforms

The objective is not merely to produce results but to preserve the ability to continue producing results.

---

## 7.3 Repository-Centered Architecture

GitHub repositories became the primary organizational unit of the research program.

Each repository served multiple purposes simultaneously:

- Research paper
- Knowledge archive
- Handover platform
- Collaboration interface
- Context restoration tool

Examples included:

1. 1KMapStructureInvariance
2. 2SymmetricBooleanFunctionMinorThesis
3. 3VariableRearrangementInvarianceMinorThesis
4. 4StructureRecognitionTheory
5. 5HumanAIResearchCollaboration

Together, these repositories formed a distributed research infrastructure.

---

## 7.4 Research Portfolio Integration

As the number of repositories increased, a higher-level organizational structure became necessary.

Research Portfolio repositories emerged as integration layers.

Their functions included:

- Connecting related studies
- Explaining relationships among repositories
- Providing reading order
- Preserving research history
- Supporting future expansion

This transformed independent repositories into a coherent research program.

---

## 7.5 Handover-Based Continuity

Long-term collaboration requires continuity despite interruptions.

To support continuity, handover artifacts were developed.

Examples included:

- README files
- Research summaries
- Status reports
- Repository descriptions
- AI handover documents

These artifacts reduced the cost of context reconstruction after interruptions.

Rather than requiring complete rediscovery of previous work, future collaborators could restore context through documentation.

---

## 7.6 Multi-AI Role Differentiation

Different AI systems gradually assumed different roles within the research program.

Observed examples included:

### ChatGPT

- Conceptual discussion
- Theory development
- Research planning
- Context integration

### Claude

- Repository organization
- Documentation refinement
- Structural editing

### ANTIGRAVITY

- Large-scale repository processing
- Bulk analysis
- Extended document generation

Over time, a distributed collaboration structure emerged in which different AI systems specialized in different functions.

---

## 7.7 Context Reconstruction Workflows

Context reconstruction became a recurring research activity.

Several methods were repeatedly used:

### Repository Review

Reading repository documentation to restore project status.

### Handover Review

Reading handover documents prepared by previous collaborators.

### Research Portfolio Navigation

Following links among repositories to reconstruct conceptual relationships.

### Working Agreement Activation

Using recurring prompts and collaboration protocols to recover research context.

Examples included:

- "또 날 위해 출력해줄 거 있어?"
- "지금 내가 놓치고 있는 것은?"
- "연구 프로그램 관점에서 보면?"

These prompts frequently triggered recovery of previously established research structures.

---

## 7.8 Human-AI Collaboration Lifecycle

The observed collaboration process often followed a recurring cycle.

Observation
↓
Documentation
↓
Repository Storage
↓
AI Analysis
↓
Knowledge Integration
↓
Future Recovery
↓
New Observation

This cycle enabled continuous growth of the research program despite interruptions and system changes.

---

## 7.9 Research Program Scalability

One important observation was that the architecture became more valuable as the research program expanded.

Adding new repositories did not simply increase information volume.

Instead, it increased the number of possible relationships among studies.

As a result, preserving structure became increasingly important.

The architecture therefore emphasized:

- Documentation
- Repository organization
- Context transfer
- Knowledge integration

rather than simple information storage.

---

## 7.10 Long-Term Research Program Hypothesis

Based on the observations described in this chapter, the following hypothesis is proposed.

> Long-term Human-AI research programs can be sustained when knowledge preservation, context transfer, and collaboration protocols are treated as first-class components of the research process.

Under this view, research is not merely the production of new knowledge.

It is also the construction and maintenance of systems capable of preserving, restoring, and extending that knowledge across time.

# 8. Case Study

This chapter presents real-world observations collected during the development of the Minor Thesis research program. Unlike controlled experiments, these cases emerged naturally through long-term collaboration between a human researcher and multiple AI systems.

---

## 8.1 Repository-Based Research Program

The research initially depended on individual conversations and temporary context.

As the research program expanded, a need emerged for persistent storage and structured knowledge preservation.

GitHub repositories were adopted as research memory systems.

Each paper was managed as an independent repository, and later connected through portfolio repositories and research hubs.

This transformation enabled research continuity across sessions, devices, and AI systems.

---

## 8.2 AI-to-AI Handover

Multiple AI systems participated in the research process.

Examples included:

- ChatGPT
- Claude
- ANTIGRAVITY

Each system contributed at different stages of the research.

Whenever a transition occurred between AI systems, there was a risk of losing research context.

To mitigate this problem, handover documents were created and maintained.

These documents enabled research continuity despite changes in AI systems.

---

## 8.3 Token Exhaustion as a Research Constraint

Token limitations repeatedly influenced the research workflow.

Long conversations, image analysis, repository reviews, and large document processing consumed substantial context resources.

As a result, context reconstruction became a recurring task.

This revealed that token limitations are not merely computational constraints but also collaboration constraints.

The need to rebuild context significantly influenced the design of the research workflow.

---

## 8.4 Future-Self Communication

The researcher frequently created documents intended for future use.

Examples included:

- README files
- Research logs
- Status reports
- Handover documents
- Reminder systems

These artifacts functioned as communication mechanisms between the present researcher and the future researcher.

Rather than serving only as records, they became tools for restoring research context after interruptions.

---

## 8.5 Development of the Minor Thesis Program

The research program did not begin as a unified framework.

Initially, individual ideas and observations were explored independently.

Over time, these studies became increasingly connected.

The resulting progression was:

1. K-Map Structure Invariance
2. Symmetric Boolean Function Minor Thesis
3. Variable Rearrangement Invariance Minor Thesis
4. Structure Recognition Theory
5. Human-AI Research Collaboration

Eventually, the structure of the research program itself became an object of study.

---

## 8.6 Emergent Human-AI Working Agreements

During long-term collaboration, recurring interaction patterns emerged between the researcher and AI systems.

These patterns functioned as informal collaboration protocols.

### Research Mode Triggers

Certain phrases consistently signaled a transition into research-oriented discussion.

Examples included:

- "또 날 위해 출력해줄 거 있어?"
- "지금 내가 놓치고 있는 것은?"
- "연구 프로그램 관점에서 보면?"
- "저장할 거 저장해줘."

These phrases served not merely as questions but as procedural triggers that guided the collaborative process.

### Context Preservation Agreements

Important insights were repeatedly identified and preserved.

The researcher actively externalized key observations, while AI systems assisted in reconnecting and restoring them later.

Examples included:

- Structure discovery experiences
- Human-AI collaboration observations
- Externalized memory concepts
- Research roadmap discussions

### Task Delegation Agreements

Different AI systems gradually assumed different roles.

Examples included:

- ChatGPT for research discussion and conceptual development
- Claude for repository organization and documentation
- ANTIGRAVITY for large-scale repository processing

This resulted in an emergent division of labor among AI systems.

### Future-Self Coordination

The future version of the researcher effectively became another participant in the collaboration process.

To support this coordination, the researcher continuously produced artifacts such as:

- README files
- Handover documents
- Research logs
- Repository structures
- Reminder systems

These artifacts enabled knowledge transfer across time and functioned as mechanisms for collaboration with future versions of the researcher.

---

## 8.7 Externalized Memory in Practice

One recurring observation was that research continuity depended less on biological memory and more on externalized artifacts.

Repositories, documents, project memories, reminders, and handover files collectively formed a distributed memory system.

Within this system, context was transferred through artifacts rather than retained exclusively within either the human researcher or AI systems.

This observation became one of the central motivations for the Human-AI Research Collaboration study.

# 9. Discussion

## 9.1 Overview

The case studies presented in this research suggest that long-term Human-AI collaboration is not primarily a problem of intelligence.

Instead, it is largely a problem of memory, context preservation, and coordination.

The findings indicate that successful collaboration depends on the ability to preserve and transfer research context across time, sessions, repositories, and AI systems.

---

## 9.2 Beyond Context Windows

Most discussions surrounding Large Language Models focus on context window size.

However, the observations presented in this study suggest that context windows alone are insufficient for long-term research.

Even very large context windows eventually encounter limitations.

As research duration increases, preserving context requires mechanisms that exist outside the active conversation.

This shifts the focus from context storage to context restoration.

The critical question becomes:

> How can lost context be reconstructed efficiently?

rather than:

> How much context can be stored at once?

---

## 9.3 Externalized Memory as Infrastructure

The results suggest that Externalized Memory should be viewed as infrastructure rather than documentation.

Repositories, README files, handover documents, research logs, and reminder systems did not merely record research progress.

They actively enabled future research progress.

Without these artifacts, substantial portions of research context would have been lost.

Therefore, Externalized Memory functioned as an operational component of the research process.

---

## 9.4 Human-AI Working Agreements

A notable observation was the emergence of recurring collaboration protocols.

Examples included prompts such as:

- "또 날 위해 출력해줄 거 있어?"
- "지금 내가 놓치고 있는 것은?"
- "연구 프로그램 관점에서 보면?"
- "저장할 거 저장해줘."

These interactions evolved into procedural mechanisms for:

- Context recovery
- Knowledge preservation
- Research planning
- Gap identification

This suggests that effective collaboration depends not only on memory artifacts but also on stable interaction protocols.

Future Human-AI collaboration systems may benefit from explicitly supporting such protocols.

---

## 9.5 Future-Self as a Research Participant

Traditional collaboration research assumes collaboration among contemporaneous participants.

The present study suggests an additional form of collaboration.

The future version of the researcher frequently became a recipient of information created in the present.

README files, research logs, handover documents, and reminders were often written with the explicit purpose of assisting future research activities.

Consequently, collaboration occurred across time as well as across individuals and systems.

This observation expands the notion of collaboration beyond simultaneous interaction.

---

## 9.6 Distributed Research Memory

The research program demonstrated characteristics of a distributed memory system.

Memory was distributed across:

- Human researchers
- AI systems
- GitHub repositories
- Documentation artifacts
- Reminder systems

No individual component contained the complete research context.

Instead, continuity emerged from the interactions among components.

This resembles distributed information systems in which reliability depends on network structure rather than a single storage location.

---

## 9.7 Implications for Human-AI Collaboration

The findings suggest several implications.

### Research Systems

Future research environments should support:

- Persistent documentation
- Structured handovers
- Context restoration workflows
- Multi-AI collaboration

### AI Design

Future AI systems may benefit from features that support:

- Long-term context preservation
- Collaboration protocol recognition
- Artifact-based memory integration
- Cross-session continuity

### Knowledge Management

Knowledge management should be viewed as a core component of Human-AI collaboration rather than a secondary administrative task.

---

## 9.8 Limitations

Several limitations should be acknowledged.

First, the observations are based on a single long-term research program.

Second, the collaboration environment involved specific AI systems and tools.

Third, many observations emerged naturally rather than through controlled experimentation.

As a result, the findings should currently be interpreted as exploratory rather than definitive.

Future studies involving additional researchers, AI systems, and research domains will be necessary.

---

## 9.9 Future Research Directions

Several future research directions emerge from this work.

### Formal Models of Externalized Memory

Developing theoretical models that describe context transfer across humans, AI systems, and artifacts.

### Human-AI Collaboration Protocols

Investigating recurring interaction patterns as formal collaboration mechanisms.

### AI-to-AI Handover Systems

Studying structured methods for transferring research context between AI systems.

### Distributed Research Memory

Exploring memory architectures that integrate repositories, documentation, reminders, and AI systems into a unified framework.

### Long-Term Research Programs

Examining how Human-AI collaboration influences research programs that extend across months or years.

---

## 9.10 Main Claim

The central claim of this study is not that AI systems possess perfect memory.

Nor is it that human researchers possess sufficient memory to sustain long-term projects unaided.

Instead, the evidence suggests that long-term Human-AI collaboration becomes possible when memory is externalized, preserved, and transferred through persistent artifacts and stable collaboration protocols.

Under this view, research continuity emerges not from any single participant but from the structure connecting all participants.

# 10. Conclusion

## 10.1 Summary

This study investigated long-term Human-AI research collaboration through a multi-repository research program involving multiple AI systems, repository infrastructure, documentation artifacts, and persistent knowledge management practices.

The findings suggest that the primary challenge of long-term collaboration is not intelligence alone.

Instead, long-term collaboration depends heavily on:

- Memory preservation
- Context transfer
- Knowledge continuity
- Collaboration protocols
- Research infrastructure

Throughout the research program, these factors repeatedly influenced the ability to sustain progress across time.

---

## 10.2 Main Findings

Several major observations emerged.

### Finding 1: Memory Exists Beyond Individuals

Research context was frequently preserved outside both human memory and AI memory.

Repositories, documents, logs, reminders, and handover files collectively functioned as memory systems.

This led to the concept of Externalized Memory.

---

### Finding 2: Context Transfer Is More Important Than Context Storage

The central challenge was rarely storing information.

Instead, the challenge was restoring and transferring context when needed.

README files, handover documents, research summaries, and repository structures were most valuable when they enabled efficient context reconstruction.

---

### Finding 3: Research Memory Becomes Distributed

Research continuity emerged from interactions among multiple components.

These included:

- Human researchers
- AI systems
- Repositories
- Documentation artifacts
- Reminder systems

No single component contained the complete research context.

Instead, memory became distributed throughout the research environment.

This observation motivated the concept of Distributed Research Memory.

---

### Finding 4: Collaboration Protocols Matter

Long-term collaboration produced recurring interaction patterns.

Examples included prompts such as:

- "또 날 위해 출력해줄 거 있어?"
- "지금 내가 놓치고 있는 것은?"
- "연구 프로그램 관점에서 보면?"
- "저장할 거 저장해줘."

These interactions evolved into stable collaboration mechanisms supporting:

- Context recovery
- Knowledge preservation
- Research planning
- Discovery of missing connections

This suggests that successful Human-AI collaboration depends not only on information artifacts but also on procedural agreements.

---

### Finding 5: Future-Self Collaboration Is Real

A recurring observation was that future versions of the researcher frequently became participants in the research process.

Documentation was often created specifically to assist future research activities.

README files, handover documents, research logs, and reminders functioned as communication channels across time.

As a result, collaboration occurred not only among humans and AI systems but also between present and future versions of the same researcher.

---

## 10.3 Proposed Framework

Based on the observations presented throughout this study, the following framework is proposed.

Long-term Human-AI collaboration depends on four interconnected components:

### Externalized Memory

Preservation of research context outside active memory systems.

### Context Transfer

Movement of research context across time, sessions, repositories, and participants.

### Distributed Research Memory

Distribution of knowledge across humans, AI systems, repositories, and artifacts.

### Collaboration Protocols

Stable interaction patterns that support continuity and context recovery.

Together, these components form the foundation of sustainable long-term Human-AI research programs.

---

## 10.4 Human-AI Research Continuity Theory

The findings of this study support the following claim:

> Long-term Human-AI research collaboration is fundamentally a problem of research continuity rather than a problem of intelligence alone.

Under this interpretation, the success of collaboration depends on the ability to preserve, restore, and transfer context across time.

Consequently, research infrastructure becomes as important as reasoning capability.

Repositories, documentation systems, handovers, and reminders should therefore be considered integral components of Human-AI collaboration.

---

## 10.5 Future Directions

Several avenues for future research remain open.

These include:

- Formal models of Externalized Memory
- AI-to-AI handover protocols
- Distributed Research Memory architectures
- Human-AI collaboration standards
- Repository-centered research environments
- Longitudinal studies of multi-year Human-AI research programs

Future work may determine whether the patterns observed in this study generalize beyond the present research program.

---

## 10.6 Final Statement

This study began with a practical question:

How can humans and AI systems continue a research program when neither participant can reliably preserve all necessary context?

The observations presented throughout this work suggest that continuity emerges when context is externalized into persistent artifacts and transferred through stable collaboration structures.

Under this view, successful Human-AI collaboration is not achieved by eliminating memory limitations.

Instead, it is achieved by constructing systems that make those limitations manageable.

Long-term research therefore becomes possible not because memory is perfect, but because context can be preserved, restored, and transferred across time.

