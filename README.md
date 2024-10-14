# Exploratory Data Analysis (EDA) on Iris Dataset

This repository contains an Exploratory Data Analysis (EDA) on the Iris dataset, focusing on the relationships between different flower attributes, including `petal_length`, `petal_width`, and `species`. The goal is to analyze the data distribution and visualize relationships using various univariate and multivariate plots.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
  
## About the Project
The EDA is implemented using Python, leveraging the Seaborn and Matplotlib libraries to generate visualizations. This project aims to help understand the statistical properties of the Iris dataset and explore relationships between features. It includes:
- Histograms for univariate analysis of `petal_length` and `petal_width`.
- Scatter plots for exploring relationships between `petal_length`, `petal_width`, and `species`.

### Visualizations
1. **Univariate Analysis**:
   - Histograms show the distribution of `petal_length` and `petal_width`.
   
2. **Multivariate Analysis**:
   - Scatter plots between `petal_length` and `petal_width`.
   - Scatter plots between `petal_length`, `petal_width`, and `species`.

## Dataset
The analysis uses the famous [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains information about the petal and sepal dimensions of three different species of Iris flowers.

| Feature        | Description                  |
|----------------|------------------------------|
| `petal_length` | Length of the petals         |
| `petal_width`  | Width of the petals          |
| `species`      | Species of the Iris flower   |

## Project Structure
The project includes the following files:
- **`eda_analysis.py`**: This script contains the main code for conducting the Exploratory Data Analysis on the Iris dataset. It imports the necessary libraries, loads the data, performs data cleaning (if needed), and generates visualizations using Seaborn and Matplotlib.

- **`README.md`**: The README file provides an overview of the project, setup instructions, and details on how to contribute.

- **`requirements.txt`**: A list of Python libraries required to run the project. This includes:
  - `pandas`: For data manipulation and analysis.
  - `matplotlib`: For creating static, interactive, and animated visualizations.
  - `seaborn`: For statistical data visualization based on matplotlib.

## Installation
To get started with this project, clone the repository and install the required dependencies.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/eda_analysis.git
   cd eda_analysis
