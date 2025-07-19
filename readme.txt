Predicting Taxi Gratuities in New York City - Project Summary

Overview The goal of this project was to create multiple linear regression and Random Forest models to predict whether a rider gives a high gratuity (>20%) using 2017 NYC Taxi and Limousine Commission data. The final Random Forest model achieved 86% accuracy and 72% precision in distinguishing generous tippers (>20%) from non-generous tippers (<20%). The PACE framework guided the analysis, identifying trip duration, distance, and fare cost as the most influential features.

Business Understanding According to Salary.com, the average salary for a New York taxi driver is around $45,000, significantly below the city's median rent of $6,500/month. Understanding factors that encourage generous tipping is critical to helping drivers achieve a livable wage. This project supports the NYC Taxi and Limousine Commission and drivers by identifying key drivers of gratuities.

Data Understanding The dataset, sourced from NYC.gov via Google BigQuery, includes approximately 408k unique taxi trips in 2017 with 18 features, such as trip duration, distance, fare amount, vendor, tolls, and payment type. A rush-hour feature was engineered, and redundant columns were dropped and reformatted into proper data types. Limitations include the lack of rider demographic data. See tip_distribution.txt for a text-based summary of generous vs. non-generous tippers.

Modeling and Evaluation A Random Forest model with 100 decision trees, hosted on Google Cloud Vertex AI, determined feature importance, with trip duration, distance, and fare cost as the top three factors. A multiple linear regression model was also explored to assess feature impacts. The Random Forest model performed with:

Accuracy: 86%

Precision: 72% See feature_importance.txt for a text-based summary of feature importance.

Conclusion This model helps taxi drivers predict whether they will receive generous tips, enabling them to prioritize profitable trips. Future work includes running parametric models to predict exact tip amounts and incorporating rider past tipping behavior to enhance predictions. This project demonstrates my skills in Python, Google BigQuery, and machine learning for data-driven decision-making.

Contact

Email: krishornung@gmail.com

GitHub: github.com/Fleabyte26

LinkedIn: linkedin.com/in/kris-hornung-3932072/