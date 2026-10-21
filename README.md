# Biomaterial Performance Project

This repository hosts the interactive dashboard and research notebook for the experimental validation project.

- Live dashboard: available at the GitHub Pages URL shown in **Settings → Pages**.
- Notebook: [experimental_validation_biomaterial_model.ipynb](experimental_validation_biomaterial_model.ipynb)

## Run the notebook

The notebook currently points to the raw-data folder on the original Mac. To run it elsewhere, update `DATA_ROOT` in the notebook to the location of your dataset and install the packages listed in `outputs/requirements.txt` from the project workspace, or install pandas, NumPy, and Matplotlib.

## Deployment

A GitHub Actions workflow deploys the root of this repository to GitHub Pages. In **Settings → Pages**, set the publishing source to **GitHub Actions**. Each push to `main` will then refresh the site.