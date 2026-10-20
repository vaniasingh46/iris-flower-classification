# Iris Flower Classification Using Machine Learning

## Project Overview
This beginner-friendly machine learning project predicts an Iris flower species from four measurements: sepal length, sepal width, petal length, and petal width. The possible classes are Iris setosa, Iris versicolor, and Iris virginica.

Two models are trained and compared:
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

The notebook evaluates both models using test accuracy and confusion matrices. It also displays classification reports.

## Dataset
The classic Iris dataset is included in scikit-learn, so no separate dataset file is required.

Dataset documentation: https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html

The dataset has 150 samples, four numeric features, and three target classes.

## Technologies
- Python
- Jupyter Notebook / Google Colab
- pandas
- matplotlib
- seaborn
- scikit-learn

## How to Run
### Option 1: Google Colab
1. Upload `iris_flower_classification.ipynb` to Google Drive or open Google Colab.
2. Select **File → Upload notebook** and upload the notebook.
3. Run **Runtime → Run all**.

### Option 2: Local Jupyter Notebook
1. Install Python 3.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn jupyter
   ```
3. Start Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `iris_flower_classification.ipynb` and run all cells.

## Method
1. Load the Iris dataset.
2. Inspect its shape, data types, missing values, and class distribution.
3. Set the four measurements as features (`X`) and species as target (`y`).
4. Split the data into 80% training and 20% testing, using stratification and a fixed random seed.
5. Train a Decision Tree and a scaled KNN pipeline.
6. Compare test accuracy and confusion matrices.

## Results
Run the notebook to generate the actual accuracy scores and confusion matrices. The results can depend on the train-test split and model settings; the notebook uses a fixed split (`random_state=42`) for reproducibility.

**Best-performing model:** Check the generated results table after running the notebook. The conclusion should be based on the measured test accuracy, not an assumed winner.

## Conclusion
This project demonstrates a basic end-to-end supervised machine learning workflow: loading data, checking data quality, preparing features and targets, training two classifiers, and evaluating their predictions. It also shows why scaling is useful for KNN.

## Repository Structure
```text
iris-flower-classification/
├── iris_flower_classification.ipynb
└── README.md
```

## Author
Add your name and course details here before submitting.
