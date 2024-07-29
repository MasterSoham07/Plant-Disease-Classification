# Plant Disease Detection

This repository contains code and resources for detecting plant diseases using machine learning techniques. The dataset used for training and evaluating the models has been sourced from Kaggle. The goal is to create an efficient and accurate model that can identify various plant diseases from images.

## Introduction

Plant diseases are a significant threat to agriculture, impacting both the quality and quantity of crop production. Early detection and identification of plant diseases can help mitigate these impacts. This project aims to leverage machine learning to build a model that can accurately classify plant diseases from images.

## Dataset

The dataset used in this project has been obtained from [Kaggle](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset/data). It contains images of healthy and diseased plants across various species. The dataset is structured as follows:

- `train`: Contains training images.
- `valid`: Contains validation images.
- `test`: Contains testing images.

## Installation

To run this project, you need to have Python installed. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Web App

The app.py file contains the Streamlit web application for the project. It allows users to upload images of plants and get predictions about potential diseases. The app provides a user-friendly interface for interacting with the trained model and viewing results.

To run the web app:

Open a terminal window.

Execute the following command:

```bash
streamlit run app.py
```

## Usage

1. Open the web app in your browser.
2. Upload an image of a plant from the test set.
3. View the predicted disease.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Any improvements, bug fixes, or additional features are welcome!

## Acknowledgements

- The dataset was provided by Kaggle.
- Thanks to the contributors and developers of the tools and libraries used in this project.