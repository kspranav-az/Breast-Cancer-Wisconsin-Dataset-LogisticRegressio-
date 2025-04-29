# Logistic Regression - Breast Cancer Classification

This project demonstrates the use of **Logistic Regression** to classify tumors as either *benign* or *malignant* based on the Breast Cancer Wisconsin dataset.

## Steps Performed

1. **Data Loading**: Loaded the Breast Cancer dataset from a CSV file.
2. **Data Preprocessing**:
   - Dropped any columns with missing or invalid values.
   - Encoded the target labels (`M` for Malignant, `B` for Benign) as numerical values.
   - Standardized the features to ensure all features are on the same scale.
3. **Train-Test Split**: Split the dataset into training and testing sets.
4. **Model Training**: Trained a Logistic Regression model on the training data.
5. **Model Evaluation**:
   - Evaluated the model using a confusion matrix, precision, recall, accuracy, and ROC-AUC score.
   - Tuned the decision threshold and visualized the ROC curve.

## Tools Used

- Pandas
- Scikit-learn
- Matplotlib

## Results

The model successfully classified the tumors as malignant or benign, and evaluation metrics like precision, recall, and ROC-AUC were used to assess its performance.

---

