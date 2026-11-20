# Laptop Retail Price Regression

Consumer electronics pricing pipeline predicting laptop retail prices from hardware specifications.

## Project Structure

```text
09_Laptop_Price_Regression/
├── laptop_price_regression_data.csv
├── laptop_price_regression_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `laptop_price_regression_data.csv`
- **Task Type:** `Regression`
- **Target Variable:** `price_usd`
- **Numerical Features (4):** `inches, ram_gb, ssd_gb, weight_kg`
- **Categorical Features (4):** `company, typename, cpu_brand, gpu_brand`

## Model Evaluation Summary

- **Selected Best Model:** `Ridge`

| Metric | Score |
| :--- | :--- |
| `r2` | `0.8782` |
| `mae` | `180.94` |
| `rmse` | `241.24` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
