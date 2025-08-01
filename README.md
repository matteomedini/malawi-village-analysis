# Elaboration on the analyses in the paper "Using wearable proximity sensors to characterize social contact patterns in a village in rural Malawi"

This notebook analyzes contact data within and between households in a village in rural Malawi.
I have created this project during my internship at ISI Foundation, with the aim of exploring new approaches for analyzing contact patterns in village settings using graph theory.
The data was collected by ISI Foundation, whose researchers provided the village’s inhabitants with contact proximity sensors. The paper can be found on the SocioPatterns website.
In order to compute all the different analyses, I used the same methods and formulas as described in the paper, unless otherwise stated in the code. 


## How to Use
Run these on your terminal:
git clone https://github.com/matteomedini/malawi-village-analysis.git
cd malawi-village-analysis

pip install -r requirements.txt


1. Open the notebook in Jupyter.
2. Make sure the data is in the `data/` folder.
3. Run all the cells.

## What's Inside

- "malawipaper.ipynb": The code.
- "data/": The datasets
- "requirements.txt": libraries to install

## You Need to Install

- pandas
- numpy
- matplotlib
- networkx
- python-louvain
- scipy
- scikit-learn
- seaborn
- jupyter
