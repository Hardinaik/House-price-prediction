# House-price-prediction
💾 Dataset
The dataset used in this project is the Housing Price Dataset sourced from Kaggle.

Source: Kaggle - Housing Price Dataset

Dataset Description: It contains 545 observations and 13 features including:

Numerical: Price, Area, Bedrooms, Bathrooms, Stories, Parking.

Categorical: Mainroad, Guestroom, Basement, Hot water heating, Air conditioning, Prefarea, Furnishing status.

📈 Methodology & Technical Workflow
The project follows a standard Data Science lifecycle:

Data Cleaning: Handled data types and verified that no null values were present.

Outlier Treatment: Used the Interquartile Range (IQR) method to remove extreme price points that were causing high bias in the linear model.

Feature Engineering: Scaled numerical features using StandardScaler to ensure coefficients are comparable.

Transformed categorical text data into numerical format using OneHotEncoder.

Used Ridge and Lasso regularization to navigate the Bias-Variance tradeoff. By tuning the alpha hyperparameter, I controlled the model's complexity to find the point of optimal generalization.
