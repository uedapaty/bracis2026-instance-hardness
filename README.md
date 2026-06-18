# Learning Transferable Instance Hardness: A Meta-Learning Approach to Predict Model Difficulty Across Datasets

This repository contains the official implementation and meta-datasets for the paper presented at **BRACIS 2026**.

## Abstract
Instance Hardness (IH) quantifies the difficulty of correctly predicting the labels of individual samples in a dataset. In this work, we investigate whether the target model-based IH can be predicted strictly from data-based IHMs and, crucially, whether such predictions generalize across datasets. We propose a meta-learning framework using a probabilistic formulation derived from cross-validated predictions of a diverse pool of classifiers.

## Repository Structure
* `BRACIS2026_final.ipynb`: Main Jupyter Notebook containing the data pipeline, meta-feature extraction, ensemble consensus calculation, and experimental evaluation.
* `data/TabZilla/`: Directory where the source `.arff` datasets from the TabZilla benchmark should be placed.

## How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/seu-usuario/bracis2026-instance-hardness.git](https://github.com/seu-usuario/bracis2026-instance-hardness.git)
   cd bracis2026-instance-hardness

2. **Install dependencies:**
   pip install -r requirements.txt

3. **Download the Datasets:**
    Place the required .arff files from the TabZilla benchmark inside the data/TabZilla/ directory.

4. **Execute the Notebook:**
    Open BRACIS2026_final.ipynb in Jupyter Lab, Jupyter Notebook, or Google Colab and run all cells.

## Citation
If you use this code or metadata in your research, please cite our BRACIS 2026 paper.
