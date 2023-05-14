# COVID-19 Classification from Chest X-Ray using Neural Networks

This repository presents a project focused on automatically classifying COVID-19 patients using digital chest X-ray images. The main objective of this project is to develop a screening process for identifying COVID-19 cases through radiological imaging, specifically chest radiography. Deep Convolutional Neural Networks (DCNN) are employed to maximize the accuracy of COVID-19 detection.

## Introduction

The COVID-19 pandemic has had a devastating impact on global health, emphasizing the need for efficient and timely screening processes. Radiological imaging, particularly chest X-ray, plays a crucial role in the early detection of COVID-19 cases. This project aims to leverage DCNNs to automatically detect COVID-19 patients using chest X-ray images. By achieving high accuracy in classification, the proposed model enhances the screening process.

## Dataset

The dataset used in this project consists of 8,723 chest X-ray images. These images were collected and curated to ensure consistent quality and format. All images were stored in JPEG and PNG formats and were of the same size. The dataset includes X-ray images of COVID-19-positive patients as well as images from non-COVID-19 cases.

## Methodology

In this project, a custom CNN model with transfer learning techniques is proposed for COVID-19 classification using chest X-ray radiographs. Transfer learning enables the model to leverage pre-trained weights from a large dataset to enhance its performance on the specific task of COVID-19 detection. The custom CNN model is designed to achieve high accuracy, and the results show a training accuracy of over 97%.

## Results and Evaluation

The proposed model demonstrates robust performance in COVID-19 classification. The average sensitivity, specificity, and accuracy achieved by the model are remarkable, indicating its potential for reliable screening. The project's results highlight the effectiveness of transfer learning in enhancing the model's performance.

## Deployment

One advantage of the custom CNN model developed in this project is its relatively small size, which enables easy deployment for COVID-19 detection. The model can be integrated into existing healthcare systems, facilitating efficient screening processes and assisting healthcare professionals in diagnosing COVID-19 cases.

<!-- ## Repository Structure

- **`data/`**: This directory contains the dataset used for training and evaluation.
- **`models/`**: This directory contains the implementation of the custom CNN model and transfer learning techniques.
- **`results/`**: This directory stores the results and evaluation metrics obtained from the trained model.
- **`README.md`**: This file provides an overview of the repository and its contents. -->

#
## Conclusion

The COVID-19 Classification from Chest X-Ray project demonstrates the effectiveness of deep learning techniques, specifically custom CNN models and transfer learning, in automating the detection of COVID-19 cases from chest X-ray images. The proposed model achieves high accuracy, sensitivity, and specificity, making
