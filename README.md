# House Price Prediction

This project is an exploration into regression techniques for predicting house prices, based on the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition on Kaggle.

As I begin my data career journey, this repository serves as a practical application of data cleaning, feature engineering, and model building. I hope it inspires others who are also starting their path in the world of data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Data Visualization](#data-visualization)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/houseprice.git
   cd house-price-prediction
   ```
2. It is recommended to create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: A `requirements.txt` file should be created for this step to work. You can generate one with `pip freeze > requirements.txt`)*

## Usage

The main analysis is contained within the Jupyter Notebook. To run it, start the Jupyter server:
```bash
jupyter notebook
```
Then, open the `analysis.ipynb` (or your notebook's name) file from the Jupyter interface in your browser.

## Data

To obtain the data, you need to go to the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition on Kaggle, download and unzip the data. Then, you can move the data folder to your workspace.

Or you can download the data from the commandline. You need to activate Kaggle API by following [the manual.](https://github.com/Kaggle/kaggle-api/blob/main/docs/README.md#api-credentials) Next, install kaggle to your work environment or base environment.
```bash
pip install kaggle
```
After finished preparing the above step, type in the following command to download dataset from the competition.
```bash
kaggle competitions download -c house-prices-advanced-regression-techniques
```
Then, unzip the folder and move the data folder to your workspace.

To submit the result, locate your result csv file and upload directly to the submission page or type in the command below.
```bash
kaggle competitions submit -c house-prices-advanced-regression-techniques -f submission.csv -m "Message"
```

# Data Visualization
