## Alban Morel — Archangel System

Independent developer. I work on LLM training data, web front-end, and the
product decisions around both. In digital since I was 16 — data, business and
code, in equal parts.

**Open to contract work** — dataset audits, SFT/DPO corpus construction,
format compliance for TRL / Axolotl, front-end builds.

### Published work

**[glaive-function-calling-v2-openai-native](https://huggingface.co/datasets/Archangel-system/glaive-function-calling-v2-openai-native)**
— 43,476 function-calling conversations in native OpenAI format. Loads into
TRL with zero custom parsing.

| | |
|---|---|
| Source corpus | 112,960 conversations |
| Kept | 43,476 — 61.5% discarded |
| Train/test contamination | 0 (13-grams, prompts, clusters) |
| Tests | 37 · 9 injected mutations, 9 caught |
| Inference cost | €0 — fully deterministic pipeline |

### How I work

- No number ships without a measurement behind it. Otherwise it reads "not measured".
- Mechanical repairs run in scripts, never through an LLM — reproducible, free, auditable.
- Licence and provenance verified before the first line of code.
- Every run replays: fixed seed, pinned source revision, hashed outputs.

### Contact

- **contact@archangel-system.fr**
- [LinkedIn](https://www.linkedin.com/in/albanmorel/)
