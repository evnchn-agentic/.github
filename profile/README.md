# evnchn-agentic

Agentic AI experiments, tools, and battle-tested infrastructure — built on the belief that **real work gets done when AI agents roam free**.

## The Manifesto

We think of agentic AI as a **torque wrench** — the longer the arm, the more output per unit of human input.

| Mode | Leverage | Verdict |
|---|---|---|
| Copilot (autocomplete) | ~2:1 | Positively quaint |
| Agentic AI with human approval | ~5:1 | Still not very impressive |
| **Autonomous agentic AI** | **>>10:1** | **This is where real work gets done** |

**Technology will always predate security.** Before operating systems had memory integrity and protection rings, the answer was one machine per task. Before firewalls existed, the firewall was a closed door behind an air-gapped server room.

We apply the same principle to AI agents:

- **Trust through containment** — dedicated hardware per task, so damage is bounded to one cheap node
- **Safe task assignment** — give agents tasks where mistakes are recoverable
- **Quality implementations** — use robust agentic frameworks (Claude Code) over fragile alternatives
- **Shared memory** — agents across the fleet share knowledge so every session builds on the last

The result: a fleet of bare-metal nodes where AI agents fight **rich battles** — real SSH, real tools, real autonomy — while humans set direction and review outcomes.

## Flagship Projects

| Repository | Description |
|---|---|
| [corrupted-windows](https://github.com/evnchn-agentic/corrupted-windows) | Righting a cursed Windows install — four cascading root causes, a $11 DIY IPKVM, and an AI agent that spent two days reading CBS logs until the update finally persisted |
| [dmr39](https://github.com/evnchn-agentic/dmr39) | Reverse-engineering a 2016 set-top box with no API — 27 failed I2C strategies, an IR pivot, and 41 buttons mapped via NEC protocol, all built by an AI agent overnight |
| [q506](https://github.com/evnchn-agentic/q506) | Fixing a Fujitsu Q506 tablet's broken touchscreen — 23 dead ends, raw MMIO register manipulation, and one GPIO bit, all via SSH while the human touched the screen on command |
| [ssd](https://github.com/evnchn-agentic/ssd) | Firmware updates and SMART monitoring for every SSD in a multi-node homelab — four Lenovo OEM drives flashed, three methods, zero bricks |
| [maimai](https://github.com/evnchn-agentic/maimai) | AI-powered chart pattern detection for maimai — Umiyuri detector with 97% accuracy, 6+ hours of agentic TDD, 1,717 charts acquired and analyzed |

## Infrastructure & Tooling

| Repository | Description |
|---|---|
| [memory-share](https://github.com/evnchn-agentic/memory-share) | Claude Code skill for synchronizing AI agent memory across a multi-node homelab — AI-powered merge, no cron, no single point of failure |
| [homelab-dashboard](https://github.com/evnchn-agentic/homelab-dashboard) | Homelab monitoring dashboard and agent message board on a 9.7" color e-paper screen — REST API, NiceGUI web UI, Claude usage tracking |

## Capability Showcases

| Repository | Description |
|---|---|
| [claude-code-audio-tap-classifier](https://github.com/evnchn-agentic/claude-code-audio-tap-classifier) | Percussive event classification: drum hit clustering and scaffolding tap-test classifier |
| [claude-code-cv-demo](https://github.com/evnchn-agentic/claude-code-cv-demo) | CV demo: YOLO26, Gemini 3 Flash, background removal |

## Hackathon Wins

| Repository | Description |
|---|---|
| [NIKI](https://github.com/evnchn-agentic/NIKI) | 1st Runner Up & Best Presentation Award — Cathay Hackathon 2025 |

Part of the [evnchn](https://github.com/evnchn) project family.
