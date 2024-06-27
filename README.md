# Analyzing Credit Card User Behavior


## Project Overview
 In the realm of financial business, particularly in the credit card industry, a profound understanding of credit card user behavior is crucial. Analyzing transaction data from 9000 individuals over 6 months provides valuable insights into spending trends, shopping patterns, and credit card usage habits. This analysis aims to identify user segments with similar behaviors, understand their preferences, and enhance tailored service and marketing strategies.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)

## Dataset
The dataset used in this project is sourced from Kaggle:  [CC General](https://www.kaggle.com/code/nataliaole/cc-general-clustering/). It includes transaction details of credit card users, covering various aspects of their spending behaviors.

## Installation
To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/mfarizky/ligres-uber-lyft.git
    cd ligres-uber-lyft
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To use this project, follow these steps:

1. Download the dataset from Kaggle and place it in the `data` directory.
2. Run the data analysis and visualization scripts:
    ```bash
    jupyter notebook
    ```
3. Open the `Linear_Regression.ipynb` notebook and run the cells to see the analysis and visualizations.

## Features
- **Data Cleaning:** Preprocessing and cleaning the dataset for analysis.
- **Exploratory Data Analysis (EDA):** Statistical analysis and visualization of spending trends and patterns.
- **Clustering:** Segmenting users based on similar behaviors using clustering algorithms using K-means and Hierarchical. 
- **Insights and Recommendations:** Drawing conclusions and providing recommendations based on the analysis.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or issues, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Acknowledgements
- The [CC General](https://www.kaggle.com/code/nataliaole/cc-general-clustering) provided by Kaggle.
- Inspiration and guidance from various data science and machine learning communities.
---

