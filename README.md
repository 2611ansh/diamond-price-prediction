# Diamond Price Prediction

This is the README file for the "Diamond Price Prediction" project. The project is designed to predict the price of diamonds based on various characteristics. The prediction model is implemented as a Flask web application, allowing users to input diamond features and receive price predictions.

## Project Repository

You can find the project's code and files in the following GitHub repository:

[Diamond Price Prediction GitHub Repository](https://github.com/2611ansh/diamond-price-prediction.git)

## Getting Started

To run the project locally, follow these steps:

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/2611ansh/diamond-price-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd diamond-price-prediction
   ```

3. Install the required Python packages. It's recommended to use a virtual environment:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python application.py
   ```

   The application will be accessible at [http://localhost:5000](http://localhost:5000) in your web browser.

## Usage

Once the application is running, you can access it through your web browser. The following routes are available:

- `/`: The home page of the application, where you can enter diamond characteristics for price prediction.
- `/predict`: The endpoint for predicting diamond prices based on input data.

## Input Diamond Characteristics

To make a prediction, enter the following diamond characteristics on the `/` page:

- Carat
- Depth
- Table
- Dimensions (X, Y, Z)
- Cut
- Color
- Clarity

## Prediction

After entering the required diamond characteristics, click the "Predict" button. The application will use the trained model to predict the price of the diamond, and the result will be displayed on the form page.

## Model and Data Pipelines

The project uses custom data processing pipelines to prepare the input data for prediction. The prediction pipeline generates price predictions based on the input diamond characteristics.

## Acknowledgments

- The dataset used for training and testing the price prediction model.
- Flask for creating the web application.
- Custom data and prediction pipelines for data processing and modeling.
- The open-source community for valuable resources and inspiration.

Feel free to reach out for any questions or suggestions related to this project. Happy predicting!
