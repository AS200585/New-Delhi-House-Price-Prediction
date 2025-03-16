# House Price Prediction with Linear Regression

This project predicts house prices in New Delhi using Linear Regression on the MagicBricks dataset from Kaggle, achieving an R-squared score of 0.702.

## Installation
1. Clone the repo: `git clone https://github.com/yourusername/house-price-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage
1. Add `MagicBricks.csv` to the project directory.
2. Run `jupyter notebook house_price_prediction.ipynb` and execute all cells.

## Methodology
- **Data:** MagicBricks dataset (features: `Area`, `BHK`, `Bathroom`, `bathroom_ratio`).
- **Preprocessing:** Applied log transformation to `Price` and `Area`.
- **Model:** Linear Regression with `StandardScaler`.

## Results
- R²: 0.702

## References
- [MagicBricks Dataset]([https://www.kaggle.com/datasets/username/magicbricks](https://www.kaggle.com/datasets/jatin31/house-price-prediction-delhi-magicbricks))
- [Scikit-Learn](https://scikit-learn.org/stable/user_guide.html)
- [NumPy](https://numpy.org/)
- [Pandas]([https://numpy.org/](https://pandas.pydata.org/docs/user_guide/index.html#user-guide)
- [Matplotlib](https://matplotlib.org/stable/users/index.html)
- [Seaborn](https://seaborn.pydata.org/tutorial.html)
