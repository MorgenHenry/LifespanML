# Life Expectancy Drugs-Target Interaction Matrix Completion

## Project Overview
This project applies matrix completion to predict the effects of various longevity-associated drugs on mouse lifespan. By combining chemical structural similarity (via RDKit Morgan fingerprints) and biological pathway overlap (via KEGG Jaccard similarity), the algorithm imputes missing lifespan data across different biological pathways. 

The biological data is sourced from the National Institute on Aging Interventions Testing Program (ITP), hosted on the Mouse Phenome Database.

## File Structure
* **`ITP_data_loading_Rapamycin.ipynb`**: The main Jupyter Notebook containing the data processing, similarity calculations, completion algorithm, and visualizations.
* **`Lifespan_C2015.xlsx`**: Raw lifespan data for the 2015 ITP mouse cohort.
* **`ITP_C2020_Lifespan.xlsx`**: Raw lifespan data for the 2020 ITP mouse cohort.

## Prerequisites
To run this notebook, you will need Python installed along with the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scipy`
* `rdkit`
* `requests`

You can install the necessary packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scipy rdkit requests
