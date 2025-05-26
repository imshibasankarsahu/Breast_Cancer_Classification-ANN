# Breast Cancer Classification Project Summary

## Objective
Develop a neural network to classify breast tumors as malignant or benign using the Wisconsin Breast Cancer Dataset.

## Dataset
- **Source**: Scikit-learn's Wisconsin Breast Cancer Dataset
- **Instances**: 569
- **Features**: 30 numeric attributes (e.g., mean radius, texture, perimeter)
- **Classes**: Malignant (212), Benign (357)
- **No Missing Values**

## Methodology
1. **Data Preprocessing**:
   - Loaded data and converted to a Pandas DataFrame.
   - Standardized features using `StandardScaler`.
   - Split data into training and test sets.

2. **Neural Network**:
   - Built a simple ANN to predict tumor class.
   - Outputs probabilities for malignant (0) and benign (1).

3. **Evaluation**:
   - Test accuracy: **96.49%**, loss: 0.0991.
   - Predictions converted to labels using `np.argmax`.

4. **Predictive System**:
   - Sample input (30 features) classified as **benign** with 86.59% probability.

## Results
- The model demonstrates high accuracy in classifying breast tumors.
- The predictive system successfully processes new data points for classification.

## Tools Used
- Python, NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras