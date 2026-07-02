# Hi, I'm Thom 👋

**I build AI agent tooling** — MCP servers, orchestration frameworks, and the plumbing that makes AI-assisted work reliable.

I care about the parts most AI projects skip: **human-approval gates, tests that catch real bugs, and honest status.** Several of the tools below run my own daily workflow. My background is in design, digital fabrication, and innovation education.

---

## 🧩 MCP servers & agent tooling

- **[kanbanger](https://github.com/earlyprototype/kanbanger)** — An MCP kanban server where an AI can *propose* work is done, but only a human can approve it — enforced server-side, not by a prompt. 160 tests, ADR-documented performance work.
- **[thought_bubble](https://github.com/earlyprototype/thought_bubble)** ⭐ — An MCP server that turns documents into themed, self-contained HTML with server-rendered Mermaid diagrams and D3 charts — offline, one pipeline. 172 tests.
- **[notebooklm-py-MCP](https://github.com/earlyprototype/notebooklm-py-MCP)** — Exposes Google NotebookLM as 72 agent tools, audited against the live SDK with introspection tests that caught 11 real bugs. (Plus a 14-tool edition for daily use.)
- **[hunch_kit](https://github.com/earlyprototype/hunch_kit)** — A local-first experiment framework — isolate one variable, track lineage, score by human judgement — with a full MCP server. 61 tests.

## 🔷 Orchestrating AI agents

- **[early-prototype](https://github.com/earlyprototype/early-prototype)** — My Claude Code plugin marketplace: turns solo AI-agent sessions into auditable PM → Worker cycles, with race-safe session identity and human approval before any agent's work counts as done.
- **[lia-workflow-specs](https://github.com/earlyprototype/lia-workflow-specs)** — *Slow-code*: an 18-workflow prompt framework (with its own MCP server) for deliberate AI development — built from real use, including an 85,000-word paper analysis.

## 🔬 Applied AI tools

- **[meTube](https://github.com/earlyprototype/meTube)** — A TypeScript CLI turning YouTube history into a searchable knowledge base (dual transcript pipeline + Gemini). It then audited itself, caught its own silent data-loss bugs, and got rewritten with compiler-enforced invariants. 740+ tests, green CI.
- **[plasticFlower](https://github.com/earlyprototype/plasticFlowers)** — A real-time speech → knowledge-graph engine (Gemini, Neo4j, Redis Streams) with a hand-built graph-physics layout.
- **[knowledge-graph-kit](https://github.com/earlyprototype/knowledge-graph-kit)** — A config-driven knowledge-graph builder with citation provenance, generalized from a research tool I actually use.
- **[FabLatticeGPT](https://github.com/earlyprototype/FabLatticeGPT)** — A phase-gated AI advisor that stops FabLab members solutioning before their idea is scoped — built for an Enterprise FabLab role via the OpenAI SME Accelerator.

## 🧪 Research

- **[Activation Tensor Resonance](https://github.com/earlyprototype/lucier-gpt2-activ-tensor-reson-experiments)** — Looped GPT-2's own activations back through itself 500× and found it always collapses to one of five words — then built a 125-prompt sweep to try to *falsify* that before trusting it. (Dashboard generated with my own thought_bubble tool.)

---

📫 **Get in touch** — [LinkedIn](https://www.linkedin.com/in/thom-conaty) · [thomconaty@gmail.com](mailto:thomconaty@gmail.com)
