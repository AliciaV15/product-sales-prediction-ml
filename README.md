# Product-Level Sales Prediction with Neural Networks

This project implements a machine learning system for predicting product-level sales using neural networks and advanced feature engineering. It includes a full pipeline from raw data ingestion to model training, evaluation, and export.

## 🚀 Features

- End-to-end ML pipeline (data loading, preprocessing, training, evaluation)
- Product-level sales prediction
- Advanced feature engineering (temporal + product statistics)
- Neural network optimized for performance
- Detailed evaluation metrics (MAE, RMSE, R², MAPE)
- Product-level performance analysis
- Monthly comparison of predicted vs actual sales
- Full model export (model + scalers + encoders + metadata)

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## ⚙️ Setup

1. Clone the repository:

```bash
git clone https://github.com/TU_USUARIO/product-sales-prediction-ml.git
cd product-sales-prediction-ml
```

2. Install dependencies:

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn
```

3. Add your dataset:

Place files in:

```
/data/
```

Supported formats:
- sales_detail_*.csv
- sales_detail_*.zip

## ▶️ Usage

Run the script:

```bash
python 2productwisesalesprediction.py
```

The pipeline will:

1. Load and merge sales data
2. Extract temporal features (day, month, quarter, etc.)
3. Compute product-level statistics
4. Encode categorical variables
5. Train a neural network model
6. Evaluate performance
7. Generate predictions for future data
8. Compare predicted vs actual results
9. Export trained model and metadata

## 📊 Model Details

### Input Features

- Product, Category, Region, Customer Type (encoded)
- Temporal features (Day, Month, Quarter, Weekend)
- Sales metrics (Unit Price, Quantity, Discount)
- Product-level statistics:
  - Mean, std, sum, count of sales
  - Quantity and pricing statistics

### Model Architecture

- Fully connected neural network
- Dropout regularization
- Batch training optimized for GPU
- Early stopping and learning rate reduction

## 📈 Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score
- MAPE (Mean Absolute Percentage Error)

## 📊 Results

The model provides:

- Product-level predictions
- Monthly performance comparison
- Accuracy per product and per month
- Error analysis (absolute and percentage)

## 👤 Author

Alicia Virreira
