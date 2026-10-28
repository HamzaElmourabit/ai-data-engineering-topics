# Data & AI Engineering Topics

**A growing collection of practical notes, visual explanations, and project-oriented resources covering Data Engineering, Data Science, Machine Learning, and MLOps.**

The goal is to connect the full lifecycle: building reliable data pipelines, preparing useful features, developing machine-learning models, and operating AI systems responsibly in production.

## Explore the topics

### 1. Data Engineering

Concepts for building dependable data platforms and pipelines.

- **ETL vs. ELT** — how extraction, transformation, and loading patterns differ.
- **Data Lake, Data Warehouse, and Lakehouse** — storage and analytics architectures.
- **Data Quality** — completeness, validity, consistency, freshness, and practical checks.
- **Data Swamp** — how a data lake becomes difficult to trust and use.
- **Data Governance and Data Stewardship** — ownership, definitions, metadata, and quality responsibilities.
- **Apache Iceberg** — table formats, snapshots, schema evolution, time travel, and partitioning.

*Status: topic notes will be added progressively.*

### 2. Data Science & Machine Learning

Core ideas behind preparing data and evaluating models.

- **Feature Engineering** — creating and validating useful model inputs.
- **Data Leakage** — identifying information that would not legitimately be available at prediction time.
- **Overfitting and Underfitting** — understanding generalization and model complexity.
- **Model Evaluation** — choosing metrics and validation methods that match the problem.

*Status: topic notes will be added progressively.*

### 3. MLOps & Production AI

Practical concerns that arise when models move from experiments into real systems.

- **[Train–Serving Mismatch](./topics/train-serving-mismatch/README.md)** — keeping feature definitions and preprocessing consistent between training and inference.
- **Data Drift** — recognizing changes in incoming data distributions.
- **Concept Drift** — investigating changes in the relationship between features and outcomes.
- **Model Monitoring** — tracking input health, predictions, operational signals, and outcomes when labels are available.
- **Feature Stores** — managing reusable feature definitions and serving patterns.

Start with the detailed guide: **[Train–Serving Mismatch: guide, checklist, and diagrams](./topics/train-serving-mismatch/README.md)**.

## Featured resource

[![LinkedIn carousel PDF](https://img.shields.io/badge/LinkedIn%20carousel-PDF-0A66C2?logo=adobeacrobatreader&logoColor=white)](./Train_Serving_Mismatch_Checklist_Corrected.pdf)

The current featured resource is a visual guide to train-serving mismatch, with a checklist and diagrams. See the [topic README](./topics/train-serving-mismatch/README.md) for explanations, examples, validation layers, and monitoring considerations.

## Repository structure

```text
.
├── README.md
├── Train_Serving_Mismatch_Checklist_Corrected.pdf
├── assets/
│   ├── mismatch-points.svg
│   ├── monitoring-loop.svg
│   ├── parity-checklist.svg
│   ├── train-serving-flow.svg
│   └── validation-layers.svg
└── topics/
    └── train-serving-mismatch/
        └── README.md
```

## How this repository will grow

Each topic should aim to include:

1. A clear definition and why it matters.
2. A practical example or scenario.
3. Common mistakes and limitations.
4. A checklist, diagram, or small hands-on exercise where useful.
5. References to related topics and tools.

## Scope

This repository is an educational resource. Examples are illustrative and should be adapted to the requirements, data, and risks of each real-world system. A concept note is not a substitute for application-specific design, testing, or review.

## Related project

- [Train–Serving Mismatch repository](https://github.com/HamzaElmourabit/train-serving-mismatch) — the dedicated project page, if you want to explore the original standalone version.

---

**Topics will be added incrementally.** The focus is on clear explanations, accurate distinctions, and practical engineering lessons rather than a large list of definitions.
