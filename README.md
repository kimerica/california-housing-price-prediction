# California Housing Price Prediction

This project uses regression modeling to predict median house values in California based on demographic and geographic features. 
The dataset is derived from the 1990 California census and includes variables such as location, median income, house age, and more.

## Objective

To build and evaluate regression models that predict housing prices in California using demographic and geographic features.  
This project places special focus on estimating housing values in **San Diego**, leveraging insights gained from models trained on the broader California dataset.

## Dataset

- Source: [California Housing Dataset (1990 Census)](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)
- Features include:
  - Longitude, Latitude
  - Housing median age
  - Total rooms, total bedrooms
  - Population, households
  - Median income
  - Median house value (target)

## Methods

- Data preprocessing and EDA
- Feature normalization
- Model selection:
  - Linear Regression
  - Polynomial Regression
  - Cross-validation
- Model evaluation using:
  - RMSE
  - R² score

## How to Run

1. Clone the repository.
2. Open the notebook: `Predicting_Housing_Price_California.ipynb`
3. Run all cells in order.
   - All dependencies are standard Python libraries (`pandas`, `numpy`, `matplotlib`, `sklearn`).

## Results

- Polynomial regression provided better fit than linear models.
- The final model was used to generate predictions specifically for **San Diego**, showcasing how localized price estimates can be made using state-wide models.
  
## Author

Erica Kim  
M.S. in Data Science, University of Colorado Boulder  
GitHub: [kimerica](https://github.com/kimerica)
