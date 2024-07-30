# Classification on Imbalanced Data: Enhancing Insurance Claims Models

Project Type: Supervised Learning Classification

Project Summary:

Developed a predictive model to accurately identify insurance claims despite significant class imbalance, ensuring effective risk management and resource allocation. The project involved extensive exploratory data analysis to visualize distributions and relationships within the dataset, addressing class imbalance through oversampling, and evaluating model performance using metrics like Precision, Recall, F1 Score, and AUROC. A Random Forest classifier was employed, leveraging its robustness against class imbalance and ability to handle complex interactions. The final model demonstrated high predictive accuracy across both classes, with balanced performance metrics, effectively managing the challenges posed by imbalanced data in the insurance industry.

Key Steps:

1. Data Collection and Preprocessing:

* Gathered and preprocessed historical insurance claims data.
* Transformed time periods into a datetime format suitable for time series analysis.

2. Exploratory Data Analysis:

* Visualized and analyzed the distribution of the target variable and key features.
* Examined distributions of numerical and categorical features to understand their relationships with claim status.

3. Handling Class Imbalance:

* Addressed class imbalance through oversampling the minority class.
* Created balanced datasets to improve model training and performance.

4. Feature Selection:

* Identified the most important variables for predicting insurance claims using Random Forest feature importance.

5. Model Training:

* Built and trained a Random Forest classifier using the balanced dataset.
* Evaluated model performance using appropriate metrics for imbalanced data, such as precision, recall, F1 score, and AUROC.

6. Model Evaluation and Visualization:

* Generated and visualized predictions on both oversampled and original datasets.
* Compared original and predicted claim statuses to assess model accuracy.

Insights Derived:

* High Predictive Accuracy: The model achieved high accuracy (99%) in predicting insurance claims, indicating effective handling of class imbalance.

* Balanced Performance: The model maintained a high balance between precision and recall for both classes, ensuring reliable predictions across different outcomes.
* Effective Risk Assessment: The ability to accurately identify claims allows for improved risk assessment and resource allocation, supporting strategic decision-making in the insurance industry.

Outcome:

Successfully developed a robust predictive model to accurately identify insurance claims despite significant class imbalance. The model achieves 99% overall accuracy with high precision and recall for both claims and non-claims, ensuring effective risk management and resource allocation. This project highlights the importance of handling imbalanced data in classification tasks, demonstrating the practical application of advanced machine learning techniques to real-world business scenarios.
