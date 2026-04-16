# Repository Setup Guide

This document describes how to create and initialize the repository structure.

## 1. Create the Repository

```bash
git clone https://github.com/JasminDoe/Causal-Inference-Roadmap.git
cd Causal-Inference-Roadmap

mkdir 01_foundations 02_causal_inference 03_dags 04_examples 05_code_examples

touch README.md
touch 01_foundations/probability_basics.md
touch 01_foundations/random_variables_and_expectation.md
touch 01_foundations/statistical_models_estimands_estimators.md

touch 02_causal_inference/potential_outcomes.md
touch 02_causal_inference/causal_effects_and_estimands.md
touch 02_causal_inference/exchangeability_confounding.md
touch 02_causal_inference/consistency_positivity.md

touch 03_dags/dag_basics.md
touch 03_dags/d_separation.md
touch 03_dags/backdoor_criterion.md

touch 04_examples/ice_cream_and_drowning.md
touch 04_examples/shoes_and_headache.md
touch 04_examples/aspirin_and_stroke.md

touch 05_code_examples/README.md

git add .
git commit -m "Initial repository structure"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/causal-inference-foundations.git
git push -u origin main
