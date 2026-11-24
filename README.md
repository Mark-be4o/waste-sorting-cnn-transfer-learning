# Waste Sorting Cnn Transfer Learning

Waste image classification with a pretrained CNN, class weights and fine-tuning.

## What it does

Classifies waste images into 12 classes. Uses a frozen pretrained backbone with a new head, then unfreezes and fine-tunes. Class weights handle the imbalance.

## Files

- `waste_sorting_transfer_learning.ipynb`

## Tools

TensorFlow/Keras, scikit-learn, split-folders, matplotlib, seaborn

## Dataset

[Garbage Classification, 12 classes (Kaggle)](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)

The dataset is not included in this repo.

## Results

The saved notebook copy has no recorded metrics. Run it to reproduce them.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
