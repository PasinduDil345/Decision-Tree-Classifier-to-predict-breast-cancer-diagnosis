### Breast Cancer Classification with Decision Trees

This project uses a Decision Tree Classifier to predict whether a tumor is malignant or benign based on the Wisconsin Breast Cancer dataset. It covers the complete classification workflow from data preprocessing to model evaluation and comparison of different criteria.

* **Dataset**: The `data.csv` file containing the Wisconsin Breast Cancer dataset, where the target is the `diagnosis` column.
* **Key Techniques & Concepts**:
    * **Model**: `DecisionTreeClassifier`.
    * **Preprocessing**: Label encoding the categorical target variable (`diagnosis`) for model training.
    * **Evaluation**: Calculating model accuracy, generating a confusion matrix, and creating a detailed classification report.
    * **Visualization**: Plotting the class distribution and the full structure of the trained decision tree.
    * **Analysis**: A direct comparison between using `gini` and `entropy` as the splitting criterion.
* **Technologies Used**:
    * Python
    * Pandas
    * Scikit-learn
    * Matplotlib
