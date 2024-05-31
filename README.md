# RNN-LSTM Based Typhoon Prediction in the Philippines
(Sorry for the late submission sir)

## Overview
This Streamlit app utilizes a bi-directional Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) units to analyze historical typhoon data and forecast the likelihood of typhoons affecting the Philippines in a given month. Users can interact with the app to visualize past typhoon patterns and receive monthly forecasts, potentially aiding in disaster preparedness efforts.

## Features
- **Data Visualization**: View historical typhoon data through interactive visualizations.
- **Model Training**: Train the LSTM model on historical typhoon data to make predictions.
- **Typhoon Forecasting**: Get monthly forecasts for the next few years based on the trained model.
- **Accuracy Metrics**: Evaluate the model's performance using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

## Data Source
The data used in this app is obtained from the [Wikipedia page](https://en.wikipedia.org/wiki/List_of_typhoons_in_the_Philippines_(2000%E2%80%93present)) on typhoons in the Philippines from 2000 to the present.

## Installation
1. Clone this repository to your local machine.
2. Install the required Python packages by running `pip install -r requirements.txt`.
3. Run the Streamlit app using `streamlit run app.py`.

## Usage
- Upon running the app, you can explore the dataset, visualize typhoon patterns, and train the LSTM model.
- Click on the "Start Training" button to train the model, and then use the "Predictions" button to generate forecasts.
- Adjust the number of years to project using the slider on the sidebar.

## Contributors
- Prof. Louie F. Cervantes, M. Eng. (Information Engineering)
- Kyle Billones

---

Feel free to customize it further according to your specific needs!
