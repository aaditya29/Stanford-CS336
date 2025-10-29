# Learning Stanford CS336: Language Modeling from Scratch

This repository documents my work for [Stanford CS336: Language Modeling from Scratch(Spring 2025)](https://stanford-cs336.github.io/spring2025/).
Here you will find:

- All assignment solutions, code and experiments
- My personal notebooks and explorations beyond the assignments
- Notes, summaries, and derivations of course concepts
- References, research papers and additional resources

The aim is to build a deep, bottom-up understanding of modern language models by _implementing them from scratch_, rather than using high-level abstractions.

---

## Course Overview

CS336 covers the full pipeline of building language models, from raw data to deployment, including:

- Tokenization, data collection and cleaning
- Transformer architectures and self-attention
- Training large-scale language models and scaling laws
- Performance optimisation, distributed training
- Inference, sampling techniques
- Alignment and reasoning: supervised finetuning, RLHF

This is an implementation-heavy course: you write the plumbing of the model yourself rather than using “plug-and-play” frameworks.

## What This Repository Contains

- Pure implementations (e.g., PyTorch) built from first principles
- Training scripts, config files, logs and checkpoints
- Explanation-rich notebooks and commentary alongside code
- Extended experiments: e.g., sampling vs greedy decoding, memory vs speed trade-offs, scaling behaviour
- A personal reference base for future research in language modelling

---

## Why This Repository Exists

- To document and publicly share a deep dive into language modelling
- To build and maintain clean, reproducible implementations for learning and future work
- To serve as a reference for myself (and others) when building large-scale models or doing research
- To emphasise clarity of intuition, code and experiments — not just “making it run”

---

## Useful Links & References

- Course website: [Stanford CS336 – Spring 2025](https://stanford-cs336.github.io/spring2025/)
- Lecture schedule and assignment deadlines (see course site)
- Recommended foundational papers:

  - “Attention Is All You Need”
  - “Scaling Laws for Neural Language Models”
  - Recent papers on RLHF and alignment

---

## Contributing & Notes

While this is primarily a personal repository I welcome suggestions or improvements (e.g., better docstrings, clearer experiments, improved visualisations). Feel free to open an issue.
