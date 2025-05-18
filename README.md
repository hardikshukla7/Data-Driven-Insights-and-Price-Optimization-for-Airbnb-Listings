# Data-Driven Insights and Price Optimization for Airbnb Listings

---

## 📊 Overview

This project presents an end-to-end data science pipeline analyzing over 270,000 Airbnb listings across major global cities. The objective is to uncover key pricing drivers and guest satisfaction factors through comprehensive data processing, feature engineering, geospatial analysis, and predictive modeling.

---

## 🔍 Key Features

* **Data Acquisition & Cleaning**: Collected and cleaned extensive Airbnb datasets, addressing missing values and inconsistencies to ensure data integrity.

* **Feature Engineering**: Extracted and transformed relevant features, including geospatial coordinates, room types, and host attributes, to enhance model performance.

* **Exploratory Data Analysis (EDA)**: Conducted in-depth EDA to identify trends, correlations, and anomalies within the data.

* **Predictive Modeling**:

  * Implemented regression models (Linear Regression, Random Forest, PyTorch-based MLPs) to predict listing prices.
  * Developed classification models to assess listing performance categories.
  * Achieved a 6% reduction in price prediction error and improved F1 scores for performance classification.

* **Statistical Analysis**:

  * Applied permutation tests and bootstrapped validation to assess the significance of various features.
  * Utilized SMOTE for class balancing in classification tasks.

* **Insights & Recommendations**: Derived actionable insights for hosts, such as optimal pricing strategies based on location and property features.

---

## 🛠️ Technologies Used

* **Programming Languages**: Python
* **Libraries & Frameworks**:

  * Data Manipulation: Pandas, NumPy
  * Visualization: Matplotlib, Seaborn
  * Machine Learning: Scikit-learn, PyTorch
  * Geospatial Analysis: GeoPandas, Folium
  * Statistical Analysis: SciPy, StatsModels

---


## 📈 Results & Insights

* **Price Prediction**: The Random Forest model outperformed others with the lowest RMSE, indicating high accuracy in price prediction.

* **Feature Importance**: Location, room type, and number of reviews were among the top predictors for listing price.

* **Geospatial Trends**: Listings in city centers commanded higher prices, highlighting the premium of central locations.

* **Host Recommendations**:

  * Enhance listing descriptions and amenities to improve guest satisfaction.
  * Optimize pricing based on property features and location insights.

---

## 📚 References

* [Inside Airbnb](http://insideairbnb.com/get-the-data.html): Source of Airbnb listing data.
* [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html): Machine learning library used for modeling.
* [PyTorch Documentation](https://pytorch.org/docs/stable/index.html): Deep learning framework utilized for MLP implementation.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---
