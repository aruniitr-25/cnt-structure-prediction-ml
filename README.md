# AI-Driven Structural Prediction of Carbon Nanotubes (CNTs)
Overview
This project uses Machine Learning to predict the structural equilibrium of Carbon Nanotubes (CNTs), reducing reliance on computationally expensive Density Functional Theory (DFT) simulations.

Overview
To build a predictive model that maps initial CNT configurations (chiral indices and atomic coordinates) to their equilibrium structures using Machine Learning.

 Dataset
- 10,700+ CNT samples
- Features:
  - Chiral indices (n, m)
  - Atomic coordinate data

> Note: Full dataset not uploaded due to size constraints. A sample dataset can be used for demonstration.

Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

Methodology
- Data preprocessing and cleaning (handled complex delimiters)
- Feature engineering on structural descriptors
- Scaling high-dimensional coordinate data
- Model training using Random Forest Regressor
- Model evaluation using Mean Absolute Error (MAE)

Results
- Mean Absolute Error (MAE): **0.007078**
- High prediction accuracy
- Computation time reduced from **hours (DFT) → milliseconds (ML)**

Results Visualization

Actual vs Predicted
![Prediction Plot](results/prediction_vs_actual.png)

Error Distribution
![Error Plot](results/error_distribution.png)

Feature Importance
![Feature Importance](results/feature_importance.png)

Key Highlights
- Applied Machine Learning to a material science problem
- Built an end-to-end ML pipeline
- Handled large-scale, high-dimensional scientific data
- Achieved fast and scalable predictions

Future Improvements
- Implement deep learning models
- Hyperparameter tuning
- Expand dataset for better generalization

Project Structure
