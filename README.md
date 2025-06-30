# House Price Prediction Model

A full-stack machine learning web application to predict house prices in Bangalore, India. The project features a trained ML model, a Flask backend API, and a modern, interactive frontend UI.

## Features
- Predicts house prices based on area, BHK, bath, and location
- Trained ML model (Linear Regression)
- Flask REST API backend
- Responsive, animated frontend (HTML/CSS/JS)
- Easy to deploy and extend

## Project Structure
```
├── client/         # Frontend (HTML, CSS, JS)
├── model/          # Jupyter notebook, model, and columns
├── server/         # Flask backend, util scripts, model artifacts
├── .gitignore
├── README.md
```

## Setup Instructions
1. **Clone the repository:**
   ```sh
   git clone https://github.com/PranavGondePatil/House_Price_Prediction_Model.git
   cd House_Price_Prediction_Model
   ```
2. **Install dependencies:**
   ```sh
   pip install -r server/requirements.txt
   ```
3. **Run the backend server:**
   ```sh
   python server/server.py
   ```
4. **Open the frontend:**
   - Open `client/app.html` in your browser.

## Usage
- Enter the area (sqft), select BHK, bath, and location.
- Click "Estimate Price" to get the predicted price instantly.

## Deployment
- You can deploy the backend on Render, Railway, Heroku, or any cloud VM.
- The frontend can be served as static files (Netlify, Vercel, Render Static Site) or via Flask.
- For production, use a WSGI server like Gunicorn or Waitress.

## License
This project is for educational/demo purposes. Please credit the author if you use or modify it. 