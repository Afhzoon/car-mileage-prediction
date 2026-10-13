# car-mileage-prediction
Built a multiple linear regression model in Python to predict car fuel efficiency (MPG) from horsepower, top speed, volume and weight, using a dataset of 81 cars.

• Explored and validated the data (shape, null values, data types, summary statistics)
• Tested regression assumptions: linearity, normality, multicollinearity, homoscedasticity and residual behavior
• Identified strong multicollinearity (VOL–WT correlation of 0.99, HP–SP of 0.97) that affects coefficient interpretation
• Trained the model with scikit-learn and analyzed residuals
• Saved the trained model with Pickle for reuse

Tools: Python, Pandas, Seaborn, Matplotlib, Scikit-learn
