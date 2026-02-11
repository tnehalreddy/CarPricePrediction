# Car Price Prediction

A machine learning-based project to predict car prices based on various features such as brand, year of manufacture, mileage, fuel type, and transmission. This project helps users estimate a fair price for a car using data-driven insights.

## Features

* Predicts car prices based on multiple input features.
* Uses regression-based machine learning models.
* Clean and simple web interface.
* Helps users make informed buying and selling decisions.

## Technologies Used

* Python
* Pandas and NumPy for data manipulation
* Scikit-learn for building regression models
* Flask for the web framework
* HTML and CSS for front-end

## How I Developed This Project

1. **Dataset Collection**:

   * I collected a publicly available dataset containing car details and prices.
   * The dataset includes features such as brand, model, year, mileage, fuel type, and transmission.

2. **Data Preprocessing**:

   * Cleaned missing values and removed duplicates.
   * Encoded categorical variables.
   * Performed feature scaling where required.

3. **Model Development**:

   * Built regression models such as Linear Regression and Random Forest Regressor.
   * Trained the model to predict car prices based on input features.
   * Evaluated model performance using metrics like R² score and Mean Absolute Error.

4. **Web Application Development**:

   * Created a Flask-based web interface.
   * Users enter car details and receive predicted price.
   * HTML and CSS used to design a user-friendly interface.

5. **Testing and Optimization**:

   * Tested the application with multiple inputs.
   * Tuned model hyperparameters to improve accuracy.

6. **Deployment**:

   * The application can be run locally using Flask.

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/tnehalreddy/CarPricePrediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CarPricePrediction
   ```

3. Install dependencies:

   ```bash
   pip install flask pandas scikit-learn
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Open browser and visit:

   ```plaintext
   http://127.0.0.1:5000/
   ```

## Dataset

The dataset contains car features and their corresponding prices. It is used to train and test the regression models.

## Project Structure

* `app.py`: Main Flask application file
* `templates/`: HTML templates
* `static/`: CSS and JS files
* `mlmodel/`: Trained model files
* `data/`: Dataset

## Contributions

Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the **MIT License**. You can view the license [here](https://github.com/tnehalreddy/CarPricePrediction/blob/main/LICENSE)

## Contact

If you have any questions or feedback, feel free to reach out: tnehalreddy

* **Email**: [tnehalreddy@gmail.com](mailto:tnehalreddy@gmail.com)
* **GitHub**: [tnehalreddy](https://github.com/tnehalreddy)

