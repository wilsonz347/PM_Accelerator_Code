# PM_Accelerator_Code

## Overview

This project is part of the PM Accelerator coding assessment, which analyzes the "Global Weather Repository.csv" dataset from Kaggle to forecast future weather trends. The dataset provides daily weather information for cities around the world, offering a comprehensive set of features reflecting weather conditions worldwide, including over 40 features.

**Dataset**: [Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data)

## Process
### 1. Data Cleaning & Preprocessing

*   **Libraries**: pandas, numpy
*   **Tasks**:
    *   Handle missing values using pandas library.
    *   Identify and manage outliers using methods like IQR.

### 2. Exploratory Data Analysis (EDA)

*   **Libraries**: seaborn, matplotlib
*   **Tasks**:
    *   Perform EDA to uncover trends, correlations, and patterns in the dataset.
    *   Generate histograms for key weather variables like temperature and precipitation.
    *   Investigate relationships between different weather features.

### 3. Model Building

*   **Libraries**: `pmdarima`, `statsmodels`
*   **Tasks**:
    *   Build a forecasting model (SARIMA) to predict future weather conditions.
    *   Use the `lastupdated` feature for time series analysis.
    *   Evaluate the model's performance using appropriate metrics (Root Mean Squared Error).
    *   Utilize `auto_arima` for automated model selection and parameter tuning.

## Installation Guide

To set up the project environment, follow these steps:

1.  **Clone the repository:**
    ```
    git clone https://github.com/wilsonz347/PM_Accelerator_Code.git
    cd PM_Accelerator_Code
    ```
2.  **Create a virtual environment (recommended):**
    ```
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```
3.  **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```


## Usage

1.  **Download the dataset**: Obtain the `Global Weather Repository.csv` file from the [Kaggle link](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data) and place it in the project directory.
2.  **Run the analysis scripts**: Execute the Python scripts for data cleaning, EDA, and model building.

