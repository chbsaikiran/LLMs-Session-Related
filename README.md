# LLMs Video Series

Code and notebooks for a video series on training Large Language Models from scratch — starting at tokenization and going through pretraining and supervised fine-tuning (SFT).

## Topics

- **Tokenization** — Byte Pair Encoding (BPE), building/using tokenizers (`BPE.ipynb`)
- **Pretraining** — training a base LLM from scratch on raw text corpora
- **SFT (Supervised Fine-Tuning)** — adapting a pretrained base model to follow instructions

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

```bash
uv sync
```

## Structure

- `BPE.ipynb` — tokenization walkthrough
- `main.py` — entry point / scratch script
