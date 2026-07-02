# conformal_prediction

Working repository for a master's thesis on conformal prediction for time-series forecasting.

This snapshot contains reusable utilities, model tuning scripts, HPC-oriented experiment runners, and a small notebook example. The code appears to support multiple regression and probabilistic forecasting workflows, including classical conformal prediction, quantile-based methods, Bayesian approaches, and TCN-based pipelines.

## Overview

- Thesis topic: [fill in short thesis title]
- Primary forecasting target(s): [fill in target series or use case]
- Main datasets: [fill in data sources and time span]
- Main methods explored: classical CP, QCP, FRR, BART, boosting, k-NN, linear baselines, and TCN variants
- Current status of this repository snapshot: [fill in what is complete, partial, or experimental]

## Repository Layout

- `src/`: core data loading, metrics, models, conformal prediction, and tuning utilities
- `hpc/`: larger experiment scripts intended for batch or cluster execution
- `toy_example.ipynb`: compact notebook example for quick experimentation
- `requirements.txt`: Python dependencies for the code in this snapshot

## Setup

1. Create and activate a Python environment.
2. Install dependencies with `pip install -r requirements.txt`.
3. Verify that the expected datasets are available locally.

### Environment Notes

- Python version: [fill in]
- Package manager or environment tool: [fill in]
- Any HPC or cluster-specific setup: [fill in]

## Data

- Raw data location: [fill in]
- Processed data location: [fill in]
- External API or download steps: [fill in]
- Data preprocessing assumptions: [fill in]

## Usage

### Notebook

Open `toy_example.ipynb` to run a lightweight example and inspect the core workflow.

### Scripts

- Core utilities: import from `src/`
- Experiment scripts: run files in `hpc/` for tuning or larger-scale experiments

Example entry points:

- [fill in a minimal local script or notebook command]
- [fill in HPC submission command if applicable]

## Results

- Main thesis findings: [fill in]
- Best-performing model(s): [fill in]
- Key evaluation metric(s): [fill in]
- Calibration or uncertainty findings: [fill in]

## Reproducibility

- Random seeds used: [fill in]
- Train/calibration/test split policy: [fill in]
- Hardware assumptions: [fill in]
- Known limitations of this snapshot: [fill in]

## Development Notes

- Several scripts are written for long-running experiments and may assume access to local datasets or HPC storage.
- Some dependencies are only needed for specific model families, so a minimal environment may still work for a subset of the repository.

## Contact

- Author: [fill in]
- Institution or lab: [fill in]
- Project link or thesis reference: [fill in]
