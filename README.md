# Liver Disease Prediction Web App

A Flask-based web application for predicting liver disease using machine learning. The application uses an ensemble model (Gradient Boosting Classifier + AdaBoost Classifier) trained on the Indian Liver Patient Dataset to predict whether a patient has liver disease based on various blood test parameters.

## Features

- **Disease Prediction**: Input patient parameters to get instant prediction results
- **Data Visualization**: View charts and performance metrics
- **Dataset Upload**: Upload CSV files for analysis and preview
- **Model Performance**: Display training and testing accuracy metrics
- **Responsive UI**: Modern, user-friendly interface built with Bootstrap

## Dataset

The model is trained on the **Indian Liver Patient Dataset** which includes the following features:
- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphatase
- Alamine Aminotransferase
- Aspartate Aminotransferase
- Total Proteins
- Albumin
- Albumin and Globulin Ratio

## Model Performance

- **Algorithm**: Ensemble Technique (Gradient Boosting + AdaBoost Classifier)
- **Training Accuracy**: 100%
- **Testing Accuracy**: 92%

## Installation

1. Clone the repository:
```bash
git clone https://github.com/BalajiTV04/liverDiseaseprediction-.git
cd liverDiseaseprediction-
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Requirements

- Python 3.8
- Flask
- Pandas
- NumPy
- Scikit-learn 1.0.2 or 1.1.1
- Matplotlib

## Usage

1. Navigate to the SOURCE CODE directory:
```bash
cd "SOURCE CODE"
```

2. Run the Flask application:
```bash
python app.py
```

3. Open your browser and go to `http://127.0.0.1:5000/`

## Project Structure

```
SOURCE CODE/
├── app.py                 # Main Flask application
├── liver.pkl             # Trained machine learning model
├── indian_liver_patient.csv  # Training dataset
├── templates/            # HTML templates
│   ├── index.html
│   ├── prediction.html
│   ├── chart.html
│   ├── performance.html
│   └── ...
├── static/               # Static assets (CSS, JS, images)
│   ├── assets/
│   └── ...
└── test/                 # Test files
```

## Routes

- `/` - Home page
- `/prediction` - Disease prediction form
- `/predict` - Process prediction request
- `/chart` - Data visualization
- `/performance` - Model performance metrics
- `/upload` - File upload for data analysis
- `/preview` - Preview uploaded CSV data

## Technologies Used

- **Backend**: Python Flask
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Machine Learning**: Scikit-learn
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Indian Liver Patient Dataset (UCI Machine Learning Repository)
- Flask framework
- Bootstrap for UI components
