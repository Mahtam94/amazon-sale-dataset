I attempted to build a multi-class classification model to predict order status (Completed, Pending, Cancelled) based on product, price, location, and other transaction features.

After testing multiple models including Random Forest and XGBoost, I found that the dataset lacked strong predictive signals for this task. Accuracy hovered around 30%, and class-wise precision/recall showed model struggle.

Key reasons for poor performance:

Similar patterns across different classes

Limited features (e.g., no customer behavior, no time patterns)

Small dataset size (250 rows)
