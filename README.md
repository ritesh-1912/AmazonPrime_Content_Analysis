# Amazon Prime Content Analysis

![Amazon Prime Video](https://img.shields.io/badge/Amazon_Prime-Video_Analysis-blue?style=for-the-badge&logo=amazonprime) ![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) and applies Machine Learning techniques on the **Amazon Prime Video** dataset. The goal is to uncover trends in content strategy, understand audience preferences, and build predictive models to analyze content performance.

## 📂 Dataset
The project uses two main datasets:
1. **`titles.csv`**: Contains information about movies and TV shows.
   - **Key Features**: `title`, `type` (Movie/TV Show), `genres`, `release_year`, `imdb_score`, `tmdb_popularity`, `production_countries`.
2. **`credits.csv`**: Contains cast and crew information.
   - **Key Features**: `name`, `character`, `role` (Actor/Director).

> **Note:** These files are located in the root directory of the repository.

## 🛠 Technologies Used
- **Language**: Python
- **Libraries**:
  - **Data Manipulation**: `pandas`, `numpy`
  - **Visualization**: `matplotlib`, `seaborn`, `plotly` (if applicable)
  - **Machine Learning**: `scikit-learn`

## 📓 Notebooks Description

### 1. `Amazon_Prime_EDA.ipynb` (Exploratory Data Analysis)
This notebook focuses on visualizing and understanding the data. Key analyses include:
- **Content Distribution**: Breakdown of Movies vs. TV Shows.
- **Genre Analysis**: Most popular genres and genre combinations.
- **Geographical Analysis**: Top production countries.
- **Temporal Trends**: Content release patterns over the years.
- **Rating Analysis**: Distribution of IMDB and TMDB scores.
- **Runtime Analysis**: Duration trends for movies and shows.

### 2. `Amazon_Prime_ML_Project.ipynb` (Machine Learning)
This notebook implements machine learning models to predict content success or recommendation. 
*(Update this section based on your specific model, e.g., Rating Prediction or Recommendation System)*:
- **Data Preprocessing**: Handling missing values, encoding categorical variables (One-Hot/Label Encoding), and feature scaling.
- **Feature Engineering**: Creating new features from genres, cast, or release dates.
- **Model Training**: Implementing models such as:
  - Linear Regression / Logistic Regression
  - Decision Trees / Random Forest
  - Gradient Boosting (XGBoost/LightGBM)
- **Evaluation**: Assessing performance using metrics like MAE, RMSE, or Accuracy.

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/ritesh-1912/AmazonPrime_Content_Analysis.git](https://github.com/ritesh-1912/AmazonPrime_Content_Analysis.git)
