# Liver Tumor Segmentation using AI

This repository contains the code and resources for the project "Liver Tumor Segmentation using AI." The project employs deep learning techniques to accurately segment liver tumors from medical images.

## Table of Contents
- Introduction
- Project Structure
- Installation
- Usage
- Results
- Contributing
- Acknowledgements

## Introduction

Liver tumor segmentation is a crucial task in medical image analysis, assisting in the diagnosis, treatment planning, and monitoring of liver cancer. This project implements a deep learning model to segment liver tumors from CT scans using a convolutional neural network (CNN) architecture.

## Project Structure

- `Liver_tumor_segmentation.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and visualization of the segmentation results.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/liver-tumor-segmentation.git
    cd liver-tumor-segmentation
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Liver_tumor_segmentation.ipynb
    ```

2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate the results.

## Results

Include any visual results, metrics, or example outputs here. For example:
- loss: 0.0254 - accuracy: 0.9897
- Example segmentation results:

![CT-of-the-abdomen-showing-the-segment-3-liver-lesions-at-diagnosis](https://github.com/user-attachments/assets/63afa17f-84d2-48f9-855a-e02a79aa56a5)


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Acknowledgements
Data used : LiTS17
- TensorFlow/Keras for the deep learning framework.
- Any other libraries or tools used in this project.


