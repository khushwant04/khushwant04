# Khushwant Sanwalot

**AI Engineer · Systems Architect**

I build production infrastructure for agentic AI: systems that reason, call tools, coordinate, and execute reliably.

[LinkedIn](https://www.linkedin.com/in/khushwant-sanwalot/) · [X](https://x.com/ksanwalot04) · [Email](mailto:khushwantsanwalot2004@outlook.com)

---

## Engineering Philosophy

> An agent is not a chatbot with tools attached.
> It's a distributed system with a model inside the control loop.

So I treat agents the way I'd treat any production system:

- **State is explicit.** Context and memory are managed, versioned, and inspectable.
- **Failure is expected.** Every tool call can time out, return garbage, or partially succeed. Retries, idempotency, and rollback are designed in from the start.
- **Permissions are bounded.** Agents get the minimum access the task needs, enforced by the system rather than by the prompt.
- **Behavior is observable.** Every decision, tool call, and token is traceable.
- **Completion is verified.** "The model said it's done" is not a success condition. Evals and checks are.

---

## System Architecture

The stack I design and build across:

```text
  Production Systems        reliability · scale · cost
          ▲
  Distributed Execution     queues · events · async workers
          ▲
  Agent Orchestration       routing · delegation · coordination
          ▲
  Tool Use                  sandboxed execution · side effects
          ▲
  Planning & Reasoning      control flow · decision policies
          ▲
  Context & Memory          retrieval · state · long-term memory
          ▲
  LLMs                      inference · structured outputs
```

---

## What I Work On

| Area | What that means in practice |
| :--- | :--- |
| **Agent Infrastructure** | Multi-agent orchestration, tool execution runtimes, agent-to-agent messaging, state management, durable workflows |
| **LLM Systems** | Context engineering, structured outputs, prompt pipelines, model routing, inference serving |
| **Knowledge Systems** | RAG pipelines, semantic retrieval, vector search, long-term memory, document intelligence |
| **Distributed Infrastructure** | Event-driven services, async processing, queues, caching, Kubernetes, observability |
| **Agent Security** | Permission models, sandboxing, guardrails, and audit trails for autonomous actions |

---

## Problems I Care About

1. Keeping context correct and compact over long-running tasks
2. Making agent decisions deterministic enough to debug
3. Recovering cleanly from partial failures mid-workflow
4. Enforcing hard limits on what an agent can touch
5. Coordinating multiple agents without race conditions or duplicated work
6. Evaluating whether a task was actually completed
7. Running all of it at scale without costs or latency blowing up

---

## Stack

| Layer | Tools |
| :--- | :--- |
| **AI / ML** | PyTorch · Transformers · LLMs · RAG · Vector Search · LLM Inference |
| **Backend** | Python · TypeScript · FastAPI · PostgreSQL · Redis · Kafka |
| **Infrastructure** | Docker · Kubernetes · AWS · GCP · Event-Driven Architecture |
| **Frontend** | Next.js · React · TypeScript |

---

## Education

**B.E. Computer Science & Engineering (AI/ML)**
Visvesvaraya Technological University · 2023 – 2027

---

*Engineering reliable machine intelligence, one system at a time.*
