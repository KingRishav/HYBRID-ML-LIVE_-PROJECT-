# Brazilian E-Commerce Intelligent Warehouse Routing & Simulation Engine

## 1. Project Overview

This project develops a machine learning and simulation framework for intelligent warehouse selection and e-commerce order fulfillment using Brazilian e-commerce data.

The system combines warehouse prediction, shipping-cost estimation, inventory availability checks, geographical distance calculations, and decision-based warehouse selection to support efficient order processing.

## 2. Objectives

- Predict the most suitable warehouse for an order using machine learning.
- Estimate shipping costs using regression models.
- Simulate warehouse inventory and product availability.
- Evaluate geographical distance and delivery-time information.
- Develop an integrated order-processing and warehouse-selection pipeline.

## 3. Technologies Used

- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Kaggle API

## 4. Dataset

The project uses Brazilian e-commerce data obtained through Kaggle. The data includes information about orders, customers, sellers, products, order items, and geographical locations.

Dataset access and licensing requirements should be checked before redistribution.

## 5. Methodology

### Data Preprocessing
- Load and merge multiple e-commerce datasets.
- Clean missing values and process timestamps.
- Integrate customer and seller geographical information.

### Feature Engineering
- Calculate geographical distances using the Haversine formula.
- Extract temporal features from order timestamps.
- Prepare features for warehouse and shipping-cost prediction.

### Machine Learning
- Random Forest Classifier for warehouse prediction.
- Random Forest Regressor for shipping-cost estimation.
- Evaluate model performance using appropriate metrics.

### Inventory and Warehouse Simulation
- Simulate product inventory across warehouses.
- Check product availability before order assignment.
- Rank warehouse options using distance, estimated cost, and delivery-related factors.
- Simulate end-to-end order processing.

## 6. Model Results

The notebook reports the following evaluation results:

| Metric | Reported Result |
|---|---:|
| Warehouse prediction accuracy | 63.15% |
| Baseline accuracy | 12.27% |
| Shipping-cost prediction MAE | 2.94 |
| Shipping-cost prediction R² | 0.77 |

These results are from the notebook's reported evaluation. They should be interpreted in the context of its train-test split, feature selection, and simulation assumptions.

## 7. Project Structure

- `HYBRID(ML+LIVE_)PROJECT 1.ipynb` — Main notebook containing data preparation, machine learning, warehouse selection, and simulation.

## 8. How to Run

1. Open the notebook in Google Colab.
2. Install the required Python libraries.
3. Configure access to the required Kaggle dataset using your own credentials.
4. Load and preprocess the data.
5. Execute the notebook cells in order.
6. Review the model evaluation, visualizations, and warehouse simulation outputs.

Do not commit Kaggle API credentials or other secrets to the repository.

## 9. Future Improvements

- Compare additional machine learning models.
- Optimize warehouse assignment using mathematical optimization.
- Incorporate warehouse capacity and dynamic inventory constraints.
- Evaluate the system on independent test data.
- Improve reproducibility and automated model evaluation.

## 10. Author

Rishav Singh
