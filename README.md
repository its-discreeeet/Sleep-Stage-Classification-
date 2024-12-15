# Sleep Stage Classification and Sleep Apnea Prediction

This project aims to perform **sleep stage classification** and **sleep apnea prediction** using the [SleepEDF]([url](https://www.physionet.org/content/sleep-edf/1.0.0/)) Dataset and the [Apnea-ECG]([url](https://physionet.org/content/apnea-ecg/1.0.0/)) Database. The models utilize deep learning techniques to analyze sleep data, classify stages, and predict the occurrence of sleep apnea events. This project uses a series of Jupyter Notebooks to preprocess data, train models, and evaluate performance.

## Project Files

1. **Apnea ECG Dataset analysis (1).ipynb**  
   - This notebook analyzes the **Apnea-ECG dataset**, which contains annotated ECG data for sleep apnea detection. It performs initial exploratory data analysis (EDA) to understand the dataset and identify important features.

2. **apnea-ecg.ipynb**  
   - This notebook focuses on preprocessing the ECG data, extracting relevant features, and preparing it for model training. It includes filtering, signal normalization, and feature engineering steps.

3. **load_parse_data.ipynb**
   - This script loads the Sleep EDF dataset from the source files and parses it into the required format. It also handles splitting the dataset into training, validation, and testing sets for model training.

5. **data_engg.ipynb**
   - This notebook is dedicated to **data engineering** tasks, including data cleaning, handling missing values, and further transformation to make the dataset suitable for deep learning models.

6. **train_model.ipynb**  
   - This notebook contains the training of the deep learning models for both sleep stage classification and sleep apnea prediction. It includes the implementation of **Attention Augmented CNN + BiLSTM** for model training, evaluation, and tuning.
  
   - 
