# X-ray Image Classification for Lung Diseases


## Project Overview

This project focuses on developing a Convolutional Neural Network (CNN) model to classify X-ray images of lung scans into three categories: normal patients, bacterial pneumonia, and viral pneumonia. The primary goal is to leverage deep learning techniques to achieve accurate classification and explore various strategies to optimize model performance.

## Dataset

- The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal).
- There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).
- Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou.
- All chest X-ray imaging was performed as part of patients’ routine clinical care.
- For the analysis of chest X-ray images, all chest radiographs were initially screened for quality control by removing all low-quality or unreadable scans.
- The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

**Acknowledgments**
- Data Source: [Mendeley Dataset](https://data.mendeley.com/datasets/rscbjbr9sj/2)
- License: CC BY 4.0
- Citation: [Cell](http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5)

**Note**: You can also find the dataset on [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

## Project Objectives

- **Image Classification**: Create a CNN model capable of accurately classifying X-ray images into three categories.
- **Experimentation**: Experiment with different techniques to improve model performance, including:
  - Padding strategies
  - Dropout layers
  - Batch normalization
  - Stride variations

## Project Structure

The project is structured as follows:

- **Data Preparation**: Preprocess and organize the X-ray image data, including resizing, data augmentation, and splitting into training, validation, and test sets.

- **Model Architecture**: Define the CNN architecture, incorporating various techniques such as padding, dropout, batch normalization, and strides to optimize performance.

- **Training**: Train the model using the training dataset, and monitor metrics like loss and accuracy on the validation set.

- **Evaluation**: Evaluate the trained model on a separate test dataset to assess its generalization performance.

- **Experimentation**: Experiment with different hyperparameters and architectural modifications to find the best configuration for improving validation accuracy and minimizing loss.

- **Results**: Document and present the results of different experiments, including model performance metrics and visualizations.
