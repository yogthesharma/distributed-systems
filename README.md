# Distributed Systems

Standalone learning repo. Work here on its own — no other repos required.

**Phase (for your own roadmap):** Capstone

## Context

Multiple machines mean partial failure, clocks that lie, and consensus problems. Leader election, eventual consistency, idempotency, and failure handling are the core ideas. Study them here as a standalone discipline.

This repository is the single place for everything related to **Distributed Systems**: notes, exercises, and small projects. Clone it, open it, and treat it as a complete unit of study.

## Scope

- Failure modes in distributed settings
- Consensus and leader election (intuition + famous algorithms at a high level)
- Eventual consistency and conflict handling
- Idempotency and exactly-once vs at-least-once realities
- Retries, timeouts, backoff, circuit breakers

## Outcomes

When you are done with this repo, you should be able to:

- Explain why \"exactly once\" is hard and what to do instead
- Design retries and idempotency keys for a write API
- Describe consensus / leader election at a whiteboard level

## How to work in this repo

1. Read / write concept notes under `notes/`.
2. Solve practice problems under `exercises/`.
3. Ship at least one small project under `projects/` that forces the ideas to stick.
4. Tick the checklist below as you go.

You do not need any other curriculum repo open while you work here.

## Layout

```
distributed-systems/
├── README.md       # Context and checklist (this file)
├── notes/          # Concept write-ups
├── exercises/      # Practice problems and solutions
└── projects/       # Mini builds that apply the topic
```

## Progress

- [ ] Core concepts noted
- [ ] Exercises completed
- [ ] Mini-project shipped
- [ ] Can explain the main ideas without looking anything up

## Resources

Add books, docs, courses, and articles here as you find them. Keep this list local to this topic.

---

_This repo is independent. Progress elsewhere does not block work here._
