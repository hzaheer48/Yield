# Crop Yield Prediction System

Welcome to the Crop Yield Prediction System project! This project aims to revolutionize agriculture by utilizing data-driven insights to predict crop yield. By forecasting both hg/ha yield and area yield, it endeavors to empower farmers, policymakers, and stakeholders with invaluable information for informed decision-making, ultimately contributing to enhanced food security and sustainable agricultural practices.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Overview](#project-overview)
  - [Data Import and Cleaning](#data-import-and-cleaning)
  - [Visualization](#visualization)
  - [Model Training](#model-training)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project employs Support Vector Regression (SVR), Random Forest Regression, Neural Network Regression, and K-Nearest Neighbors (KNN) algorithms to predict crop yield. It encompasses various stages such as data cleaning, exploratory data analysis, and model training to create an effective crop yield prediction system.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries (see [requirements.txt](requirements.txt))

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hzaheer48/crop-yield-prediction.git
   cd crop-yield-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Yield.ipynb
   ```

## Project Overview

### Data Import and Cleaning

The project begins with importing crop yield-related data and cleaning it to ensure the dataset's integrity. Columns with missing values are handled, and unnecessary columns are dropped.

### Visualization

Visualizations provide insights into crop yield distribution across different items, years, and geographic areas. Explore the visualizations to better understand the dataset.

### Model Training

Various machine learning models, including SVR, Random Forest, Neural Network, and KNN, are employed for training and evaluating the crop yield prediction system.

## Usage

1. Open the Jupyter Notebook in your local environment.
2. Execute each cell sequentially to run the entire project.
3. Analyze the visualizations and model evaluations to understand the predictive performance.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.