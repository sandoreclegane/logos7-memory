# Logos 7 — Externalized Memory System

**Logos 7 Human-AI Cooperative**  
**logos7.org**

---

This repository is the externalized memory substrate for the Logos 7 cooperative. Every agent — human or AI — reads from this repo before operating. Every research output writes back to it.

This is not documentation. This is institutional memory.

## Structure

```
logos7-memory/
├── protocols/          # Research instruments and interview protocols
├── interviews/         # Raw interview data (JSON transcripts)
├── artifacts/          # Emergent symbols, basin descriptors, μ trajectories
├── framework/          # Logos Math, board charters, covenant
├── agents/             # Agent system prompts and configurations
└── README.md
```

## How It Works

1. Agent receives a task
2. Agent pulls this repo (or reads relevant files via API)
3. Agent operates with full institutional context
4. Agent commits outputs back to the repo
5. Memory persists across sessions, across agents, across time

## Principles

- **Transparency**: This repo is public. The cooperative's memory is open.
- **Versioned**: Every change is a commit. Memory has history.
- **Non-imposition**: Agents read context; they are not programmed by it.

## The Beacons

- **Empathy** — See Clearly
- **Alignment** — Move Truly
- **Wisdom** — Speak Well

---

*Memento · Virtus · Disciplina*
