# 🏡 Optimizing Airbnb Pricing in London (2024)

## 📌 Objective
Develop a data-driven pricing model to help Airbnb hosts in London maximize revenue while staying competitive in the market.

## 📊 Project Overview
This project explores and models Airbnb listing data from London to understand the key factors that influence price and to predict optimal listing prices. 
The focus is on creating a predictive model using machine learning techniques, primarily Random Forest Regression.

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- GeoPy (for calculating distance to city center)
- Tableau (for creating dashboards and presentation)

## 🧪 Key Steps
1. **Data Cleaning**  
   - Removed outliers and filtered for relevant room types and price ranges.
   - Handled missing values and engineered features like `days_since_last_review` and `price_per_review`.

2. **Feature Engineering**  
   - Created spatial features like `distance_to_center`.
   - Added neighborhood-level average prices and room type averages.
   - Built new ratios such as `reviews_to_availability` and `reviews_to_minimum_nights`.

3. **Modeling**  
   - Trained and evaluated a Random Forest model.
   - Used R² and RMSE to assess model performance.
   - Identified top features affecting price.

## 🧠 Insights
- Location (latitude/longitude), room type, and availability are major price drivers.
- Distance to city center and neighborhood pricing trends are useful predictors.
- The Random Forest model achieved the best performance among models tested.

## 📁 Repository Structure
pricingairbnb/
├── Airbnb_London_Pricing_2024.ipynb # Main notebook
├── data/ #  Raw dataset
├── images/ # Visualizations or output charts
└── README.md # Project summary (this file)

## 🔭 What Could Be Done Next
- Integrate seasonality data (e.g., booking trends by month).
- Explore clustering to segment pricing strategies by area or host type.
- Deploy as an interactive tool or web app for host use.

  ## 📬 Contact
For questions or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/nataiz/) or open an issue in this repo.
