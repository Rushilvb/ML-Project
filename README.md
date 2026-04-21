About the Project

This project is about predicting how much electricity a household will use using machine learning.
Energy consumption changes a lot over time, so the idea was to use past data to predict future usage.

What We Did
Used a dataset with household electricity usage (~2 million records)
Cleaned and prepared the data
Extracted time-related features like hour, day, and month
Added a lag feature (previous value of energy consumption)
Trained two models:
Linear Regression
Random Forest
Features Used
Voltage
Global Intensity
Hour, Day, Month
Previous energy consumption (lag feature)
Models

Linear Regression

Simple model
Used as a baseline

Random Forest

More advanced
Handles non-linear relationships better

Results
Random Forest performed slightly better, which suggests the data is not purely linear.

Key Takeaways
Energy consumption depends a lot on time and past usage
Adding time features improved the model
Lag feature was important for better predictions
