# Lab4-Machine-Learning-Programming-PROG8245

#  Data Tidying and Cleaning in Python

This repository contains a Jupyter Notebook demonstrating various data tidying and cleaning techniques using Python. The notebook serves as a practical guide to preparing data for analysis, visualization, and machine learning.

---

##  Table of Contents

- [About The Project](#-about-the-project)  
- [Datasets](#-datasets)  
- [Methodology](#-methodology)  
  - [Data Tidying](#data-tidying)  
  - [Data Cleaning](#data-cleaning)  
  - [Outlier Detection](#outlier-detection)  
- [Getting Started](#-getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Usage](#usage)  
- [Libraries Used](#-libraries-used)

---

##  About The Project

This project showcases fundamental data engineering processes of **data cleaning** and **tidying**. The primary goal is to transform raw, messy data into a clean, organized, and readable format, which is crucial for any subsequent data-driven tasks. The notebook provides step-by-step implementations of common data wrangling operations on various real-world datasets.

---

##  Datasets

The notebook utilizes the following datasets to illustrate different cleaning and tidying challenges:

- **PEW Research Dataset (`pew-raw.csv`)**  
  Contains data on income ranges based on religion.

- **Billboard Dataset (`billboard.csv`)**  
  Includes information about top hit songs on the Billboard charts.

- **Cars Dataset (`cars.csv`)**  
  Provides specifications of different car models.

- **Diabetes Dataset**  
  Imported from `sklearn.datasets`. A classic dataset for regression tasks, used here for outlier detection.

---

##  Methodology

The notebook is divided into three main sections, each focusing on a different aspect of data preparation.

### Data Tidying

This section focuses on structuring the data to be more organized and readable based on the principles of **tidy data**:

- Each variable forms a column.  
- Each observation forms a row.  
- Each type of observational unit forms a table.  

**Primary function used:** `pandas.melt` to transform wide data formats into long formats.

---

### Data Cleaning

Addresses common data quality issues, such as:

- **Missing Data:**  
  - Identifying and handling missing values.  
  - Techniques: dropping rows/columns, imputing with mean/median, or using `SimpleImputer` from scikit-learn.

- **Unnecessary Data:**  
  - Removing irrelevant columns.  
  - Removing duplicate entries.

- **Inconsistent Data:**  
  - Standardizing and formatting values.  
  - Example: extracting numerical values from strings.

---

### Outlier Detection

This section explores methods to identify and handle data points that deviate significantly from the rest:

- **Visualization Techniques:**  
  - Box plots  
  - Scatter plots

- **Statistical Methods:**  
  - **Z-Score**: Identifies outliers based on their deviation from the mean.  
  - **Inter-Quartile Range (IQR)**: Uses quartile boundaries to detect outliers.

---

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Python 3.x
- `pip` (Python package installer)
- `git` (for cloning the repository)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Yogesh-333/Lab4-Machine-Learning-Programming-PROG8245.git](https://github.com/Yogesh-333/Lab4-Machine-Learning-Programming-PROG8245.git)
    cd YourRepositoryName
    ```

2.  **Create and activate a virtual environment** (recommended):

    - **macOS/Linux:**
      ```bash
      python3 -m venv env
      source env/bin/activate
      ```
    - **Windows:**
      ```bash
      python -m venv env
      .\env\Scripts\activate
      ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  From the Jupyter interface in your browser, open `week5Lab_Students.ipynb` to see the completed exercises with detailed explanations.

---
