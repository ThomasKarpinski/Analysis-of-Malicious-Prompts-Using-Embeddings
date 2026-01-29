# Analysis of Malicious Prompts Using Embeddings and Clustering

## Project Overview
This project focuses on the analysis of malicious prompts using various embedding techniques and clustering methods. It utilizes the **PL-Guard Dataset** to explore and detect harmful inputs in natural language processing tasks.

## Key Features
- **Embeddings:** Comparison of different embedding methods including FastText and BERT (Raw and Fine-Tuned).
- **Clustering:** Application of K-Means, DBSCAN, and Hierarchical Clustering to identify patterns in malicious prompts.
- **Dimensionality Reduction:** Visualization using PCA, t-SNE, and UMAP in both 2D and 3D.
- **Outlier Detection:** Identification of anomalous prompts using Isolation Forest.
- **Robustness Analysis:** Evaluation of model performance against adversarial drifts.

## Repository Structure
- `DS_Project.ipynb`: Main Jupyter notebook containing the data analysis, model training, and evaluation.
- `Plots/`: Comprehensive set of visualizations generated during the analysis.
- `report.tex`: LaTeX source for the project report.
- `.gitignore`: Configured to exclude large model weights and binary data files.

## Dataset
The project uses the PL-Guard dataset, focused on Polish language safety in the context of LLM prompts.

## Author
Tomasz Karpiński
