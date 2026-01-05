Project Name - Predictive Analysis & Insights Generation Using Machine Learning
Cross-validation was applied during hyperparameter tuning to ensure the model generalizes well to unseen data. This helped reduce bias from a single train-test split and improved model stability.
Which hyperparameter optimization technique have you used and why?
GridSearchCV was used for hyperparameter optimization because it systematically tests multiple parameter combinations and selects the best configuration based on cross-validation performance.
Have you seen any improvement? Note down the improvement with updates Evaluation metric Score Chart.
Yes, after hyperparameter tuning, the model showed improved F1-score and recall, ensuring better detection of customer sentiment while maintaining stable accuracy.
1. Which Evaluation metrics did you consider for a positive business impact and why?
Precision, Recall, F1-score, and Accuracy were considered.
Recall is important to correctly identify dissatisfied customers, Precision avoids false alerts, and F1-score provides a balanced measure crucial for business decision-making.
2. Which ML model did you choose from the above created models as your final prediction model and why?
Logistic Regression was selected as the final model due to its strong performance, simplicity, interpretability, and ability to scale efficiently for large volumes of customer reviews.
3. Explain the model which you have used and the feature importance using any model explainability tool?
Feature importance was interpreted using Logistic Regression coefficients.
TF-IDF features with higher positive or negative weights indicate words that strongly influence sentiment predictions, making the model transparent and explainable.
8. Future Work (Optional)
1. Save the best performing ml model in a pickle file or joblib file format for deployment process.
The trained Logistic Regression model was saved using joblib format to support easy deployment and reuse in production systems.
2. Again Load the saved model file and try to predict unseen data for a sanity check.
The saved model was reloaded and tested on unseen review data to validate consistency and ensure reliable real-world predictions.
Congrats! Your model is successfully created and ready for deployment on a live server for a real user interaction !!!
Conclusion
This project successfully transformed raw restaurant reviews into actionable insights using EDA, NLP preprocessing, visualization, hypothesis testing, and machine learning.
The final sentiment prediction model is interpretable, scalable, and deployment-ready, enabling businesses to improve customer experience, pricing strategies, and service quality.
Hurrah! You have successfully completed your Machine Learning Capstone Project !!!
