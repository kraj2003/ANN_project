# Artificial Neural Network for Customer Churn Prediction

A project leveraging Artificial Neural Networks (ANN) and other regression algorithms to predict customer churn using the Kaggle churn dataset. The project includes a deployed Streamlit app for user interaction.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Streamlit App](#streamlit-app)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn prediction is critical for retaining customers in any business. This project develops an Artificial Neural Network (ANN) model alongside multiple regression algorithms, such as XGBoost, Decision Tree Regressor, AdaBoost, Random Forest, and Gradient Boosting, to accurately predict churn. The results are visualized and made accessible through a Streamlit web application.

## Features

- Preprocessed and analyzed the Kaggle churn dataset.
- Built and trained an ANN model using TensorFlow.
- Compared the ANN's performance with multiple regression algorithms:
  - XGBoost
  - Decision Tree Regressor
  - AdaBoost
  - Random Forest
  - Gradient Boosting
- Created a user-friendly Streamlit app for model interaction.
- Deployed the Streamlit app for public use.

## Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - TensorFlow
  - pandas
  - matplotlib
  - scikit-learn
  - TensorBoard
  - Streamlit

## Dataset

- Dataset: [Kaggle Churn Dataset](https://www.kaggle.com/)
- The dataset includes features related to customer demographics, account information, and usage patterns.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/kraj2003/ANN_project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ann-churn-prediction
   ```

3. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # For Windows, use `env\Scripts\activate`
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Train the models and evaluate performance:
   ```bash
   python train_models.py
   ```

2. Launch the Streamlit app:
   ```bash
   streamlit run app.py
   ```

3. Access the app in your browser at `https://kraj2003-ann-project-app-picwvk.streamlit.app/`.

## Project Workflow

1. **Data Preprocessing**:
   - Cleaned the dataset, handled missing values, and performed feature scaling.
   - Encoded categorical variables.

2. **Model Development**:
   - Built an ANN model using TensorFlow.
   - Trained and tested the ANN model and compared it with multiple regression algorithms (XGBoost, Decision Tree Regressor, AdaBoost, Random Forest, Gradient Boosting).

3. **Visualization**:
   - Generated performance metrics and visualized results using matplotlib.

4. **Streamlit App**:
   - Developed an interactive app to allow users to upload data and view predictions.
   - Deployed the app for public access.

## Streamlit App

The Streamlit app allows users to:

- Upload customer data for churn prediction.
- Visualize model predictions and performance metrics.
- Compare the ANN model with other regression algorithms.

Deployed App: [Streamlit Deployment Link]([https://yourappurl.streamlit.app](https://kraj2003-ann-project-app-picwvk.streamlit.app/))

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
