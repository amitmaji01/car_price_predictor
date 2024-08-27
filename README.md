# Car Price Prediction Model

## Introduction

This project involves building a Car Price Prediction Model using a raw dataset collected through web scraping. After obtaining the dataset, extensive Exploratory Data Analysis (EDA) was performed using Pandas, NumPy, Seaborn, and Matplotlib. This analysis revealed key insights, such as feature correlations and distribution patterns, which guided the model development process. The XGBoost regression algorithm was chosen for its superior performance, and the model was thoroughly evaluated to ensure accurate predictions. The project culminated in the creation of a web application using HTML, CSS, and Flask, allowing users to easily predict car prices based on input features.

## Project Structure

- `data/`: Contains the dataset used for training and testing the model.
- `notebooks/`: Jupyter notebooks for data preprocessing, EDA, and model training.
- `app/`: Flask application files, including HTML templates and CSS styles.
- `models/`: Serialized model files for deployment.
- `static/`: Static files for CSS, JavaScript, and images.
- `templates/`: HTML templates for the web interface.
- `app.py`: Main Flask application script.
- `requirements.txt`: List of required Python packages.

## Data Preprocessing and EDA

The dataset underwent significant preprocessing, which included:

- Handling missing values and outliers.
- Encoding categorical features.
- Scaling and normalizing numerical data.
- Splitting the data into training and testing sets.

Exploratory Data Analysis (EDA) was conducted to uncover important patterns and relationships in the data using:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For efficient numerical operations.
- **Seaborn**: For visualizing complex relationships between features.
- **Matplotlib**: For creating detailed plots and graphs.

## Model Development

The XGBoost regression algorithm was chosen for its effectiveness in handling large datasets and capturing intricate relationships between features. The following steps were taken:

- Model training with hyperparameter tuning.
- Cross-validation to prevent overfitting and to ensure generalization.
- Evaluation using metrics such as RMSE (Root Mean Squared Error) to assess model accuracy.

The model demonstrated strong predictive performance, making it a reliable tool for predicting car prices.

## Web Application

A user-friendly web application was developed using Flask, with the front-end designed in HTML and CSS. This application allows users to input relevant car features and receive an instant price prediction. The interface is intuitive and responsive, ensuring a seamless user experience.

## Future Scope

The project has potential for further enhancement in the following areas:

- **Model Improvement**: Exploring advanced algorithms like Gradient Boosting Machines (GBMs) or deep learning models to enhance prediction accuracy.
- **Real-time Data**: Integrating real-time data from online car listings to continuously update the model and provide more accurate predictions.
- **User Authentication**: Adding features for users to save their predictions and track price changes over time.
- **Mobile Application**: Developing a mobile-friendly version of the web application for better accessibility on smartphones and tablets.
- **Deployment**: Deploying the application on cloud platforms like AWS or Heroku for broader accessibility.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/amitmaji01/car_price_predictor
