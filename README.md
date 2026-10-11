# AI_Panic_Research

A personal research project examining the relationship between how well people understand generative AI and how they feel about it. The repo holds the anonymized survey responses and the analysis notebook.

## Contents

- `notebook.ipynb` — loads the survey data and hosts the analysis (pandas, NumPy, Matplotlib)
- `Research Study_ ... Form Responses 1.csv` — anonymized survey responses
- `requirements.txt` — Python dependencies

## Dataset

The survey collects demographic context plus a mix of technical-understanding questions and opinion statements.

- **Demographics / context:** age group, field of study or work, employment status, prior software-development involvement, and self-rated confidence in LLM/generative-AI knowledge.
- **Technical questions:** how LLMs generate text, how image generators work, model watermarking, training-data provenance, deepfakes, and hardware requirements — each with a scored correct answer.
- **Opinion items (Likert):** automation anxiety, AI as collaborator vs. replacement, deepfake and authenticity concerns, environmental impact, training-data ethics, AI regulation, and existential risk.

Responses were collected as of 19/02/2026 and anonymized before publication.

## Getting started

```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
