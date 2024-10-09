# This is a machine learning project, which predicts whether a person has Chronic Kidney Disease or not using the data made available by blood and urine tests. In the later part, influence of each feature on the prediction is calculated using explainable AI models LIME and SHAP.

## LIME:
LIME (Local Interpretable Model-agnostic Explanations) explains individual predictions of any machine learning model by perturbing the input data and observing how these changes affect the predictions. It creates a simpler, interpretable model (like a linear model) around the vicinity of each prediction to approximate how the original model behaves locally. LIME is useful for understanding why a model made a particular prediction, especially for complex models.
### LIME Output
![image](https://github.com/user-attachments/assets/2849a6d3-8192-4360-bd9f-249ec801e23b)


## SHAP:
SHAP (SHapley Additive exPlanations) is based on game theory and provides global interpretability by calculating the contribution of each feature to a model's predictions across the entire dataset. It assigns Shapley values to each feature, which represent the average contribution of that feature to the prediction. SHAP is more mathematically grounded and consistent, offering both local and global explanations of model behavior. However, it can be more computationally intensive than LIME.
### SHAP Output:
![image](https://github.com/user-attachments/assets/af63558d-1526-48ac-9c4b-906e6baa58d0)
