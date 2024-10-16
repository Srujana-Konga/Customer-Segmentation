# Customer Segmentation

## Overview
This project aims to segment customers based on their purchasing behavior and demographics to enhance marketing strategies and improve customer satisfaction. Using a dataset containing various customer attributes, a Decision Tree classifier was implemented to predict customer responses to marketing campaigns based on the features available in the dataset.

## Libraries Used
- **pandas**: For data manipulation and preprocessing.
- **scikit-learn**: For implementing the Decision Tree classifier and evaluating the model.
- **matplotlib**: For data visualization and plotting the decision tree.

## Methodology
1. **Data Preprocessing**: 
   - Handled missing values.
   - Encoded categorical variables.
   - Normalized numerical features.

2. **Feature Selection**: 
   - Relevant features were selected based on their significance and correlation with the target variable (`Response`).

3. **Model Training**: 
   - A Decision Tree classifier was trained using the processed dataset.
   - The model was evaluated using a train-test split approach.

4. **Model Evaluation**: 
   - The model's performance was assessed using accuracy, precision, recall, and F1-score metrics.

## Insights
- The model achieved a high accuracy of **0.84**, indicating that it effectively predicts customer responses.
- The precision and recall for Class 0 (non-responders) were notably high, while the precision for Class 1 (responders) was lower, suggesting room for improvement in targeting campaign responses.

## Conclusion
The Decision Tree model successfully identified customer segments, providing actionable insights into customer behavior and preferences. The high accuracy suggests that the model can effectively aid in targeting marketing campaigns. However, the lower precision for responders indicates a need for further refinement, possibly by exploring additional features or employing more complex models. Future work may also include experimenting with other machine learning algorithms, such as Random Forests or Gradient Boosting, to improve prediction performance.
