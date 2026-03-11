# Advanced Machine Learning: Mid-Semester Examination

This repository contains my submissions for the Advanced Machine Learning Mid-Semester Examination (Part B).

- **Student Name:** Harsh Gupta
- **Roll Number:** 230093
- **Course:** Advanced Machine Learning
- **Institution:** NST, Rishihood University

## Repository Structure

### Part A: Paper Selection
The selected paper for this examination is:
**"LIBLINEAR: A Library for Large Linear Classification"** (Fan et al., *Journal of Machine Learning Research*, 2008).
The paper introduces efficient dual coordinate descent methods for training large-scale linear SVMs and logistic regression.

- The LLM usage disclosure for Part A is located in the root as `llm_usage_partA.json`.

### Part B: Reproduction, Experimentation & Analysis
All Part B materials are located in the `partB/` directory.

- `partB/task 1 1.ipynb` - `task 1 3.ipynb`: Markdown notebooks detailing the core contribution (Algorithm 1), key assumptions (Linear Sufficiency), and baseline comparisons (SVMperf, Pegasos).
- `partB/task 2 1.ipynb`: Setup of a synthetic binary classification dataset (1000x20 features).
- `partB/task 2 2.ipynb`: Implementation of the **Dual Coordinate Descent (DCD)** solver from scratch.
- `partB/task 2 3.ipynb`: Result analysis, comparisons with standard `LinearSVC`, and reproducibility checklist.
- `partB/task 3 1.ipynb`: Ablation studies on **Bias Augmentation** and **Coordinate Randomization**.
- `partB/task 3 2.ipynb`: Failure Mode Analysis on non-linearly separable data (Concentric Circles).
- `partB/report.pdf`: Synthesized 4-page report (exported from `report.md`).
- `partB/data/`: Contains saved data structures and a `README.md` explaining the dataset generation.
- `partB/results/`: Contains generated plots (confusion matrix, ablation bars, failure scatter plots).
- `partB/llm task 1 1.json` - `llm task 4 2.json`: Mandatory LLM usage disclosures for each task.
- `partB/requirements.txt`: Python dependencies (NumPy, Scikit-Learn, Matplotlib, Pandas).

## Setup and Reproducibility

To reproduce the results:
1. Navigate to the `partB` directory: `cd partB`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebooks in order:
   - `task 2 1.ipynb` (Data Generation)
   - `task 2 2.ipynb` (Solver Implementation)
   - `task 2 3.ipynb` (Evaluation)
   - `task 3 1.ipynb` (Ablations)
   - `task 3 2.ipynb` (Failure Mode)

---
*Created by Harsh Gupta (230093) as part of the AML Mid-Sem 2026 Examination.*
