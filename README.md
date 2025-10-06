# Car Purchase Prediction Model🚘

This project implements a **Gradient Boosting Classifier** to predict car purchase likelihood using a Japanese dataset and applies the model to estimate potential customers in an Indian dataset. The Jupyter Notebook (`Car_Purchase_Prediction.ipynb`) includes data preprocessing, feature engineering, model training, evaluation, business insights, and a Tableau visualization plan.

## Dataset
- **Japanese Dataset**: `JPN Data.xlsx - CN_Mobiles.csv`
- **Indian Dataset**: `IN_Data.xlsx - IN_Mobiles.csv`

## Installation
```bash
pip install pandas sklearn seaborn matplotlib
```
- Requires Python 3.8+ and Jupyter Notebook.
- Place dataset files in the project directory.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/itsbk13/Car_Purchase_Prediction.git
   cd Car_Purchase_Prediction
   ```
2. Run `Car_Purchase_Prediction.ipynb` in Jupyter to execute the full workflow.
3. Use exported `japan_data.csv` and `india_data.csv` for Tableau visualizations.

## Project Structure
```
Car_Purchase_Prediction/
├── JPN Data.xlsx - CN_Mobiles.csv    # Japanese dataset
├── IN_Data.xlsx - IN_Mobiles.csv     # Indian dataset
├── Car_Purchase_Prediction.ipynb     # Main notebook
├── japan_data.csv                   # Exported Japanese data
├── india_data.csv                   # Exported Indian data
├── output.csv                       # Indian predictions
└── README.md                        # This file
```

## Key Features
- **Model**: Gradient Boosting Classifier (70.26% accuracy).
- **Key Predictors**: Car age (>360 days) and income.
- **Business Insight**: Target high-income individuals with older cars.
- **Tableau**: Visualize age, income, and purchase trends.

## License
- This project is licensed under the [MIT License](LICENSE).
- Attribution: This project was built as a capstone during an internship program with [Internshala](https://trainings.internshala.com/data-science-beginner-course).
