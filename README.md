# Khushwant Sanwalot

**Founder, [Hexel Studio](https://hexelstudio.com)** · AI systems research · Bengaluru, India

I work on inference and agentic execution — how language models are served efficiently, and how they can be given autonomy without giving up control over what they do. My interest sits below the application layer: attention and kernel design, scheduling, isolation, and the failure behaviour of systems with a model in the control loop.

---

## Research

**Inference systems.** Attention variants and kernel-level optimisation — latent attention, mixture-of-experts routing, test-time scaling, and Triton kernels. The question I keep returning to is where the real cost of serving a model lives, and which of it is architectural rather than incidental.

**Agentic execution.** Agents are stateful, long-lived, and iterative, while inference systems are built for stateless single requests. That mismatch is where I think the interesting work is: session-aware scheduling, KV memory reuse across steps, and batching across heterogeneous agent workloads.

**Reliability and control.** Where determinism should end and the model should begin. I prefer architectures that keep arithmetic, validation, and permission decisions in ordinary code, so that a wrong model output is a bounded event rather than a silent one.

**Multi-tenant AI infrastructure.** Isolation enforced at the database rather than in application logic, declarative reconciliation onto GPU hardware, and serving paths that survive the failure of the systems coordinating them.

---

## Hexel Studio

I founded **Hexel Studio** to build infrastructure for agentic systems that organisations can actually deploy — where an agent operates across real workflows under real constraints, and where security and auditability are properties of the architecture rather than additions to it.

Most of my research questions come out of that work, and get tested there.

[hexelstudio.com](https://hexelstudio.com)

---

## Interests

`Inference Systems` · `LLM Serving` · `Agentic AI` · `Multi-Agent Systems` · `GPU Kernels` · `AI Memory` · `RAG` · `Distributed Systems` · `AI Security`

## Working with

`PyTorch` · `Triton` · `vLLM` · `Python` · `Go` · `TypeScript` · `PostgreSQL` · `Kubernetes` · `Azure` · `Prometheus`

---

## Education

**B.E. Computer Science Engineering (AI/ML)** — Visvesvaraya Technological University, 2023–2027

---

## Connect

[Hexel Studio](https://hexelstudio.com) · [LinkedIn](https://www.linkedin.com/in/khushwant-sanwalot/) · [X](https://x.com/ksanwalot04) · [@hexelstudio](https://github.com/hexelstudio) · [khushwantsanwalot2004@outlook.com](mailto:khushwantsanwalot2004@outlook.com)
