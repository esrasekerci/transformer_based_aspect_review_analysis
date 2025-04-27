## Distilling Human Feedback for Aspect-Grounded Review Generation
This repository contains the project files for the IS 584: Deep Learning for Text Analytics term project at Middle East Technical University (METU).

## Project Overview
This project explores the automated generation of structured peer review feedback for scientific submissions using transformer-based models. Specifically, we investigate fine-tuning LongLLaMA models through human knowledge distillation, where human-authored reviews act as teacher signals to guide model behavior.

The primary focus is to generate aspect-grounded critiques that align with key dimensions of scholarly evaluation, including clarity, motivation, and soundness. By leveraging the ASAP-Review dataset—which provides full submission texts paired with human-written, aspect-annotated reviews—we aim to enhance the interpretability and quality of generated outputs.

## Dataset
We use the ASAP-Review dataset, which contains:
- Full-text conference submissions
- Human-written peer reviews
- Aspect-level annotations (e.g., clarity, motivation, soundness)
- Meta-review information and acceptance outcomes

Dataset access and description: [Dataset Link](https://drive.google.com/file/d/1nJdljy468roUcKLbVwWUhMs7teirah75/view?usp=sharing)

## Repository Structure

```bash
├── notebooks/             # Final Jupyter notebook for experiments
├── source/                # Source code and custom modules
├── reports/               # IEEE-format project reports
├── figures/               # Figures used in reporting
├── requirements.txt       # Environment dependencies
└── README.md              # Project overview
