# Spike-train-classification

## Overview

This project explores the classification of neuronal spike train data using classical machine learning techniques. We extract meaningful features such as **firing rate**, **synchrony**, and **inter-spike interval (ISI)** to distinguish between different stimulus conditions or neural populations.

## Objectives

- Extract biologically meaningful features from spike train data
- Perform statistical analysis to assess feature separability
- Compare classification performance across different feature sets and classifiers

## Features Extracted

- **Firing Rate**: Spikes per second for each neuron
- **Synchrony**: Pairwise correlation between neuron firing patterns
- **ISI Statistics**: Mean, standard deviation, and coefficient of variation of inter-spike intervals

## Classifiers Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

## Evaluation Metrics

- Accuracy
- F1 Score
- ROC AUC
- Confusion Matrix

## File Structure

```bash
.
├── spike_train_classification.ipynb   # Main Jupyter Notebook
├── x.npy                              # Original spike train data
├── isi_features.npy                   # Pre-computed ISI features
├── requirements.txt                   # Python dependencies
├── README.md                          # Project overview and instructions
└── slides.pdf                         # Final presentation slides (methods & results)
