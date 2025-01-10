# Health Insurance Premium Prediction

This project is a machine learning-based application designed to predict health insurance premiums. Users can input personal and health details such as age, income, BMI, smoking habits, and medical history to receive an estimated insurance premium.

## Key Features
- User-friendly interface for inputting details.
- Predicts insurance premiums based on multiple factors.
- Uses distinct models for different age groups:
  - **Linear Regression** for users aged 25 years or younger.
  - **XGBRegressor** for users older than 25 years.

## How It Works
1. Users input their personal and health details into the application.
2. The application selects the appropriate model based on the user's age:
   - **Linear Regression**: Simpler and effective for younger users.
   - **XGBRegressor**: Advanced model for better accuracy in older age groups.
3. The model processes the input and provides an insurance premium estimate.

## Technologies Used
- **Machine Learning Models**: Linear Regression, XGBRegressor.
- **Programming Language**: Python.
- **Libraries**: scikit-learn, XGBoost, pandas, numpy, etc.


