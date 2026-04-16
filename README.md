# Causal-Inference-Roadmap
Structured notes on causal inference, from probability basics and potential outcomes to confounding, exchangeability, estimands, and DAGs.

# Causal Inference Foundations

This repository contains structured notes on causal inference, covering probability theory, potential outcomes, confounding, exchangeability, causal estimands, and directed acyclic graphs (DAGs). It is designed as a living resource that will expand over time to include statistical examples and code implementations in R and Python.

## Purpose

The goal of this repository is to provide a clear and systematic introduction to causal inference. It serves as:

- A personal knowledge base
- A teaching and learning resource
- A reference for researchers and students in epidemiology, statistics, data science, and public health
- A foundation for applied causal analysis with reproducible code

## Topics Covered

- Probability and statistical foundations
- Potential outcomes and counterfactual reasoning
- Causal effects and estimands
- Confounding and exchangeability
- Consistency and positivity assumptions
- Directed acyclic graphs (DAGs) and d-separation
- The backdoor criterion and causal identification
- Classic examples illustrating causal reasoning

Statistical examples and implementations will be added progressively.

## 📂 Repository Structure

```text
.
├── README.md
├── 01_foundations/
│   ├── probability_basics.md
│   ├── random_variables_and_expectation.md
│   └── statistical_models_estimands_estimators.md
│
├── 02_causal_inference/
│   ├── potential_outcomes.md
│   ├── causal_effects_and_estimands.md
│   ├── exchangeability_confounding.md
│   └── consistency_positivity.md
│
├── 03_dags/
│   ├── dag_basics.md
│   ├── d_separation.md
│   └── backdoor_criterion.md
│
├── 04_examples/
│   ├── ice_cream_and_drowning.md
│   ├── shoes_and_headache.md
│   └── aspirin_and_stroke.md
│
└── 05_code_examples/
    └── R implementation
