# Skin-cancer-prediction

Skin Cancer Detection is a machine learning project that aims to classify skin lesion images into two categories: malignant and benign. The project utilizes deep learning models to achieve accurate and efficient predictions.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Models in Releases](#models-in-releases)

## Introduction

Skin cancer is one of the most prevalent forms of cancer globally, and early detection plays a crucial role in improving patient outcomes. This project leverages Convolutional Neural Networks (CNNs) and Transfer Learning techniques to automatically identify and classify skin lesions, aiding medical professionals in the diagnosis process.

## Installation

To run the Skin Cancer Detection project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/skin-cancer-detection.git
   cd skin-cancer-detection
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## How to Use

1. Make sure you have installed all the required dependencies as mentioned in the [Installation](#installation) section.

2. Run the Flask web application:
   ```
   python app_cnn.py
   ```

3. Open your web browser and visit `http://localhost:5000`. You should see the Skin Cancer Detection application.

4. Upload skin lesion images through the application interface.

5. Click on the "Detect" button to initiate the prediction process.

6. The application will use the trained models to classify the uploaded image as malignant or benign. The results will be displayed on the screen.

## Models in Releases

The deep learning models used for skin cancer detection are hosted in the [GitHub Releases](https://github.com/your-username/skin-cancer-detection/releases) section. These models have been trained on a large dataset of skin lesion images to provide accurate predictions.

To use the models, follow these steps:

1. Go to the [Releases](https://github.com/your-username/skin-cancer-detection/releases) section of this repository.

2. Download the model files (`model2.h5`, `resnet.h5`, `skin_cancer_inceptionv3.h5`, etc.) from the latest release.

3. Place the downloaded model files in the root directory of the project.

4. The application will automatically load these models during runtime and use them for skin cancer detection.

