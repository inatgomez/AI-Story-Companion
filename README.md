# Rhea: Your AI Story Companion

**Rhea** is an AI character that helps fiction writers outline and explore their stories before committing to a draft. It's built as a creative partner—not just a tool—with the goal of surfacing the _best_ version of your story.

---

## Why This Exists

Writing a story is a massive creative commitment. Rhea is here to help authors:

- Discover their story before writing it
- Brainstorm new directions and plot twists
- Compare different narrative angles
- Make informed creative decisions

---

## MVP Goals

This repo documents the development of a Minimum Viable Product (MVP) for Rhea using open-source models. Key deliverables include:

- Evaluation of small LLMs for creative tasks (1B–3B parameters)
- Prompt engineering + versioning experiments
- Interactive prototype via Gradio + Hugging Face Spaces
- Clear documentation of limits, strengths, and future directions

---

## Models Evaluated

- [`Qwen/Qwen2.5-1.5B-Instruct`](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct)
- [`Ministral-3B-Instruct`](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.3)
- [`SmolLM2-1.7B-Instruct`](https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct)

All models selected for:

- Small size (runs on 16GB RAM)
- Instruction-following ability
- Long-enough context window for story reasoning

---

## Evaluation Criteria

Coming soon in `evaluations/`:

- Prompt effectiveness
- Output creativity and coherence
- Style alignment
- Token usage and latency benchmarks

---

## Deployment Plans

Once the best model + prompt combo is selected, the prototype will be deployed to [Hugging Face Spaces](https://huggingface.co/spaces) using Gradio for interaction.
