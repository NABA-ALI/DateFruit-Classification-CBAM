# DateFruit-Classification-CBAM
Task Deep Learning Approach for Date Fruit Variety and Quality Classification Using ResNet-18 and CBAM
Date Fruit Classification Using ResNet-18 and CBAM

Project Overview

This project investigates a multi-task deep learning approach for automated date fruit classification. It aims to classify date fruit varieties and assess their quality using a Convolutional Neural Network (CNN) enhanced with the Convolutional Block Attention Module (CBAM).

The proposed architecture integrates ResNet-18 as a feature extraction backbone with channel and spatial attention mechanisms to improve feature representation and classification performance.

Research Objectives

* Develop a deep learning model for date fruit variety classification.
* Classify date fruit quality into three categories.
* Investigate the effectiveness of CBAM attention mechanisms.
* Compare the proposed approach against baseline models.
* Explore computational efficiency for potential edge deployment.

Dataset

The project uses the Date Fruit Dataset for Inspection and Grading.

Dataset source: Maitlo et al.
DOI: 10.17632/s5zfvsw5kv.3

The dataset contains images of date fruits representing different varieties and quality grades.

Proposed Architecture

The proposed model consists of:

1. ResNet-18: Extracts deep visual features from input images.
2. CBAM: Applies channel and spatial attention to refine feature representations.
3. Global Average Pooling: Aggregates spatial feature information.
4. Multi-Task Classification Heads:
    * Variety Classification.
    * Quality Classification (Three Classes).

Methodology

The research methodology includes:

* Image preprocessing and dataset preparation.
* Training and evaluation of baseline models.
* Integration of CBAM into the ResNet-18 architecture.
* Joint optimization of variety and quality classification tasks.
* Performance comparison using classification evaluation metrics.

Technologies

* Python
* PyTorch
* Google Colab
* Deep Learning
* Convolutional Neural Networks (CNNs)
* ResNet-18
* CBAM

Project Structure

DateFruit-Classification-CBAM/
│
├── README.md
├── date_fruit_classification.ipynb
└── ...

Evaluation

The models are evaluated using classification metrics, including:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Team

Developed as part of the CAI 421 – Deep Learning course project at Princess Nourah bint Abdulrahman University.

References

Maitlo et al. Date Fruit Dataset for Inspection and Grading. Mendeley Data.
https://doi.org/10.17632/s5zfvsw5kv.3

CBAM: Convolutional Block Attention Module.
https://arxiv.org/abs/1807.06521

ResNet: Deep Residual Learning for Image Recognition.
https://arxiv.org/abs/1512.03385
