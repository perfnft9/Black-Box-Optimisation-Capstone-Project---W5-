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
