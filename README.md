# UNCP ARTICLE 2026

- `01 Response to Reviewers`: response PDF and Word file, highlighted manuscript, and reviewer-action matrix.
- `02 Article`: final manuscript PDF and a ZIP containing the complete LaTeX source plus final PDF.
- `03 Data`: exact repeat-inclusive dataset identified by the latest model audit.
- `04 Code`: one consolidated Google Colab notebook containing all model implementations and saved results.
- `05 Experiment`: experiment evidence grouped by reviewer-question number. Every experiment folder contains at least one valid `.ipynb` file with saved execution output.


This repository contains the complete revision package for the manuscript
“User Next Click Prediction Using Machine Learning for UX Analysis.”

## Contents

- `01 Response to Reviewers/`
  - Response-to-reviewers document
  - Reviewer action matrix
  - Highlighted manuscript showing revised sections

- `02 Article/`
  - Final manuscript PDF
  - LaTeX source
  - ZIP archive containing the final article package

- `03 Data/`
  - Analytical dataset
  - Data documentation and provenance notes

- `05 Experiment/`
  - Reproducible experiment files
  - Model configurations
  - Evaluation outputs and statistical comparisons

## Reproducibility

The revised evaluation uses a user-disjoint train/validation/test protocol. The primary dataset contains 46,194 click events grouped into 4,223 sequences from 52 recorded User IDs. These sequences produce 41,971 supervised next-click prediction targets.

The notebooks and experiment files document the evaluated baselines, LSTM, Transformer, and UNCP model variants, together with the reported metrics and uncertainty analyses.

## Data and Code Availability

The data and code are provided for research transparency and reproducibility. Account identifiers are pseudonymized and are not used as predictive model inputs.

## Important Note

The study demonstrates next-click prediction performance and presents the model as a decision-support tool for UX analysis. Direct causal claims about improved usability, user satisfaction, or UX-testing efficiency require a future controlled user study.
