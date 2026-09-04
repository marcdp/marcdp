# Marc Delòs

**Software Engineer focused on software architecture, distributed systems, and AI engineering**

I’m a hands-on software engineer with many years of experience building and evolving software systems.

Over time, I’ve become increasingly interested in the decisions behind the code: how systems are structured, where responsibilities belong, what can fail, which trade-offs are worth making, and how to keep software understandable as it grows.

I still enjoy working directly with code. For me, architecture is most valuable when it stays connected to implementation, real constraints, and the way systems behave in production.

## What I work on

My main areas of interest are:

* **Software architecture** — system boundaries, decomposition, coupling, quality attributes, trade-offs, and evolutionary design
* **C# / .NET** — backend systems, reusable libraries, APIs, persistence, asynchronous programming, and infrastructure
* **Distributed and event-driven systems** — messaging, concurrency, state ownership, consistency, retries, recovery, and observability
* **Reliability and maintainability** — explicit failure behavior, testability, operational concerns, CI/CD, and safe evolution
* **AI engineering** — LLM-enabled systems, agents, tool use, structured outputs, retrieval, evaluation, reliability, and AI-assisted software development
* **Python** — automation, CLI tools, AI/ML work, and developer productivity

## How I think about software

I tend to ask fairly simple questions when designing or reviewing a system:

* Where does the state live?
* Who owns it?
* What happens when this fails?
* Which assumptions are we making?
* What really needs to be abstracted?
* Can this be simpler?
* How will we test the important behavior?
* What trade-offs are we accepting?
* Will someone else understand this six months from now?

I value architecture, but I don’t believe good architecture means having more layers, interfaces, services, or patterns.

Often, the better design is the one with fewer moving parts.

## Selected work

### [DProjects.Libs](https://github.com/marcdp/libs)

A set of reusable C#/.NET libraries covering areas such as configuration, caching, persistence, filesystem access, cryptography, logging, factories, and shared infrastructure.

Beyond the libraries themselves, the project is an ongoing exercise in API design, modularity, testing, dependency boundaries, and deciding when an abstraction is genuinely useful.

### [xvault](https://github.com/marcdp/xvault)

A local-first Python CLI for keeping selectively encrypted secrets inside normal Git-friendly configuration and documentation files.

The project combines developer experience with security-oriented design: authenticated encryption, password-based key derivation, multiple file formats, secret lifecycle management, explicit limitations, and safe failure behavior.

### [dprojectstools](https://github.com/marcdp/dprojectstools)

A Python package containing developer-focused CLI utilities and reusable tooling for automation, terminal workflows, backup-related tasks, and day-to-day development.

The goal is pragmatic tooling: useful components, predictable behavior, and as little unnecessary complexity as possible.

### [AI / Algorithmic Trading Research](https://github.com/marcdp/master-ia-tfm)

Research developed as part of my Master’s work in Applied Artificial Intelligence, focused on deep-learning approaches to financial time-series prediction and algorithmic trading.

It complements my software engineering work with practical experience in machine learning experimentation, evaluation, and quantitative analysis.

## Current direction

I’m continuing to deepen three areas that naturally fit together:

**Software Engineering → Software Architecture → AI Engineering**

My goal is to take on broader technical responsibility while staying close to implementation: designing systems, making difficult technical decisions, improving engineering foundations, and helping build software that remains understandable and reliable as it evolves.

I’m particularly interested in **Staff / Principal-level engineering and hands-on software architecture responsibilities**, where technical leadership comes from engineering depth, sound judgment, and influence rather than distance from the code.

## Principles I value

### Simplicity

I strongly value simplicity.

Simple does not mean simplistic. It means removing unnecessary moving parts, keeping responsibilities clear, and choosing the least complex solution that satisfies the real requirements.

I prefer a straightforward design I can explain clearly over a sophisticated one that is difficult to reason about.

### Explicit trade-offs

There is rarely a universally best architecture.

I prefer making the constraints, assumptions, benefits, and costs of a decision visible rather than hiding them behind patterns or conventions.

### Clear ownership

Systems are easier to reason about when it is clear who owns state, responsibilities, and lifecycle.

Ambiguous ownership is often where complexity and bugs begin.

### Failure matters

The happy path is only part of the design.

I care about what happens when dependencies fail, messages are duplicated, state becomes uncertain, a process restarts, or an operation only partially succeeds.

### Abstractions should earn their place

I like abstractions when they create a useful boundary or protect an important concept.

I try to avoid them when they only add indirection.

### Tests should protect behavior

I care more about testing important invariants, edge cases, and failure modes than reaching a particular coverage percentage.

### Operations are part of the design

Logging, observability, deployment, recovery, and diagnostics are not things to think about only after implementation.

They influence architecture.

### AI needs engineering discipline too

LLM and agent-based systems still need evaluation, constraints, observability, security, and explicit failure handling.

AI should not be treated as an exception to normal engineering discipline.

## Technologies

**Primary:** C#, .NET, Python

**Areas:** Software Architecture · Distributed Systems · Event-Driven Systems · Backend Engineering · APIs · Databases · Testing · CI/CD · Developer Tooling · AI/LLM Engineering

---

I use my public repositories not only to show what I build, but also to document some of the decisions, trade-offs, and lessons behind the systems.
