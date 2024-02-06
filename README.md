# Walk Run Classification Dataset

This repository contains a Jupyter notebook focused on the classification task of distinguishing between walking and running activities. The dataset `walkrun.csv` is analyzed through Exploratory Data Analysis (EDA), and various machine learning models are compared for their performance.

## Content

1. **Dataset**
    - The dataset used for this classification task consists of features related to walking and running activities.
  
2. **Jupyter Notebook**
    - The main work is documented in the Jupyter notebook file (`WalkRunClass.ipynb`).
    - The notebook covers the following aspects:
        - Data loading and exploration.
        - Data preprocessing and feature engineering.
        - Exploratory Data Analysis (EDA) to understand the distribution and relationships among variables.
        - Model selection: Comparing several machine learning models.
        - Model performance evaluation using metrics such as accuracy, precision, recall, and F1 score.
        - Hyperparameter tuning to optimize the chosen model.
        - Cross-validation to assess model generalization performance.
    
3. **Models**
    - Various machine learning models have been explored, including but not limited to:
        - Logistic Regression
        - K-Nearest Neighbors
        - Support Vector Classifier
        - Decision Tree
        - Random Forest
        - AdaBoost
        - Gradient Boosting
        - XGBoost
        - CatBoost
        - LightGBM
        - Multi-layer Perceptron (MLP) Classifier

4. **Hyperparameter Tuning**
    - Hyperparameter tuning is performed on selected models to optimize their performance.
    - The tuned hyperparameters are documented in the notebook.

5. **Cross-validation**
    - Cross-validation is utilized to assess the generalization performance of the chosen model.
    - Mean and standard deviation of cross-validated scores are reported.

## Usage

1. **Dependencies**
    - Make sure to install the required dependencies specified in the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

2. **Run the Jupyter Notebook**
    - Open the Jupyter notebook in your preferred environment.
    - Execute the cells in sequence to reproduce the analysis and results.

3. **Extend and Experiment**
    - Feel free to extend the analysis, experiment with additional models, or tweak hyperparameters for further optimization.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.

## Contributors

Aswathi T S and Akhil Sebastian

## License

This project is licensed under the [MIT License](LICENSE).

Happy coding!
