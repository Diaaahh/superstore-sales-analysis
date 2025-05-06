# superstore-sales-analysis
This project focuses on analyzing and modeling sales data from a retail superstore to gain business insights and predict future performance. It includes complete data preprocessing, exploratory data analysis (EDA), model training, and evaluation using Python libraries.
## 📈 Dataset

* **Source:** [dataworld Superstore Dataset](https://data.world/yashi-04/sample-superstoreretail-dataset)
* **Description:**

  * **Features:** `Order Date`, `Ship Date`, `Region`, `Category`, `Sub-Category`, `Sales`, `Profit`, `Discount`, `Segment`, `State`
  * **Target Variable:** `Profit`

## 🧱 ML Model

* **Algorithm Used:** Linear Regression
* **Libraries Used:**

  * `pandas`, `numpy` for data manipulation
  * `matplotlib`, `seaborn` for data visualization
  * `scikit-learn` for regression modeling and evaluation

## ⚖️ Evaluation Metrics

* R-squared Score (R²)
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

## 🎉 Results

* Linear regression model achieved a moderate R² score, indicating a basic predictive capability.
* Visualizations like heatmaps, bar plots, and distribution plots helped identify profitable regions and segments.

## 🤝 Conclusion

This project demonstrates how linear regression can be used to forecast profits using sales data. Future improvements could include:

* Trying different models like Random Forest or XGBoost
* Feature engineering to enhance model performance
* Incorporating time series models for monthly sales prediction

## ⚙️ Tech Stack / Tools Used

* Python (Jupyter Notebook)
* pandas, numpy, matplotlib, seaborn, scikit-learn

## ▶️ How to Run the Project

1. Clone the repo

git clone https://github.com/diyanafren/superstore-sales-analysis.git
cd superstore-sales-analysis

2. Install the dependencies


pip install -r requirements.txt


3. Open the notebook


jupyter notebook notebooks/exploration and graphs.ipynb


## 👨‍💼 Author

[Diya Nafren C](https://github.com/diyanafren)
