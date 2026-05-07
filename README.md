# MC886 Projects - Introduction to Machine Learning

This repository contains assignments developed for the course **MC886 - Introduction to Machine Learning** at the University of Campinas (Unicamp).

The projects explore fundamental machine learning concepts through practical implementations in Python and Jupyter Notebooks.

## Projects

### Project 1 - Linear Models

Folder: `project1/`

This project explores **Linear Regression** and other **Generalized Linear Models** using the Bike Sharing dataset.

The goal is to predict the number of rented bikes based on temporal and weather-related features.

Main topics covered:

- Exploratory data analysis
- Data preprocessing
- Feature engineering
- Linear regression
- Generalized linear models
- Model evaluation
- Error analysis

Dataset used:

- Bike Sharing Dataset

Files:

- `mc886_1s2026-assignment_1.ipynb`
- `bike_share.csv`

---

### Project 2 - Model Selection and Regularization

Folder: `project2/`

This project investigates the effects of **overfitting**, **regularization**, and **distribution shift** using corrupted MNIST images.

The goal is to train and evaluate multinomial logistic regression models under different data regimes and compare their performance on corrupted and clean test distributions.

Main topics covered:

- MNIST image classification
- Corrupted data analysis
- Multinomial logistic regression
- L1 and L2 regularization
- Cross-validation
- Model selection
- Generalization under distribution shift

Dataset used:

- MNIST
- MNIST-C corrupted variants

Files:

- `mc886_1s2025_assignment_2.ipynb`
- `data/`

## Repository Structure

```text
mc886-projects/
├── project1/
│   ├── bike_share.csv
│   └── mc886_1s2026-assignment_1.ipynb
│
├── project2/
│   ├── data/
│   └── mc886_1s2025_assignment_2.ipynb
│
└── .gitignore
