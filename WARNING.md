# Warnings

Preconditions that apply before anyone copies what this org does. These are load-bearing, not disclaimers — skip them and the leverage numbers in [the manifesto](https://github.com/evnchn-agentic) become liabilities, not assets. Filter yourself out early and save yourself some time; filter yourself out late and the cost lands somewhere more expensive.

Two kinds of agents, three filters.

- [Autonomous Agentic Coding](#autonomous-agentic-coding) — the machine filter, the operator filter.
- [Agentic Learning](#agentic-learning) — pushback-capable model required.

---

## Autonomous Agentic Coding

> [!WARNING]
> ### The machine filter
>
> Everything in the doer pillar assumes hardware segregation and the expectation that things will go wrong. Agents will delete files they shouldn't. Agents will brick SSDs, corrupt partitions, flash the wrong firmware, and occasionally leave a node in a state where the fastest recovery is a reinstall. That's fine here, because every node is cheap, every task is bounded to one machine, and nothing important lives in one place. Make copies. Assume any single node can vanish tonight.
>
> If you're reading this on a work laptop, thinking about pointing Claude Code at your employer's production database — run. This org is the wrong reference implementation for you. The containment model is the whole point, and without it, the leverage numbers in the manifesto become a liability, not an asset.

> [!WARNING]
> ### The operator filter
>
> The torque wrench multiplies angular displacement, not grip strength. In human terms: it amplifies breadth — the inventory of weird angles you can queue up when an agent hits a wall — not depth in any single domain.
>
> If you're a deep specialist used to being the smartest person in the room about one thing, the tool will feel underwhelming, because your one correct answer is already tight and there's nothing for the wrench to sweep through. If you're the kind of person who took apart alarm clocks as a kid and never quite reassembled them, who studied something interdisciplinary on purpose, who knows a little about I2C and a little about ext4 and a little about NEC IR protocols and can feel when two of them rhyme — this tool was built for your shape of mind. The repos in this org are what it looks like when someone trained wide meets an agent trained deep, and they split the work down the seam.
>
> Neither filter is a flex. They're load-bearing preconditions. Skip them and the org is cosplay at best and a resume-generating event at worst.

---

## Agentic Learning

> [!WARNING]
> ### Pushback-capable model required
>
> The thinker pillar requires a model that reliably pushes back on wrong premises rather than building confident reasoning on top of them. See [BullshitBench](https://petergpt.github.io/bullshit-benchmark/viewer/index.v2.html) and the [thinker philosophy](./PHILOSOPHY_THINKER.md).
>
> Using this method with a low-pushback model is actively dangerous. The failure is silent — the model agrees with your flawed premise, builds confident reasoning on top of it, and hands you sophisticated-sounding conclusions you cannot tell apart from correct ones. You will not know until you act on it. The [road-traffic](https://github.com/evnchn-agentic/road-traffic) session contains an early-amber intersection idea a low-pushback model would have helped design. The intersection would have killed someone. This is not a marketing claim; it is a safety constraint, and softening it would betray the people most likely to try the method on the wrong tool.
>
> **Alternative path — [pushback-primer](https://github.com/evnchn-agentic/pushback-primer).** The gap BullshitBench measures is a *default-behaviour* gap, not a capability gap. Every frontier non-Anthropic open-weight model we tested has the capacity to push back on broken premises; they just don't do it without instruction. A single plain-English system prompt lifts `deepseek/deepseek-chat` and `qwen/qwen3-235b-a22b` from 4–8% green on BullshitBench v2 to 99–100% green — above the unprompted rank-1 Anthropic result — with zero false positives on a 15-item legitimate control set. If you can ship a system prompt, Agentic Learning is no longer gated on API access to Anthropic. This does not soften the warning: an un-primed low-pushback model is still silent-failure territory, and the road-traffic scenario still applies. It widens the door.
>
> As of April 2026, *default* pushback is concentrated in Anthropic's Claude models. *Primed* pushback — via [pushback-primer](https://github.com/evnchn-agentic/pushback-primer) — reaches comparable or better green rates on frontier open-weight models. Recheck whenever a new model lands, or a default changes.

---

*Back to the [manifesto](https://github.com/evnchn-agentic).*
