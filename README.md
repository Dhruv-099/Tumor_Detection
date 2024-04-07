# Tumor Detection Project

This project aims to build a machine learning model for detecting tumors based on various features extracted from medical images. The model is trained on a dataset containing features computed from digitized breast mass images.

## Dataset

The dataset used in this project is the Tumor Detection dataset, which can be found at [insert dataset source or link]. It contains several features computed from digitized images of breast mass samples, including mean, standard error, and worst values for various characteristics such as radius, texture, perimeter, area, and more. The target variable indicates whether the tumor is benign (0) or malignant (1).

## Approach

The project follows these main steps:

1. **Data Exploration**: The dataset is loaded into a Pandas DataFrame, and exploratory data analysis is performed to understand the data distribution, identify missing values, and visualize the target variable.

2. **Data Preprocessing**: Unnecessary columns are dropped, and the target variable is mapped to binary values (0 for benign, 1 for malignant). The dataset is then split into training and test sets.

3. **Feature Scaling**: The numerical features are scaled using the StandardScaler from scikit-learn to ensure they are on the same scale and improve model performance.

4. **Model Training**: A Random Forest Classifier is trained on the scaled training data.

5. **Model Evaluation**: The trained model is evaluated on the test set, and the accuracy score is calculated.

## Dependencies

The following Python libraries are required to run this project:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## Usage

1. Clone the repository or download the project files.
2. Install the required dependencies.
3. Run the `Tumor_Detection_model.ipynb` notebook.

The notebook contains the complete code for data exploration, preprocessing, model training, and evaluation.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
