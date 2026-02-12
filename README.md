# DataSummit at MultiPRIDE 2026 – Reclamation of Slurs (Classification)

Colab/Jupyter notebook to run the experimental pipeline and reproduce the classification results for:
"DataSummit at MultiPRIDE 2026: Multilingual Automatic Detection of Reclamation of Slurs in the LGBTQ+ Context Task".

## Dataset
The dataset was provided by the MultiPRIDE/EVALITA 2026 organizers and is not included in this repository.
To avoid any potential violation of the challenge data policy/licensing terms, we chose not to redistribute it.

## Reproducibility
- Tested on Google Colab
- Run all cells in `Multipride_EVALITA_Project.ipynb` to reproduce results.

## Data folder structure
Place the provided CSV files in `data/` as follows (this folder should be ignored by git):

```text
data/
  train_it.csv
  train_es.csv
  train_en.csv
  it_test.csv
  es_test.csv
  en_test.csv
