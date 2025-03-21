# Forest Fire Prediction System

A machine learning-based web application that predicts the Fire Weather Index (FWI) using environmental parameters.

## Features
- Real-time prediction of forest fire risk
- User-friendly web interface
- Based on environmental parameters like temperature, humidity, wind speed, etc.
- Powered by Ridge Regression model

## Prerequisites
- Python 3.7 or higher
- Git

## Installation Steps

1. Clone the repository
```bash
git clone https://github.com/annnkumar/fire-weather-index-calculator.git
cd fire-weather-index-calculator
```

2. Create a virtual environment
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the application
```bash
python application.py
```

5. Access the application
Open your web browser and go to:
```
http://localhost:5000
```

## Input Parameters

The system requires the following input parameters:
- Temperature (°C)
- Relative Humidity (%)
- Wind Speed (km/h)
- Rain (mm)
- FFMC (Fine Fuel Moisture Code) Index
- DMC (Duff Moisture Code) Index
- ISI (Initial Spread Index)
- Classes
- Region

## Model Information
The prediction is based on a Ridge Regression model trained on historical forest fire data. The model takes into account various environmental factors to predict the Fire Weather Index (FWI).

## Technologies Used
- Python
- Flask
- scikit-learn
- NumPy
- Pandas
- Bootstrap

## Contributing
Feel free to fork this repository and submit pull requests to contribute to this project.

## License
This project is open source and available under the [MIT License](LICENSE).
