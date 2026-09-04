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

Simple does not mean simplistic. I prefer designs with clear responsibilities, understandable behavior, and as few moving parts as the problem allows.

A few questions I tend to ask when designing or reviewing a system:

## How I think about software

I strongly value simplicity.

Simple does not mean simplistic. I prefer designs with clear responsibilities, understandable behavior, and as few moving parts as the problem allows.

A few questions I tend to ask when designing or reviewing a system:

* **Where does the state live, and who owns it?**
  Shared state deserves extra scrutiny.

* **What happens when this fails?**
  Failures should be visible and diagnosable.

* **Which assumptions are we making?**
  And are they actually true?

* **Can this be simpler?**
  Good design should also be pleasant to understand and work with.

* **Does this abstraction really earn its place?**
  I prefer useful boundaries over abstraction for its own sake.

* **How will we know the important behavior still works?**
  Important behavior deserves tests.

* **What trade-offs are we accepting?**
  Trying to optimize for everything usually makes the system worse.

* **Will this still be understandable six months from now?**
  By another engineer — or by me.


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
