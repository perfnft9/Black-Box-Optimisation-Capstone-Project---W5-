# Black-Box-Optimisation-Capstone-Project---W5-
This repository documents my Black-Box Optimisation (BBO) capstone project. The goal is to iteratively optimise eight unknown functions using machine learning. I apply Gaussian Process surrogate modelling with an adaptive exploration–exploitation strategy, refining query selections weekly based on accumulated feedback and uncertainty estimates.
├── data/
│   ├── raw/                  # Initial datasets and weekly feedback
│   ├── processed/            # Combined datasets per function
│
├── notebooks/                # Experimental modelling notebooks
│
├── src/
│   ├── surrogate_model.py    # Gaussian Process implementation
│   ├── acquisition.py        # UCB / EI logic
│   ├── utils.py              # Helper functions
│
├── results/
│   ├── weekly_submissions/   # Query history
│   ├── performance_logs/     # Best values per iteration
│
├── requirements.txt
├── README.md


Project Overview

Brief description of your black-box optimisation project.

Goals and function descriptions.

Repository Structure ✅ (Step 2 content)

data/ – Function evaluation data with raw inputs/outputs and samples.csv.

notebooks/ – Weekly analysis notebooks.

src/ – Reusable utilities.

submissions/ – Query logs for traceability.

requirements.txt / README.md – Dependencies and context.

Libraries & Rationale

PyTorch, scikit-learn, NumPy/Pandas, Matplotlib/Seaborn.

Why you chose custom NN ensembles over GPyTorch/BoTorch.

Planned Improvements

results/ for plots/tables.

config/ for strategy parameters.

models/ for NN checkpoints.

Documentation / Reproduction

Week 5 results.

NN architecture (hidden dims, dropout, ensemble size).

Lessons learned.

How to regenerate queries.
