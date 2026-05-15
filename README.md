# Dog/Cat/Panda Image Classification

## Course Information

- **Course name:** Machine Learning
- **Course code:** CO3117
- **Semester:** Semester I
- **Academic year:** 2025–2026

## Instructor Information

- **Instructor:** TS. Lê Thành Sách, TS. Trương Vĩnh Lân
- **University:** Ho Chi Minh City University of Technology, VNU-HCM
- **Department:** Department of Computer Science

## Team Members

| No. | Full Name | Student ID | Email |
|---:|---|---|---|
| 1 | [Vũ Song Anh] | [2252048] | [Fill email] |
| 2 | [Đặng Trung Hiếu] | [2310940] | [Fill email] |
| 3 | [Nguyễn Anh Tuyên] | [2353282] | [Fill email] |
| 4 | [Nguyễn Anh Minh Tuệ] | [2353281] | [Fill email] |
| 5 | [Bùi Thanh Tuyền] | [2353284] | [Fill email] |
## Project Objectives

This project implements **Assignment 3: Machine Learning with Image Data**.  
The objective is to build a complete traditional machine learning pipeline for image classification using the Dog/Cat/Panda dataset.

The project includes:

- Performing exploratory data analysis (EDA) on image data.
- Cleaning the dataset by removing invalid folders and duplicate images.
- Preprocessing images by converting them to RGB and resizing them to `224 × 224`.
- Extracting deep visual features using pretrained CNN models:
  - VGG16
  - ResNet50
  - EfficientNetB0
- Saving extracted feature vectors in `.npy` format.
- Training traditional machine learning classifiers:
  - Logistic Regression
  - Support Vector Machine
  - Random Forest
- Comparing different feature extractor and classifier combinations.
- Selecting the best model using validation macro F1-score.
- Evaluating the selected model on the test set.

## Instructions for Running the Notebook

### 1. Open the Colab Notebook

Open the Colab notebook here:

```text
https://colab.research.google.com/drive/1Ca0w7lQEW3A9Jw_EkI4Fs3WDCdq2f5pu?usp=sharing

Runtime → Run all

!pip install kagglehub tensorflow scikit-learn pandas numpy matplotlib seaborn pillow tqdm


## Project Structure

```text
dog_cat_panda_submission/
├── notebooks/
│   └── animal_dog_cat_panda_assignment3_pipeline.ipynb
│
├── reports/
│   └── report.pdf
│
├── features/
│   ├── X_train_VGG16.npy
│   ├── X_val_VGG16.npy
│   ├── X_test_VGG16.npy
│   ├── X_train_ResNet50.npy
│   ├── X_val_ResNet50.npy
│   ├── X_test_ResNet50.npy
│   ├── X_train_EfficientNetB0.npy
│   ├── X_val_EfficientNetB0.npy
│   ├── X_test_EfficientNetB0.npy
│   ├── y_train.npy
│   ├── y_val.npy
│   └── y_test.npy
│
├── results/
│   ├── validation_model_comparison.csv
│   ├── final_test_metrics.csv
│   ├── classification_report.txt
│   ├── optional_test_model_comparison.csv
│   └── figures/
│       └── confusion_matrix_best_model.png
│
├── modules/
│   └── README.md
│
└── README.md

##Link
https://colab.research.google.com/drive/1Ca0w7lQEW3A9Jw_EkI4Fs3WDCdq2f5pu?usp=sharing