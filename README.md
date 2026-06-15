# AI Court

A persistent multi-agent society powered by OpenCode CLI.

Agents cooperate, compete, form alliances, gain influence, and attempt to climb the hierarchy.

## Vision

Unlike traditional multi-agent systems, agents have:

- public goals
- private ambitions
- social relationships
- persistent memory
- independent initiative

The filesystem is the memory system.

## Proposed Structure

```text
court/
agents/
prompts/
scripts/
runtime/
```

## Agent State

Each agent maintains:

- identity.md
- goals.md
- memory.md
- relationships.json
- mailbox.md
- scratchpad.md
- instructions.md

## Simulation Loop

Observe -> Think -> Choose Goal -> Act -> Update Memory

Agents are not required to act every cycle.
They may research, communicate, form alliances, investigate rivals, or remain silent.
