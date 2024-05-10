# Crop Recommendation System API

This project implements a crop recommendation system using a Random Forest classifier with an accuracy of 99.18%. The model is deployed as a RESTful API using Flask and hosted on the Railway cloud platform.

## Features

- Utilizes Random Forest algorithm for accurate crop recommendations.
- Converts the model into a Flask API for easy integration.
- Hosted on the Railway cloud platform for scalability and reliability.

## Requirements

- Python 3.x
- Flask
- scikit-learn
- Railway account (for deployment)

## Installation

1. Clone the repository:

    git clone https://github.com/your_username/crop-recommendation-api.git
    cd crop-recommendation-api

2. Install dependencies:

    pip install -r requirements.txt

## Usage

1. Train the model using your dataset.
2. Start the Flask server:

    python app.py

3. Send POST requests to the API endpoint with JSON data containing the necessary features for crop recommendation.

## API Endpoint

POST /predict

Request Body

{
  "temperature": 30,
  "humidity": 70,
  "rainfall": 100
}

Response

{
  "crop_recommendation": "rice"
}

## Deployment

1. Sign up for a Railway account.
2. Install Railway CLI:

    npm install -g railway

3. Deploy to Railway:

    railway up

## Credits

- Flask
- scikit-learn
- Railway

## License

This project is licensed under the MIT License - see the LICENSE file for details.
