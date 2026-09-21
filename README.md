# Fuzzy Neural Network (FNN) with Rule Attention
This repository contains the source code, datasets including results, and book for my thesis research on predicting classification problems using linguistic deep learning approach integrated with rule attention (FNN + Rule Attention).

## Project Overview
This study evaluates and compares the performance of linguistic deep learning (FNN + Rule Attention) and baseline machine learning (K-Nearest Neighbours) across five experimental datasets:
1. **Iris:** Utilizing as a baseline dataset.
2. **QSAR:** Simple dataset which obtained from Kaggle.
3. **Galaxy Morphology** Three types of datasets: Galaxy Cruise, Galaxy Zoo 1, and Galaxy Zoo 2 obtained from each astronomical site. this dataset can accessed via link: https://bit.ly/GalaxyMorphology

## Environment
The experiments were conducted in a cloud-based **Visual Studio Code (Jupyter Notebook)** environment. The implementation relies on the following core Python libraries:
* **Python 3.x**
* **PyTorch** (Deep Learning: Neural Networks)
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Evaluation Metrics, Baseline Machine Learning)

## Setup - Python Built-in venv
```
# Open Terminal in the project directory
python -m venv myenv
myenv\Scripts\activate
pip install -r requirements.txt
```

## Repository Structure

```text
FNN_Attention/
├── raw data/                   # raw dataset use for preprocessing (.csv), only small file applicable.
│   └── train_rows.csv
├── code/                           # source code from 5 type of datasets use for sensitivity analysis, standard simulation, baseline simulation, and feature analysis
│   ├── Tesis (GC).ipynb
│   ├── Tesis (GC-FI).ipynb
│   ├── Tesis (GC-Parameter).ipynb
│   ├── Tesis (GC-ML).ipynb
│   ├── Tesis (GZ1).ipynb
│   ├── Tesis (GZ1-FI).ipynb
│   ├── Tesis (GZ1-Parameter).ipynb
│   ├── Tesis (GZ1-ML).ipynb
│   ├── Tesis (GZ2).ipynb
│   ├── Tesis (GZ2-FI).ipynb
│   ├── Tesis (GZ2-Parameter).ipynb
│   ├── Tesis (GZ2-ML).ipynb
│   ├── Tesis (Iris).ipynb
│   ├── Tesis (Iris-ML).ipynb
│   ├── Tesis (Kimia).ipynb
│   ├── Tesis (Kimia-FI).ipynb
│   ├── Tesis (Kimia-Parameter).ipynb  
│   └── Tesis (Kimia-ML).ipynb      
├── Thesis.zip                  # My thesis book
├── LICENSE                     # MIT License
├── README.md                   # Project documentation
└── requirements.txt            # List of Python dependencies

```

## Dashboard
The leaflet dashboard of galaxy morphology can be access via link: https://bit.ly/RepositoriMorfolaxy
