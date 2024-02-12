# OCR (Optical Character Recognition) Project

<hr>

**NOTE**: The notebook may not load whole in github as it is long to render. Try to run the notebook in your local environment (Colab, Kaggle, Local Jupyter Notebooks)

<hr>

## Overview
This repository contains the code and resources for performing Optical Character Recognition (OCR) tasks. The primary goal of this project is to extract text from images using advanced computer vision techniques.

## Contents

- Images: Contains reference and query images used for testing OCR algorithms. These images were created using Canva, a popular online design tool.
- roi_config.json: This JSON configuration file defines regions of interest (ROI) within reference images. It consists of two main dictionaries:
  
    - image_dict: Describes the images and their respective ROIs.
    - shape_dict: Defines the shape of each ROI, including coordinates, height, width, and type of shape.

- Notebook: A directory for Jupyter Notebook (OCR_.ipynb) that covers various topics related to OCR, including:
  - Image Registration Process
    - Load images
    - Load, Extract and Visualize ROIs using config file
    - Image Feature detection and description using SIFT
    - Feature matching of query and reference images
    - Query Image Warping
  - Error calculation from Warped image
  - ROI in registered image
  - Text Extraction using Tessaract


## Getting Started
To run the code in this repository, follow these steps:

- Clone this repository to your local machine.

          git clone git@github.com:rupeshghimire7/OCR-of-docs.git
  
- Go inside directory.

          cd OCR-of-docs
  
- Open the Jupyter notebook OCR_.ipynb and follow the instructions provided within.

          jupyter-notebook

## Usage
The OCR_.ipynb notebook serves as the main entry point for experimenting with OCR algorithms and techniques. Each section of the notebook is well-documented with explanations and code snippets to guide you through the process.
