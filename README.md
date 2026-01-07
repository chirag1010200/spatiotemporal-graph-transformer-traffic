# Spatiotemporal Graph Transformer for Traffic Prediction

This project implements a **Spatiotemporal Graph Transformer** that combines
Graph Neural Networks (GNNs) for spatial modeling and Transformers for temporal forecasting.

## Training Note

This repository contains a **pre-trained execution** of the Spatiotemporal Graph Transformer model.

The notebook is provided for **methodological reference and reproducibility**.
Re-running the notebook will retrain the model and may lead to overfitting.

For this reason, the notebook cells are **not intended to be re-executed**.


Tested on TensorFlow 2.x (Kaggle environment).

---
#Links
Kaggle Notebook: https://www.kaggle.com/code/chirag1016/tanformergnnfinalmodel/notebook

## Dataset
Download the METR-LA dataset from Kaggle:
https://www.kaggle.com/datasets/annnnddd/metr-la-dataset

Place the files inside a `data/` folder:
- METR-LA.h5
- adj_METR-LA.pkl

---

## How to Run
```bash
pip install -r requirements.txt

