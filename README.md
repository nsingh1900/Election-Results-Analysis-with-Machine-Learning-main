# Election Results Analysis with Machine Learning

This repository contains a comprehensive machine learning project that analyzes the 2019 Portugal legislative election results. The project was completed as part of the Machine Learning course's final assessment and involves the application of various machine learning regression models to predict the final mandates based on real-time election data.

## Dataset

The dataset used in this project has been sourced from the UCI Machine Learning Repository and provides detailed real-time election results from Portugal's 2019 legislative elections. It features over 10,000 observations and 30 attributes, including the number of votes per party, mandates, and territory information. The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/Real-time+Election+Results%3A+Portugal+2019).

## Project Structure

The project is structured as follows:

- **Data Preprocessing**: Cleaning the dataset and preparing it for analysis.
- **Exploratory Data Analysis (EDA)**: Conducting both univariate and multivariate analyses to uncover trends and patterns within the data.
- **Feature Engineering**: Selecting the most significant features that influence the final mandates.
- **Model Development**: Building and training six different regression models.
- **Model Evaluation**: Comparing the models based on Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared metrics.
- **Conclusions**: Drawing conclusions from the model evaluations.

## Models Evaluated

The following machine learning models were evaluated in this project:

- Linear Regression
- Decision Tree Regressor
- K-Nearest Neighbors (KNN)
- Gradient Boosting Regressor
- Support Vector Machine (SVM)
- Random Forest Regressor

## Results

The Decision Tree and Random Forest Regressor models outperformed others, showing near-perfect prediction scores. The SVM model had the least favorable results, indicating potential areas for parameter tuning and model improvement.

## Installation and Usage

Instructions for setting up the project environment and running the Jupyter notebook are provided in the `installation.md` file.

## Contributing

We welcome contributions and suggestions! Please open an issue or pull request to propose changes or additions.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more information.

## Contact

For any queries or discussions related to this project, please contact Zain at zn_chaudhry@hotmail.com.

## Acknowledgements

- Thanks to UCI Machine Learning Repository for providing the dataset.
- Gratitude to the instructors and peers of the Machine Learning course for their guidance and support.

---
