# Symmetric-Nonnegative-Embeddings-Empirical-Evaluation-and-Analysis
This repository contains my course project for CS768: Learning with Graphs, completed in Spring 2025. The project involves a reimplementation and empirical analysis of the DSNE model (NeurIPS 2023) for low-rank graph embeddings. It compares DSNE with classical methods (SVD, LPCA, BigClam), includes ablation studies (hinge loss, softmax constraints), and evaluates performance on synthetic triangle-rich and heterophilic graphs.

## Files

- **`Code.ipynb`** – A Jupyter notebook containing the full codebase: graph generation, model implementations (DSNE, SVD, LPCA, BigClam), ablation experiments (hinge loss, softmax constraints), and result visualizations.
- **`Report.pdf`** – Final write-up covering problem motivation, theoretical foundations, experimental design, comparative results, and analysis of embedding quality and interpretability.

## Description

- Implemented and evaluated the DSNE model for exact low-rank graph reconstruction.
- Compared DSNE against standard matrix factorization methods (SVD, LPCA) and community detection models (BigClam).
- Designed ablation experiments to test model sensitivity to link functions and embedding constraints.
- Constructed synthetic graphs (triangle-rich, homophilic/heterophilic, SBM variants) to assess reconstruction accuracy and community structure preservation.
- Used Python, NumPy, NetworkX, and Matplotlib for implementation, visualization, and analysis.


Due to the exceptional quality of this work, our team was awarded a direct AA (highest grade) in the course, overriding standard grade calculations.
