# 🏠 House Price Prediction using Linear Regression

This project demonstrates a simple **Linear Regression model** to predict house prices based on features such as size, number of bedrooms, location index, and age of the property.

## 📁 Dataset

The dataset is synthetically generated using NumPy to simulate real-world house data:

- `SIZE`: Square footage of the house  
- `BEDROOMS`: Number of bedrooms  
- `LOCATIONS`: Encoded location index (1-10)  
- `Age`: Age of the house (in years)  
- `Price`: Target variable - predicted house price

The dataset is saved as `house_price_data.csv` with 1000 records.

## 🔍 Exploratory Data Analysis

Performed basic EDA using:
- `pandas` for summary statistics and checking missing values
- `matplotlib` & `seaborn` for visualizing distributions and correlations

### Visuals Included:
- Histograms for all features  
- Correlation heatmap for understanding feature relationships

## 📊 Model Building

Used **Linear Regression** from `scikit-learn`:

- Features: `SIZE`, `BEDROOMS`, `LOCATIONS`, `Age`
- Target: `Price`
- Train-test split: 80-20
- Performance Metrics:
  - **Mean Absolute Error (MAE)**
  - **R² Score**

### 💡 Results:

- **MAE**: ~9490.74  
- **R² Score**: 1.00 (Indicates a perfect fit on the test set)

## 📈 Model Evaluation

Visualized actual vs predicted prices using a scatter plot to evaluate model performance.

---

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
