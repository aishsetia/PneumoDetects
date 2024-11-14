# PneumoDetects

## Pre-requisites

- Python 3.9 or later
- Poetry

## Installation and Running

1. Clone the repository
2. Install dependencies using poetry

```bash
poetry install --with dev
```

3. Clone Kaggle dataset

```bash
kaggle datasets download -d paultimothymooney/chest-xray-pneumonia
```

4. Unzip the dataset

```bash
unzip chest-xray-pneumonia.zip
```

5. Run the experiments in `experiments.ipynb`

## Stats

- Accuracy: 82.52%
- AUC: 95.03%
- F1 Score: 0.81