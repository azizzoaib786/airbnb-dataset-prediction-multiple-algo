# 🏡 Airbnb Rental Income Revenue Prediction

This project focuses on building predictive models to estimate the success of Airbnb property listings, leveraging Logistic Regression and Random Forest algorithms. The aim is to determine whether a given property listing will be successful based on various features extracted and engineered from the Airbnb dataset.

## 🎯 Objective

To accurately predict the success likelihood of Airbnb property listings by employing machine learning techniques and insightful data analysis.

## 🚩 Dataset

The dataset utilized for this project is extensive and includes numerous listings with detailed features. It can be downloaded from:

- [Inside Airbnb Dataset](https://insideairbnb.com/get-the-data/)

*(Alternatively, a direct link to the processed dataset will soon be provided.)*

## 🔍 Project Workflow

The project follows these structured steps:

1. **Exploratory Data Analysis (EDA)**
   - Data cleaning and initial analysis to understand distributions, trends, and relationships between variables.

2. **Data Visualization**
   - Heatmaps to visualize correlations between various features.

3. **Manual Feature Selection**
   - Utilizing domain knowledge to select relevant and impactful features.

4. **Handling Missing Values**
   - General imputation methods to handle incomplete data.

5. **Advanced Imputation (KNN)**
   - K-Nearest Neighbors algorithm used specifically for imputing critical missing values in `review_scores_rating` and `reviews_per_month`.

6. **Data Preparation for Modeling**
   - Encoding categorical features and scaling numeric features to enhance model performance.

7. **Feature Engineering**
   - Creating additional meaningful features derived from the dataset to boost predictive accuracy.

8. **Logistic Regression Model**
   - Application of Logistic Regression to classify listings as successful or unsuccessful.

9. **Random Forest Model**
   - Employing a Random Forest classifier for improved accuracy and handling complex feature interactions.

10. **Model Comparison**
    - Evaluating and comparing both models to determine the best performing predictive approach.

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Usage

### Clone the repository:
```bash
git clone https://github.com/azizzoaib786/airbnb-dataset-prediction-multiple-algo.git
cd airbnb-dataset-prediction-multiple-algo
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Run the analysis:
```bash
jupyter notebook
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/azizzoaib786/airbnb-dataset-prediction-multiple-algo/issues).

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 📫 Contact

For questions or suggestions, please reach out via:

- Email: azizzoaib786@gmail.com
