---

# Emergency Vehicle Detection using YOLOv5

This repository contains a project aimed at detecting emergency vehicles using the YOLOv5 model. The project involves creating a custom dataset, annotating the images, training the model, and making inferences.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project aims to detect emergency vehicles in images using the YOLOv5 object detection model. The need for such a system arises from the necessity to identify and provide right of way to emergency vehicles like ambulances, fire trucks, and police cars.

## Dataset

The dataset used in this project has been created manually and contributed to Kaggle. It consists of images of emergency and non-emergency vehicles which have been annotated using the LabelImg tool.

- **Data Collection**: Images were downloaded from various sources.
- **Annotation**: The images were annotated using the LabelImg tool to mark the emergency and non-emergency vehicles.

You can find the dataset on Kaggle [here](https://www.kaggle.com/datasets/ikramali585/emergency-vs-non-emergency-vehicles).

## Project Structure

The project is contained within a single Jupyter Notebook file that encompasses all the necessary steps:

1. **Data Downloading**: Code to download the dataset.
2. **Data Visualization**: Visualizing the images and annotations.
3. **Training**: Training the YOLOv5 model on the annotated dataset.
4. **Inferencing**: Making predictions on new images using the trained model.

## Installation

To run this project, you will need the following dependencies:

- Python 3.x
- PyTorch
- OpenCV
- Matplotlib

## Usage

To run the project:

1. Open the Jupyter Notebook file.
2. Follow the steps in the notebook to download the dataset, visualize the data, train the model, and make inferences.

```bash
jupyter notebook detection_emergencyvehicals_yolov5.ipynb
```

## Results

The model has been trained and tested on the custom dataset. You can find the results and performance metrics within the Jupyter Notebook.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, feel free to create a pull request or open an issue.

---
