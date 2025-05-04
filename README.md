# Breast Cancer Predictor 🩺
A machine learning-based web application designed to predict whether a breast mass is benign or malignant based on several cytology measurements. This app uses a trained machine learning model for prediction and is built using Python, Scikit-learn, and Streamlit.

---

## Features 🛠️
- **Interactive User Interface:**
   Allows users to input cell nuclei measurements via sliders for predicting the likelihood of breast cancer.

- **Model Prediction:**
   Displays whether the cell mass is Benign or Malicious based on the input data.

- **Probability Display:**
   Shows the probability of the mass being benign or malignant in percentage format for clarity.

- **Radar Chart:**
   Visualizes the values of different cell nuclei measurements and their comparisons (Mean, Standard Error, Worst) in a radar chart for easy interpretation.

---

## Installation & Setup ⚙️

### 1. Clone this repository:

`git clone https://github.com/DeepuKr0315/breast-cancer-predictor.git`

### 2. Navigate to the project directory:

`cd breast-cancer-predictor`
### 3. Install the required dependencies:

`pip install -r requirements.txt`

### 4. Start the Streamlit app:

`streamlit run app.py`

Your app will be running locally at `http://localhost:8501`.

## How It Works 🔬

1. **Input Data:** The user provides measurements like radius, texture, perimeter, area, smoothness, and other cell nuclei attributes via sliders.

2. **Prediction:** The model predicts whether the cell mass is Benign (Non-cancerous) or Malicious (Cancerous) based on the input data.

3. **Radar Chart:** A radar chart displays various attributes (Mean, Standard Error, and Worst values) for visual comparison.

4. **Probability Display:** The app displays the probability of the mass being benign and malignant in percentage format, making it easy to interpret.

**Example Output:**

Cell cluster prediction

The cell cluster is: Malicious 🔴

Probability of being benign: 0.00%

Probability of being malicious: 99.99%

## Model Performance 📊
**The machine learning model used for prediction has been evaluated with the following metrics:**

### Accuracy: 98%

### Precision: 99%

### Recall: 97%

### F1-Score: 98%

These metrics indicate that the model performs well in distinguishing between benign and malignant masses.

## Files in this Project 📂

- `app.py`: Main Streamlit app with the prediction interface.

- `model/model.pkl`: Trained machine learning model.

- `model/scaler.pkl`: Scaler used for feature normalization.

- `data.csv`: Dataset used to train the model.

- `assets/style.css`: Custom styles for the web app.

- `requirements.txt`: Required Python libraries for the project.

## Contributing 🤝

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions in the form of bug fixes, feature requests, or improvements are always welcome!

## Disclaimer ⚠️
**This app is intended to assist medical professionals in making diagnoses based on the provided cytology lab data. It should not be used as a substitute for a professional diagnosis by a healthcare provider.**
