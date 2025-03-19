# Wine Quality EDA (Exploratory Data Analysis) in Python

This repository contains an Exploratory Data Analysis (EDA) on the "Wine Quality" dataset, conducted using Python libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `plotly`. The primary objective of this analysis is to explore patterns, trends, and relationships in the dataset and gain a deeper understanding of the variables before applying any machine learning models.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Key Steps of EDA](#key-steps-of-eda)
- [Visualizations](#visualizations)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [License](#license)

## Project Overview

In this project, we perform a detailed EDA on a dataset containing information about red wines and their quality ratings. This analysis focuses on:
- Understanding the data's distribution, central tendencies, and spread.
- Investigating relationships between variables.
- Detecting missing values and duplicates.
- Identifying outliers and potential skewness in the data.

The final goal is to prepare the data for further machine learning modeling.

## Dataset

The dataset used in this project is the **Wine Quality Dataset** which can be found at [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). The dataset contains physicochemical tests of wines and their quality ratings, with attributes like alcohol content, acidity, sulfur dioxide, and more.

### Dataset Features:
- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality** (Target variable)

## Technologies Used

- **pandas** - For data manipulation and analysis.
- **numpy** - For numerical operations.
- **matplotlib** - For basic visualizations.
- **seaborn** - For advanced visualizations and statistical plots.
- **plotly** - Optional (for interactive visualizations, if needed).
- **warnings** - To suppress warnings during execution.

## Key Steps of EDA

The following steps are performed as part of the EDA process:

1. **Reading the dataset**: The dataset is loaded into a pandas DataFrame.
2. **Data analysis**: Basic statistics are computed, including checking for data types, missing values, and duplicates.
3. **Univariate Analysis**:
   - Count Plot for visualizing the distribution of wine quality.
   - Kernel Density Plot for understanding the distribution and skewness of numerical features.
   - Swarm Plot for detecting outliers in the relationship between quality and alcohol.
4. **Bivariate Analysis**:
   - Pair Plot for exploring relationships between pairs of variables.
   - Violin Plot and Box Plot to understand the relationship between quality and alcohol content.
5. **Multivariate Analysis**:
   - Correlation Matrix to visualize relationships among multiple variables.
   
## Visualizations

Some of the visualizations created in this project include:

- **Count Plot**: Shows the distribution of wine quality ratings.
- **Kernel Density Plot**: Displays the distribution of numerical features and highlights skewness.
- **Swarm Plot**: Visualizes the outliers in the relationship between quality and alcohol.
- **Violin Plot**: Examines the distribution of alcohol content for each quality rating.
- **Box Plot**: Examines the spread and variability of alcohol across different wine quality levels.
- **Correlation Heatmap**: Displays the correlation matrix for understanding how features are related to each other.

## Installation Instructions

To run this project locally, you need to have Python installed. Follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/wine-quality-eda.git
    cd wine-quality-eda
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the EDA script:
    ```bash
    python eda_wine_quality.py
    ```

## Usage

Once you have the dependencies installed, you can run the `eda_wine_quality.py` script to generate the EDA and visualizations. The script will automatically generate plots that help in understanding the dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
