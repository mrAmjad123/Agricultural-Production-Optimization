# Agricultural-Production-Optimization
A machine learning-based crop recommendation system that analyzes soil nutrients and environmental conditions to identify suitable crops. The project leverages exploratory data analysis, K-Means clustering, and Logistic Regression to generate agricultural insights and achieve 97% prediction accuracy across 22 crop categories.

#  Agricultural Production Optimization using Machine Learning

##  Overview

Selecting the right crop based on soil nutrients and environmental conditions is a critical challenge in agriculture. This project analyzes agricultural data and develops a machine learning-based crop recommendation system to identify the most suitable crop for specific soil and climatic conditions.

The solution leverages exploratory data analysis (EDA), clustering techniques, and predictive modeling to generate data-driven agricultural insights.

---

##  Objectives

* Analyze the impact of soil nutrients and environmental factors on crop suitability.
* Identify patterns and relationships among different crop categories.
* Group crops with similar characteristics using clustering techniques.
* Build a predictive model to recommend suitable crops based on input conditions.

---

##  Dataset Information

* **Total Records:** 2,200
* **Crop Categories:** 22
* **Features:** 7 input variables and 1 target variable

### Input Features

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH
* Rainfall

### Target Variable

* Crop Label

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* ipywidgets

---

##  Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Validation
3. Exploratory Data Analysis (EDA)
4. Statistical Analysis
5. Data Visualization
6. K-Means Clustering
7. Logistic Regression Modeling
8. Model Evaluation
9. Real-Time Crop Prediction

---

##  Key Insights

* Identified crop-specific requirements based on soil nutrients and climatic conditions.
* Grouped crops into four clusters using K-Means clustering.
* Determined seasonal crop suitability based on temperature, humidity, and rainfall patterns.
* Discovered significant relationships between nutrient levels and crop recommendations.

---

##  Model Performance

* **Algorithm:** Logistic Regression
* **Train-Test Split:** 80:20
* **Classification Accuracy:** 97%

### Evaluation Metrics

* Precision
* Recall
* F1-Score
* Confusion Matrix

---

##  Visualizations

Include screenshots of:

* Distribution of agricultural conditions
* K-Means clustering results
* Confusion matrix
* Feature comparison charts

Create an `images/` folder and update the paths below:

```markdown
![Distribution Analysis](images/distribution_analysis.png)

![Confusion Matrix](images/confusion_matrix.png)
```

---

##  Real-Time Prediction Example

```python
prediction = model.predict([[90, 40, 40, 20, 80, 7, 200]])

print(prediction)
# Output: ['rice']
```

---

##  Project Structure

```text
optimizing-agricultural-production/
│
├── data/
│   └── data.csv
├── notebooks/
│   └── Optimizing_Agricultural_Production.ipynb
├── reports/
│   └── Optimizing_Agricultural_Production.pdf
├── images/
├── requirements.txt
├── README.md
└── .gitignore
```

---

##  Installation and Usage

Clone the repository:

```bash
git clone https://github.com/your-username/optimizing-agricultural-production.git
```

Navigate to the project directory:

```bash
cd optimizing-agricultural-production
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

##  Future Enhancements

* Integrate real-time weather APIs
* Develop an interactive dashboard using Power BI or Tableau
* Deploy the solution using Streamlit
* Compare multiple machine learning algorithms
* Add feature importance analysis

---

## Author

**Md Amjad Ansari**

* LinkedIn: https://www.linkedin.com/in/mrsamh/
* GitHub: https://github.com/your-github-mrAmjad123
