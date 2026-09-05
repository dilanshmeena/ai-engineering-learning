# Regulatory Performance Clustering Analysis

## Overview
This project is part of an AI engineering learning module (`01_Machine_Learning`). It features a Jupyter Notebook that applies unsupervised machine learning to cluster countries based on their regulatory performance. 

## Key Features
* **Data Clustering:** Segments various countries into three distinct groups:
    * Countries with the **least** regulatory performance (e.g., ERI, LBY, SOM, SYR, YEM).
    * Countries with **moderate/reasonable** regulatory performance.
    * Countries with the **highest** regulatory performance.
* **Model Evaluation:** Evaluates the quality and separation of the resulting clusters using the Silhouette Score metric. 

## Performance
The current clustering model achieves a **Silhouette Score of ~0.563**, which indicates a reasonable structure and moderate separation between the defined country clusters.

## Technologies Used
* **Language:** Python 3
* **Environment:** JupyterLab / Jupyter Notebook
* **Libraries:** `scikit-learn` (specifically `sklearn.metrics.silhouette_score` for model evaluation)

## Getting Started

### Prerequisites
Make sure you have Python installed along with the following packages:
* `jupyterlab` or `notebook`
* `scikit-learn`
* `pandas` and `numpy` (assuming these were used for data manipulation)

### Installation & Execution
1. Clone this repository or download the project files.
2. Navigate to the `ai-engineering-learning/01_Machine_Learning/` directory.
3. Launch Jupyter Lab or Jupyter Notebook:
   ```bash
   jupyter lab

4. Open regulatory_clustering.ipynb and run the cells sequentially to view the country classifications and the evaluation metrics.
