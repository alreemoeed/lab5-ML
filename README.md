# lab5-ML
In this experiment, different values of top_k (3, 4, and 7) were tested to evaluate their effect on model accuracy and feature importance. The results showed that the model achieved the highest accuracy when top_k = 3, while increasing top_k to 4 and 7 slightly reduced the accuracy.

This suggests that using a smaller top_k helps reduce noise by grouping less frequent categories into "Other", which improves model performance. In contrast, increasing top_k introduces more categories that do not significantly contribute to prediction quality.

Additionally, feature importance results showed that numerical features such as price_per_item and Delivery_Distance_km were more influential than Item_Name_reduced, indicating that the item name feature had limited impact on the model.
