# Marc Delòs

**Software Engineer focused on software architecture, distributed systems, and AI engineering**

I’m a hands-on software engineer with many years of experience building and evolving software systems.

I genuinely enjoy building software, understanding how systems work, and finding simpler and better ways to design them.

Over time, that interest has increasingly drawn me toward software architecture: where responsibilities belong, who owns state, what can fail, which trade-offs are worth making, and how to keep a system understandable as it grows.

I still enjoy working directly with code. For me, architecture is not a layer above implementation; it is most useful when it stays connected to code, real constraints, and the way software behaves in production.

## What I work on

* **Software architecture**: system boundaries, decomposition, coupling, trade-offs, and evolutionary design
* **C# / .NET**: backend systems, reusable libraries, APIs, persistence, asynchronous programming, and infrastructure
* **Distributed and event-driven systems**: messaging, concurrency, state ownership, consistency, recovery, and observability
* **Reliability and maintainability**: failure behavior, testing, operational concerns, CI/CD, and safe evolution
* **AI engineering**: LLM-enabled systems, agents, tool use, retrieval, evaluation, reliability, and AI-assisted development

## How I think about software

I strongly value simplicity.

**Simple does not mean simplistic.** I prefer designs with clear responsibilities, understandable behavior, and as few moving parts as the problem allows.

A few questions I tend to ask when designing or reviewing a system:

* **Where does the state live, and who owns it?**
  Shared state deserves extra scrutiny.

* **What happens when this fails?**
  Failures should be visible and diagnosable.

* **Which assumptions are we making?**
  And are they actually true?

* **Can this be simpler?**
  A simple design can still be elegant and pleasant to work with.

* **Does this abstraction really earn its place?**
  I prefer useful boundaries over abstraction for its own sake.

* **How will we know the important behavior still works?**
  Important behavior deserves tests.

I also try to remember that we cannot optimize for everything. Every design has trade-offs, and software should still make sense to the next person who has to understand it, including me six months later.

## Selected work

### [DProjects.Libs](https://github.com/marcdp/libs)

Reusable C#/.NET libraries covering configuration, caching, persistence, filesystem access, cryptography, logging, and shared infrastructure.

Much of the work is about API design, dependency boundaries, testing, and deciding when an abstraction is genuinely useful.

### [xvault](https://github.com/marcdp/xvault)

A local-first Python CLI for keeping selectively encrypted secrets inside normal Git-friendly configuration and documentation files.

It combines developer experience with security-conscious design, explicit limitations, and safe failure behavior.

### [Equity Forecasting with Deep Learning](https://github.com/marcdp/equity-forecasting-ai)

Applied AI/ML research developed for my Master’s thesis, comparing LSTM, N-BEATS, and TSFEDL models for hourly financial time-series forecasting.

The work focuses on chronological evaluation, simple baselines, leakage prevention, and the relationship between regression accuracy, directional prediction, and simulated trading performance.

### [dprojectstools](https://github.com/marcdp/dprojectstools)

A collection of Python CLI utilities and reusable developer tooling for automation and terminal workflows.

The goal is pragmatic: useful tools, predictable behavior, and as little unnecessary complexity as possible.

## Current direction

I’m continuing to deepen three areas that naturally fit together:

**Software Engineering + Software Architecture + AI Engineering**

I want to take on broader technical responsibility while staying close to implementation: designing systems, making important technical decisions, strengthening engineering foundations, and helping software remain understandable and reliable as it evolves.

I’m particularly interested in work where **architecture, implementation, and technical leadership stay closely connected**.

## Technologies

**Primary:** C#, .NET, Python

**Focus:** Software Architecture · Distributed Systems · Event-Driven Systems · Backend Engineering · Testing · CI/CD · Developer Tooling · AI/LLM Engineering
