# LLM Fingerprint Skill

A skill for identifying and verifying AI model identity through multi-stage behavioral analysis. Works with omp, Claude Code, and any agent that discovers `~/.agents/skills/`.

## Features

- Multi-stage identity verification protocol
- Knowledge boundary probes (time-anchored events)
- Behavioral fingerprinting (stylistic patterns, refusal vectors)
- Statistical pattern analysis
- Quick fingerprint tests for rapid identification

## Installation

```bash
bunx skills add ParticleG/llm-fingerprint-skill
```

Or manually:

```bash
git clone https://github.com/ParticleG/llm-fingerprint-skill ~/.agents/skills/fingerprint
```

## Usage

Trigger phrases:

- "identify this model"
- "fingerprint the AI"
- "verify model identity"
- "knowledge cutoff test"
- "who are you really"

## Based on Research

This skill incorporates techniques from recent academic papers:

- Hide and Seek (arXiv:2408.02871)
- RoFL (arXiv:2505.12682)
- TRAP (arXiv:2402.12991)
- UTF (arXiv:2410.12318)
- And more...

## License

MIT
