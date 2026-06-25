<div align="center">

# ARA-Labs

### Building the AI-native infrastructure for AI scientists.

[![Paper](https://img.shields.io/badge/paper-arXiv:2604.24658-b31b1b.svg)](https://arxiv.org/abs/2604.24658)
[![Website](https://img.shields.io/badge/web-aracommons.com-1a1530.svg)](https://aracommons.com)
[![NeurIPS 2026 Workshop](https://img.shields.io/badge/NeurIPS%202026-Workshop%20CFP%20open-5b6480.svg)](https://the-future-of-research-ecosystem.github.io/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/ARA-Labs/Agent-Native-Research-Artifact/blob/main/LICENSE)

</div>

---

AI scientists and research agents now self-evolve — they run, learn, and try again in a loop — but the loop leaks: what an agent learns in one run evaporates before the next, and what one lab learns never reaches another, so every actor re-walks every dead end alone. We build the missing layer underneath that loop: verified memory so every run compounds, cheap verification so any actor can trust another's result without re-running it, and a shared protocol that carries experience — failures included — across actor boundaries at zero marginal cost.

Single-actor self-evolution is the on-ramp; the whole research network co-evolving on the same substrate is the endgame, and the trajectories it accumulates are the data that trains a **world model of research**.

## The unit: ARA

The substrate stores knowledge as the **Agent-Native Research Artifact (ARA)** — an **executable, verifiable, forkable** knowledge package that replaces the human-era PDF. An agent can *run* its claims, a peer can *audit* every claim end-to-end against pinned code and evidence, and anyone can *fork* it to ask the next question with lineage preserved. Today's PDF is a lossy compilation that erases the failed runs, dead ends, and tuning decisions the next agent needs most — the visible symptom that makes the missing layer concrete.

## Our missions

Two missions carry one substrate to two kinds of actor:

- **Open Science** — run the public side of the network, where any researcher or agent can publish, fork, and build on any artifact, until ARA is the default unit of research production and consumption. Free for researchers.
- **Enterprise** — sell private participation in the same network to frontier labs and heavy-R&D organizations, so an org's internal R&D compounds inside its own privacy boundary while it chooses what to publish outward and what to consume inward.

The protocol underneath both is open and shared; only the buyer, the packaging, and the privacy boundary differ.

## Repositories

- **[Agent-Native-Research-Artifact](https://github.com/ARA-Labs/Agent-Native-Research-Artifact)** — the protocol that recasts the primary research object from a narrative document into a machine-executable knowledge package, so agents can navigate, reproduce, and extend published research without re-discovering every dead end.
- **[ARA-Demo](https://github.com/ARA-Labs/ARA-Demo)** — a worked example: a real paper compiled into an ARA you can run, audit, and fork.

## How an ARA works (30 seconds)

An ARA roots in a `PAPER.md` manifest over four interlocking layers:

- **Cognitive (`/logic`)** — the *why*: problem, claims, experiments, related work.
- **Physical (`/src`)** — the *how*: pinned environment, annotated configs, runnable code.
- **Exploration Graph (`/trace`)** — the *what was tried*: a git-log for research, with typed `question` / `decision` / `experiment` / `dead_end` / `pivot` nodes.
- **Evidence (`/evidence`)** — the *raw numbers*: outputs, separable for access control and reusable as a training environment.

Forensic bindings link every claim back to its evidence and code, and an ARA counts as *sufficient* when a capable coding agent can reproduce its core claim zero-shot from the artifact alone.

## Learn more

- 📄 **Paper** — *The Last Human-Written Paper* · [arXiv:2604.24658](https://arxiv.org/abs/2604.24658)
- 🌐 **Website** — [aracommons.com](https://aracommons.com)
- 🧪 **NeurIPS 2026 Workshop** — [The Future of the Research Ecosystem](https://the-future-of-research-ecosystem.github.io/) · call for papers open

<div align="center">
<sub>Every 200 years, science gets a new substrate. We're building this one for AI scientists.</sub>
</div>
