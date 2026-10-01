# Diamond Price Prediction

Predicts diamond prices from features like carat, cut, color and clarity
using regression models. Part of the AI/ML Technical Team task round.

**Colab notebook:** <your Colab link>

## Dataset
Seaborn's built-in `diamonds` dataset (~54k rows, 10 columns).
Target: `price`.

## Pipeline
- Cleaning: removed duplicates, invalid zero sizes and impossible y/z values
- EDA: distributions, scatter and box plots, correlation heatmap
- Preprocessing: train/test split first, then StandardScaler + OneHotEncoder fitted on train only (no data leakage)
- Models: Linear Regression, Random Forest (and Decision Tree)

## Results
| Model | RMSE | MAE | R2 |
|---|---|---|---|
| Linear Regression | ... | ... | ... |
| Random Forest | ... | ... | ... |

Random Forest performed best because it captures the non-linear
carat-price relationship.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## Run Locally
1. `git clone <your repo link>`
2. `pip install -r requirements.txt`
3. Open the notebook in Jupyter or upload it to Google Colab and run all cells.
