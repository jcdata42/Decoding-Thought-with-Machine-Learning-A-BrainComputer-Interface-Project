# Decoding-Thought-with-Machine-Learning-A-BrainComputer-Interface-Project

This project explores how Machine Learning can be used to decode human thought patterns through EEG signals, forming the basis of a Brain-Computer Interface (BCI). By working with real EEG data collected during motor imagery experiments, we apply signal processing and classification techniques to determine what action a person is thinking about — such as moving their hand or foot — within a given timeframe.

The work was carried out as part of the AI curriculum at **42 Urduliz**, with a strong emphasis on advanced mathematics and practical implementation. The project integrates concepts from **linear algebra**, **matrix transformations**, and **dimensionality reduction**, combining them into a real-time classification pipeline using Python and Scikit-learn.

> 🧠 This project is developed in a **cloud-based, collaborative environment**, and it is highly recommended to run it using **Google Colab** or **Amazon SageMaker Studio Lab**. These platforms provide the flexibility and computing resources required for EEG processing, while also supporting reproducibility and teamwork.

## Notebooks

- **`raw_data_analysis_visual_own_pca.ipynb`**  
  This notebook focuses on **exploratory data analysis and signal processing**. It loads raw EEG data, applies filtering techniques to isolate relevant frequency bands, and visualizes the signals before and after preprocessing. It also includes a custom implementation of **Principal Component Analysis (PCA)** to reduce dimensionality and extract meaningful features.

- **`train_test_predict.ipynb`**  
  This notebook contains the **full machine learning pipeline**: from loading transformed features to training classification models and evaluating their performance. It uses Scikit-learn’s pipeline API to integrate dimensionality reduction and classification, and simulates real-time prediction of motor imagery tasks. It also includes performance metrics and cross-validation scores.

## Main Objectives

- Parse and filter EEG signals collected during motor imagery tasks.
- Extract relevant features using frequency band selection.
- Apply **dimensionality reduction techniques** (e.g., PCA) to high-dimensional EEG data.
- Classify mental actions using machine learning algorithms from Scikit-learn.
- Simulate real-time predictions on data streams.
- Evaluate model accuracy using cross-validation on never-seen data.

## Dataset

The EEG data comes from the **EEG Motor Movement/Imagery Dataset** hosted by [PhysioNet](https://physionet.org/content/eegmmidb/1.0.0/). Participants were asked to perform or imagine specific movements in response to visual prompts, providing a labeled dataset for training and validation.

---

This project demonstrates how Machine Learning and mathematics can work together to turn raw brain signals into structured predictions — opening doors to new forms of human-computer interaction.
