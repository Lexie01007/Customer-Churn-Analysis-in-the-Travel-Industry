# Customer Churn Analysis in the Travel Industry

This project explores customer churn in the travel industry using a combination of Python data analysis and machine learning techniques. The repository contains a Jupyter notebook and several datasets designed to help you understand, visualize, and predict why customers may stop using travel services.

## Project Structure

- [`customer-churn-in-travel-industry.ipynb`](customer-churn-in-travel-industry.ipynb): Main Jupyter notebook containing the analysis, visualizations, and modeling steps.
- [`flights.csv.zip`](flights.csv.zip): Compressed dataset with flight-related data.
- [`hotels.csv.zip`](hotels.csv.zip): Compressed dataset with hotel-related data.
- [`users.csv`](users.csv): User demographic and profile data.

## Overview

The notebook guides you through the following steps:
1. **Data Loading and Preparation:** 
   - Unzips and loads flight and hotel datasets.
   - Loads and merges user demographic information.
2. **Exploratory Data Analysis (EDA):**
   - Summarizes customer demographics, booking patterns, and churn rates.
   - Visualizes trends and relationships in the data.
3. **Feature Engineering:**
   - Constructs meaningful features from raw data for better modeling.
4. **Modeling and Prediction:**
   - Applies machine learning algorithms to predict customer churn.
   - Evaluates model performance and interprets results.
5. **Insights and Recommendations:**
   - Discusses actionable insights for reducing churn in the travel industry.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Lexie01007/Data-Analysis-Projects.git
   cd Data-Analysis-Projects
   ```

2. **Install dependencies**
   - Recommended: Use a Python 3.7+ environment.
   - Typical packages: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `seaborn`, `jupyter`

   ```bash
   pip install pandas numpy matplotlib scikit-learn seaborn jupyter
   ```

3. **Start Jupyter Notebook and run the analysis**
   ```bash
   jupyter notebook customer-churn-in-travel-industry.ipynb
   ```

## Data Sources

- **flights.csv.zip**: Contains flight bookings, cancellations, and related info.
- **hotels.csv.zip**: Contains hotel bookings, stays, and related info.
- **users.csv**: Contains user demographics such as age, gender, company, etc.

## Usage

- Modify or extend the notebook to explore additional hypotheses.
- Use the provided datasets to experiment with feature engineering and new models.
- Apply the insights to your own travel industry data or use as a template for similar churn analysis projects.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

Created by [Lexie01007](https://github.com/Lexie01007).

---

**Feel free to open issues or pull requests if you have questions or suggestions!**
