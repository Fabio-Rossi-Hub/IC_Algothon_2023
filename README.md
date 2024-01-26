# IC_Algothon_2023

Winning submissions of Imperial College Algothon 2023

This repository contains the code and data for the challenges we excelled in. Our team achieved 1st place in the Qube RT challenge and 2nd place in the BlackRock challenge, winning the overall Algothon.

## Challenges

### Challenge-1: Qube RT - Future Price Inference

The goal of this challenge was to estimate future prices by maximizing the Spearman correlation between the estimate and the target.

- **Data:**
  - `x_train.csv`: Training data.
  - `y_train.csv`: Labels of training data.
  - `x_train.csv`: Test data.

- **Notebook:**
  - `0_eda.ipynb`: Exploratory data analysis.
  - `1_pca_lgb_model_attempt.ipynb`: Fit of a LGBoost model after PCA transformation for dimensionality reduction.
  - `2_first_submission_xgb_model.ipynb`: Fit of a XGBoost model that yielded our first submission.
  - `3_last_submission_lgb_model.ipynb`: Fine tuning of a LGBoost model that yielded our final submission.

### Challenge-2: BlackRock - Portfolio Optimization

In this challenge we had to find the portfolio that maximized the Sortino Ratio out of all the stocks included in the SP500.

- **Data:**
  - Returns of all stocks included in the SP500.

- **Notebook:**
  - `blackrock.ipynb`: Python notebook for portfolio optimization.

## Achievements

- Qube RT Challenge: 1st Place
- BlackRock Challenge: 2nd Place
- Overall Hackathon: 1st Place

## Sponsors

- Qube RT
- BlackRock
- G-Research
- Fyde
- Citadel
- Wintermute
