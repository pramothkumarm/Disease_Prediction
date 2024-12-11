# Disease Prediction Using Machine Learning

## Overview
Welcome to the Disease Prediction project! This project leverages machine learning techniques to predict the likelihood of various diseases based on patient data. The primary goal is to provide early warnings and enable preventive measures, improving patient outcomes and optimizing healthcare resources.

---

## Features
- **Data-Driven Insights:** Predicts diseases based on historical data.
- **Multiple Models:** Supports Naïve Bayes, Random Forest, and SVM for disease prediction.
- **User-Friendly Interface:** A simple and intuitive web application for inputting patient data.
- **Extensible Design:** Easy to integrate additional diseases or models.

---

## Prerequisites
### Hardware
- A computer capable of running Python applications.

### Software
- Python (3.7 or above)
- Required libraries (specified in `requirements.txt`):
  - `Flask`
  - `pandas`
  - `numpy`
  - `scikit-learn`

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/disease-prediction.git
   cd disease-prediction
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```bash
   python app.py
   ```
4. Access the application in your browser at `http://127.0.0.1:5000`.

---

## Dataset
- The project uses `Training.csv` and `Testing.csv` datasets containing patient symptoms and corresponding disease labels.
- The `dataset.csv` file combines training and testing data for preprocessing and exploratory analysis.

---

## Model Details
- **Naïve Bayes Classifier:** A probabilistic model for quick and efficient predictions.
- **Random Forest:** Ensemble learning for robust and accurate predictions.
- **Support Vector Machine (SVM):** A model for high-precision predictions, especially for complex datasets.
- Pretrained models (`final_nb_model.pkl`, `final_rf_model.pkl`, `final_svm_model.pkl`) are included in the repository.

---

## Usage
1. Launch the application as described in the installation steps.
2. Enter patient symptoms in the web interface.
3. View the predicted disease based on the input symptoms.

---

## Directory Structure
```
.
├── app.py                  # Flask application entry point
├── Training.csv            # Training dataset
├── Testing.csv             # Testing dataset
├── dataset.csv             # Combined dataset
├── encoder_classes.npy     # Encoded classes for categorical data
├── final_nb_model.pkl      # Pretrained Naïve Bayes model
├── final_rf_model.pkl      # Pretrained Random Forest model
├── final_svm_model.pkl     # Pretrained SVM model
├── requirements.txt        # Dependencies
├── templates/              # HTML templates for the web interface
├── static/                 # Static files (CSS, JS, images)
└── README.md               # Project documentation
```

---

## Future Enhancements
- Integration with healthcare APIs for real-time data.
- Incorporation of additional diseases and symptoms.
- Enhanced UI for a better user experience.
- Deployment on cloud platforms for scalability.

---

## Contributors
- [PRAMOTH KUMAR ](https://github.com/pramothkumarm)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.


[Fracture Detection - Google Chrome 27-05-2024 15_30_36](https://github.com/pramothkumarm/Disease_Prediction/assets/93421622/cd68f55f-3137-4cc1-85ff-ccf914c446eb)
![Fracture Detection - Google Chrome 27-05-2024 15_29_59](https://github.com/pramothkumarm/Disease_Prediction/assets/93421622/ddab805a-ec4b-43b4-b014-f51a14c1f3bf)
