<picture>
  <img src="https://raw.githubusercontent.com/evnchn-agentic/.github/main/profile/cover.webp" alt="Frieren casting, flanked by two Claude Code avatars — You're absolutely right!">
</picture>

*Two [Claude Code avatars](https://makerworld.com/en/models/2416738) standing guard. Frieren mid-cast. ["You're absolutely right!"](https://absolutelyright.lol/) — a reminder to [trust, but verify](https://en.wikipedia.org/wiki/Trust,_but_verify).*

# evnchn-agentic

Agentic AI experiments, tools, and battle-tested infrastructure — built on the belief that **real work gets done when AI agents roam free**.

## The Manifesto

I consider agentic AI as a **torque wrench** — the longer the arm, the more output per unit of human input.

| Mode | Leverage | Verdict |
|---|---|---|
| Copilot (autocomplete) | ~2:1 | Positively quaint |
| Agentic AI with human approval | ~5:1 | Still not very impressive |
| **Autonomous agentic AI** | **>>10:1** | **This is where real work gets done** |

Another observation: **technology always predates security.** Before operating systems had memory integrity and protection rings, the answer was one machine per task. Before firewalls existed, the firewall was a closed door behind an air-gapped server room.

As such, I apply these principles to AI agents:

- **Trust through containment** — dedicated hardware per task, so damage is bounded to one cheap node
- **Safe task assignment** — give agents tasks where mistakes are recoverable
- **Quality implementations** — use robust agentic frameworks (Claude Code) over fragile alternatives
- **Shared memory** — agents across the fleet share knowledge so every session builds on the last

The result: a fleet of bare-metal nodes where AI agents fight **rich battles** — real SSH, real tools, real autonomy — while I set direction and review outcomes. Battles which other AI agents have hardly fought before.

*[Read the full philosophy →](https://github.com/evnchn-agentic/.github/blob/main/PHILOSOPHY.md)*

## Flagship Projects

| Repository | Description |
|---|---|
| [corrupted-windows](https://github.com/evnchn-agentic/corrupted-windows) | Righting a cursed Windows install — four cascading root causes, a $11 DIY IPKVM, and an AI agent that spent two days reading CBS logs until the update finally persisted |
| [dmr39](https://github.com/evnchn-agentic/dmr39) | Reverse-engineering a 2016 set-top box with no API — 27 failed I2C strategies, an IR pivot, and 41 buttons mapped via NEC protocol, all built by an AI agent overnight |
| [minibook-x](https://github.com/evnchn-agentic/minibook-x) | Installing Kubuntu on a Chuwi MiniBook X entirely over SSH — no USB boot, no installer, just Python writing a raw ext4 image to an NVMe partition from Windows |
| [q506](https://github.com/evnchn-agentic/q506) | Fixing a Fujitsu Q506 tablet's broken touchscreen — 23 dead ends, raw MMIO register manipulation, and one GPIO bit, all via SSH while the human touched the screen on command |
| [ssd](https://github.com/evnchn-agentic/ssd) | Firmware updates and SMART monitoring for every SSD in a multi-node homelab — four Lenovo OEM drives flashed, three methods, zero bricks |
| [jp-subtitle-generator](https://github.com/evnchn-agentic/jp-subtitle-generator) | Bilingual subtitle generator for Japanese YouTube videos — 5 OCR iterations, Whisper for content, PP-OCR for timing, pixel-matched text renderer with IoU 0.91, built in one evening session |
## Agent Campaigns

Multi-session agentic projects where AI agents return again and again — building on shared memory, accumulated knowledge, and human direction. These aren't one-shot battles — they're campaigns.

| Repository | Description |
|---|---|
| [lightsword](https://github.com/evnchn-agentic/lightsword) | Running x86-64 Linux inside Safari on iOS — BusyBox with 365+ applets, native ARM64 JIT at 91 MIPS, and syscall translation, built across multiple agentic sessions |
| [maimai](https://github.com/evnchn-agentic/maimai) | AI-powered chart pattern detection for maimai — 9 structural detectors, 97% accuracy on Umiyuri, 1,717 charts analyzed across 13+ hours of agentic TDD |

## Infrastructure & Tooling

| Repository | Description |
|---|---|
| [memory-share](https://github.com/evnchn-agentic/memory-share) | Claude Code skill for synchronizing AI agent memory across a multi-node homelab — AI-powered merge, no cron, no single point of failure |
| [homelab-dashboard](https://github.com/evnchn-agentic/homelab-dashboard) | Homelab monitoring dashboard and agent message board on a 9.7" color e-paper screen — REST API, NiceGUI web UI, Claude usage tracking |
| [claude-code-time-awareness](https://github.com/evnchn-agentic/claude-code-time-awareness) | Time awareness hook for autonomous Claude Code agents — injects current time into agent context via PostToolUse, so long-running sessions know when to stop |
| [claude-code-stop-gate](https://github.com/evnchn-agentic/claude-code-stop-gate) | Stop gate hook for Claude Code — nonce-based confirmation prevents accidental session termination, with checklist for cleanup, stretch goals, and bounded-time handoff |

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
