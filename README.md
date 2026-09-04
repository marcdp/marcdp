# Marc Delòs

**Software Engineer focused on software architecture, distributed systems, and AI engineering**

I’m a hands-on software engineer with many years of experience building and evolving software systems.

I’m especially interested in the decisions behind the code: how a system is structured, where responsibilities belong, what can fail, which trade-offs are worth making, and how to keep software understandable as it grows.

I still enjoy working directly with code. For me, architecture is most useful when it stays connected to implementation, real constraints, and the way systems behave in production.

## What I work on

* **Software architecture** — system boundaries, decomposition, coupling, quality attributes, trade-offs, and evolutionary design
* **C# / .NET** — backend systems, reusable libraries, APIs, persistence, asynchronous programming, and infrastructure
* **Distributed and event-driven systems** — messaging, concurrency, state ownership, consistency, recovery, and observability
* **Reliability and maintainability** — failure behavior, testability, operational concerns, CI/CD, and safe evolution
* **AI engineering** — LLM-enabled systems, agents, tool use, structured outputs, retrieval, evaluation, reliability, and AI-assisted development
* **Python** — automation, CLI tooling, AI/ML work, and developer productivity

## How I think about software

### Simplicity first

I strongly value simplicity.

Simple does not mean simplistic. It means removing unnecessary moving parts, keeping responsibilities clear, and choosing the least complex solution that satisfies the real requirements.

I prefer a straightforward design that I can explain and reason about over a sophisticated one that is difficult to understand.

A few questions I tend to ask when designing or reviewing a system:

* Where does the state live, and who owns it?
* What happens when this fails?
* Which assumptions are we making?
* Can this be simpler?
* Does this abstraction actually earn its place?
* How will we verify the important behavior?
* What trade-offs are we accepting?
* Will someone else understand this six months from now?

Other principles I value:

* **Explicit trade-offs** — there is rarely a universally best architecture. Constraints, benefits, and costs should be visible.
* **Clear ownership** — responsibilities, state, and lifecycle should have clear owners.
* **Failure is part of the design** — the happy path is only part of how a system behaves.
* **Abstractions should earn their complexity** — indirection is useful when it protects a meaningful boundary, not simply because a pattern exists.
* **Tests should protect behavior** — important invariants, edge cases, and failure modes matter more than a coverage number.
* **Operations belong in the design** — logging, observability, diagnostics, deployment, and recovery affect architecture.
* **AI needs engineering discipline too** — AI-enabled systems still need evaluation, constraints, security, observability, and explicit failure handling.

## Selected work

### [DProjects.Libs](https://github.com/marcdp/libs)

Reusable C#/.NET libraries covering configuration, caching, persistence, filesystem access, cryptography, logging, and shared infrastructure.

The project explores API design, modularity, dependency boundaries, testing, and one question I consider particularly important: **when is an abstraction genuinely useful?**

### [xvault](https://github.com/marcdp/xvault)

A local-first Python CLI for keeping selectively encrypted secrets inside normal Git-friendly configuration and documentation files.

It combines developer experience with security-conscious design, authenticated encryption, multiple file formats, explicit limitations, and safe failure behavior.

### [dprojectstools](https://github.com/marcdp/dprojectstools)

A Python package of developer-focused CLI utilities and reusable tooling for automation and terminal workflows.

The goal is pragmatic: useful tools, predictable behavior, and as little unnecessary complexity as possible.

### [Equity Forecasting with Deep Learning](https://github.com/marcdp/equity-forecasting-ai)

Applied AI/ML research developed for my Master’s thesis, comparing LSTM, N-BEATS, and TSFEDL models for hourly financial time-series forecasting.

The work focuses on chronological evaluation, simple baselines, leakage prevention, and the relationship between regression accuracy, directional prediction, and simulated trading performance.

## Current direction

I’m continuing to deepen three areas that naturally fit together:

**Software Engineering → Software Architecture → AI Engineering**

My goal is to take on broader technical responsibility while remaining close to implementation: designing systems, making difficult technical decisions, improving technical foundations, and helping build software that remains understandable and reliable as it evolves.

I’m most interested in environments where **architecture, implementation, and technical leadership remain closely connected**.

## Technologies

**Primary:** C#, .NET, Python

**Focus areas:** Software Architecture · Distributed Systems · Event-Driven Systems · Backend Engineering · APIs · Databases · Testing · CI/CD · Developer Tooling · AI/LLM Engineering

---

I use my public repositories not only to show what I build, but also to document some of the decisions, trade-offs, and lessons behind the systems.
