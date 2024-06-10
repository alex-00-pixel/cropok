# Crop Recommendation System API

This project implements a crop recommendation system using a Random Forest classifier with an accuracy of 99.18%.

## Features

- Utilizes Random Forest algorithm for accurate crop recommendations.
- Converts the model into a Flask API for easy integration.

## Input Parameters
- Nitrogen
- Phosphorus
- Potassium
- Temperature
- Humidity
- Ph

## Usage

1. Train the model using your dataset.
2. Start the Flask server:

    python app.py

3. Send POST requests to the API endpoint with JSON data containing the necessary features for crop recommendation.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
