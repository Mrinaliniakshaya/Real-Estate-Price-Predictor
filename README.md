# Real Estate Price Predictor

## Overview
The **Real Estate Price Predictor** is a machine learning-based web application that predicts property prices based on various features such as location, square footage, number of bedrooms, and more. The project follows a client-server model using **Flask** for the backend and **HTML, CSS, and JavaScript** for the frontend.

## Features
- Predicts real estate prices based on user input
- Uses **Linear Regression** model for price estimation
- Interactive UI for easy data entry
- Backend powered by **Flask**
- Data preprocessing and model training using **Pandas** and **scikit-learn**
- Visualizations using **Matplotlib** for data insights

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Flask
- **Machine Learning:** Pandas, scikit-learn, NumPy
- **Visualization:** Matplotlib

## Installation & Setup
### Prerequisites
Ensure you have **Python 3.x** and **pip** installed on your system.

### Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/Mrinaliniakshaya/Real-Estate-Price-Predictor.git
   cd Real-Estate-Price-Predictor
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask server:
   ```sh
   python app.py
   ```
4. Open a browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Usage
1. Enter property details such as location, area, bedrooms, etc.
2. Click on the **Predict Price** button.
3. View the estimated property price.

## Dataset
The model is trained using a real estate dataset containing features like:
- Location
- Square footage
- Number of bedrooms and bathrooms
- Availability of amenities

## Model & Training
- **Algorithm Used:** Linear Regression
- **Preprocessing:** Handled missing values, encoded categorical variables, and normalized numerical features.
- **Evaluation Metrics:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

## Future Enhancements
- Implement additional ML models (e.g., Random Forest, XGBoost) for better accuracy
- Deploy the model on cloud platforms (AWS/GCP)
- Enhance UI for a better user experience

## Contributing
Feel free to fork the repository, create a branch, and submit a pull request with improvements or bug fixes.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries, reach out to **Sunnam Mrinalini Akshaya** at [GitHub](https://github.com/Mrinaliniakshaya).
