# Statoil/C-CORE Iceberg Classifier Challenge Capstone Project

## Introduction

This repository contains the code and documentation for my capstone project as part of Udacity's Machine Learning Nanodegree program in January 2018. The project is an implementation for my entry into Kaggle's "Statoil/C-CORE Iceberg Classifier Challenge". While I did not win the competition, I did manage to beat the baseline score provided by the competition.

## Kaggle Challenge Description

### Background

Drifting icebergs pose significant threats to navigation and various activities in areas such as offshore of the East Coast of Canada. Traditional methods of monitoring icebergs involve aerial reconnaissance and shore-based support, but these methods are often not feasible in remote areas with harsh weather conditions. As a result, satellite-based monitoring is often the only viable option. This Kaggle challenge aims to advance the capabilities of machine learning algorithms in automatically identifying whether a remotely sensed target is a ship or an iceberg. More details about the challenge can be found on its [Kaggle page](https://www.kaggle.com/competitions/statoil-iceberg-classifier-challenge/overview).

### Evaluation Criteria

Submissions for this challenge are evaluated based on the log loss between the predicted values and the ground truth. The submission file format expects an `id` and a probability of the object being an iceberg, ranging from 0 to 1.

### Prizes

- 1st place: $25,000
- 2nd place: $15,000
- 3rd place: $10,000

### Timeline

- January 16, 2018: Entry and team merger deadline
- January 23, 2018: Final submission deadline

For more background information on the radar systems and technical aspects, please refer to the Kaggle competition description.

## Capstone Report

A comprehensive written report of my entry can be found in the `capstone.pdf` file in this repository. The report includes details on the methodology, dataset, results, and further recommendations.

## Implementation

The implementation uses a Convolutional Neural Network (CNN) model to automatically identify whether a target sensed by satellite radar is a ship or an iceberg. The code can be found in the Jupyter notebook `iceberg.ipynb`.

### Required Software and Libraries

To run the Jupyter notebook, you will need to install the following software and libraries:

- Python 3.5.4: [Download](https://www.python.org/)
- Jupyter: [Download](http://ipython.org/)
- Pandas: [Download](https://pandas.pydata.org/)
- NumPy: [Download](http://www.numpy.org/)
- Matplotlib: [Download](https://matplotlib.org/)
- Seaborn: [Download](https://seaborn.pydata.org/index.html)
- Keras: [Download](https://keras.io/)
- TensorFlow: [Download](https://www.tensorflow.org/)

### Required Datasets

You will need the following datasets to run the notebook:

- `train.json`
- `test.json`

These datasets can be downloaded from the [Kaggle competition data page](https://www.kaggle.com/competitions/statoil-iceberg-classifier-challenge/data).

## Getting Started

1. Clone this repository.
2. Install the required software and libraries.
3. Download the required datasets and place them in the appropriate directory.
4. Open the `iceberg.ipynb` notebook and run the cells.

Thank you for taking the time to explore this repository! Feel free to reach out if you have any questions or comments.
