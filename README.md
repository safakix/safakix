# Muhammet Şafak

**Software Engineer · Systems Architecture · Engineering Research · AI Systems Engineering**

> I design, build and study production software systems.

I have been building software professionally since **2008**, with most of my work centered around backend systems, infrastructure, distributed systems, developer tooling, and production architecture.

My current work increasingly focuses on **AI systems engineering**: turning LLMs and agents into systems that can be operated, observed, constrained, and trusted in production.

I care less about specific languages and more about the properties of the system being built:

**explicit contracts · interoperability · measurable behavior · operational transparency · vendor independence**

---

## What I work on

### Software Engineering

Production-oriented software, developer tools, APIs, libraries, and infrastructure.

I primarily work with:

`PHP` · `Go` · `TypeScript` · `Python` · `PostgreSQL` · `Redis` · `RabbitMQ` · `Docker`

The language is an implementation detail. The problem determines the tool.

---

### Systems Architecture

I am particularly interested in systems where correctness starts becoming harder than implementation:

- distributed and event-driven systems
- production data access
- queue interoperability
- failure handling and recovery
- observability
- architecture boundaries
- self-hosted infrastructure
- AI agent control systems

I prefer designs whose constraints are explicit and whose trade-offs can be explained.

---

### Engineering Research

I build experiments and benchmarks around questions that are easy to make claims about but harder to measure properly.

The principle is simple:

> The point is not the number. The point is that the number can be re-derived.

Research code, methodology, raw runs, and limitations should be inspectable whenever possible.

---

## Selected projects

### Developer infrastructure

**[BabelQueue](https://babelqueue.com)**  
Polyglot queue interoperability through a language-neutral message contract.

**[CommitBrief](https://commitbrief.com)**  
Local, private and provider-agnostic LLM-assisted review for Git diffs.

**[QueryProxy](https://queryproxy.com)**  
Production database access without distributing production credentials.

These projects are developed under **[Tignex](https://tignex.com)**, my open-source developer infrastructure initiative.

---

### AI systems

**[Ragmux](https://ragmux.com)**  
A self-hosted AI gateway combining provider routing, RAG, cost controls and MCP.

**[Contextator](https://contextator.com)**  
A multi-tenant MCP documentation server for turning internal knowledge into project-scoped context.

My AI infrastructure work lives primarily under **Tunedness** and focuses on systems that remain operable when deployed inside someone else's infrastructure.

---

## Engineering principles

A few rules shape most of my work:

1. **Prefer reversible decisions.**  
   Architecture should preserve the ability to change tomorrow.

2. **Write down why.**  
   Significant decisions deserve an ADR, not just an implementation.

3. **Expose the cost.**  
   Performance, complexity, infrastructure and operational costs are part of the design.

4. **Choose tools for the problem.**  
   I am not attached to a programming language or framework.

5. **Say “I don't know” when necessary.**  
   Unknowns should be identified, not hidden behind confidence.

And for AI systems:

> The machine operates at the language layer, not the decision layer.

AI can propose, analyze and automate. Critical decisions should remain explicit and reviewable.

---

## Open source

My open-source work spans multiple ecosystems including:

`Go` · `PHP` · `TypeScript` · `Python` · `Java` · `.NET` · `Swift` · `Rust`

Earlier work includes the **InitPHP / InitORM** ecosystem. More recent work focuses on cross-language infrastructure, developer tooling, AI infrastructure, and system architecture.

Most projects live in their own GitHub organizations rather than this account.

---

## Writing & research

I publish engineering notes, architecture references, experiments and long-form writing at:

**[muhammetsafak.com](https://muhammetsafak.com)**

Topics usually include:

- backend and distributed systems
- system architecture
- databases and messaging
- production engineering
- AI systems
- benchmarks and engineering experiments

I also publish the **The Unreliable Systems Trilogy**, a free series on production database access, reliable event-driven systems, and reliable AI agents.

---

## Current direction

My current technical direction is **AI Systems Engineering / Architecture**.

The interesting problem for me is not simply connecting an application to an LLM API.

It is building AI systems with:

- bounded authority
- explicit contracts
- observable behavior
- predictable cost
- failure containment
- human approval boundaries
- provider independence
- self-hosted deployment options

In other words: treating AI as another unreliable component that must operate inside a reliable system.

---

## Elsewhere

[Website](https://muhammetsafak.com) ·
[LinkedIn](https://www.linkedin.com/in/safakix) ·
[X](https://x.com/safakix) ·
[YouTube](https://www.youtube.com/@muhammetsafak)

---

<sub>
Software Engineer since 2008 · Istanbul, Türkiye
</sub>
