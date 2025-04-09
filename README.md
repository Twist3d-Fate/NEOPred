# NEOPred

## Introduction: 
Near-Earth Objects (NEOs) are a group of celestial objects, including asteroids and comets, whose orbits bring them into close proximity to Earth. These objects can potentially pose a risk to our planet due to their potential for collision. Understanding and tracking NEOs is an important part of planetary defense and space science. This project seeks to classify whether various NEOs are dangerous or not.

NASA provides access to data about NEOs through its publicly available API (Application Programming Interface) called the "Near-Earth Object Web Service" (NeoWs). This API allows researchers, developers, and the public to access information about NEOs, including their orbits, physical characteristics, and close approaches to Earth.

## Conclusion: 
The binary classification model trained to predict whether Near-Earth Objects (NEOs) are hazardous or not has yielded promising results. The evaluation metrics reveal the following key insights:

-   **Accuracy**: The model achieved an accuracy score of approximately 87.92%, indicating that it correctly classified a significant portion of NEOs.
    
-   **Precision**: With a precision score of approximately 81.03%, the model demonstrates its ability to identify hazardous NEOs with a relatively low rate of false positives. This is essential for ensuring that resources are appropriately allocated to address potential threats.
    
-   **Recall**: The recall score, measuring around 98.92%, signifies the model's effectiveness in capturing a vast majority of actual hazardous NEOs. It minimizes the risk of failing to detect dangerous objects.
    
-   **Specificity**: The specificity score of approximately 76.87% reflects the model's capability to correctly identify non-hazardous NEOs. This is crucial for preventing unnecessary alarm or resource allocation for harmless objects.
    
-   **F1 Score**: The F1 score, which combines precision and recall, stands at approximately 89.09%. This balanced metric highlights the model's ability to strike a compromise between minimizing false alarms and ensuring high detection rates.

## Extensions: 
- Use more model types (CNN, LGBM/Catboosting/XGB, Random Forests, Stacking Classifiers, etc.)
- Add hyperparameter tuning (Grid Search CV) to improve accuracy and overall performance
