# Disease Prediction Using Machine Learning

## Overview
This project predicts diseases based on symptoms using machine learning classifiers and a graphical user interface (GUI) built with Tkinter. It includes implementations of Decision Tree, Random Forest, and Naive Bayes models for disease prediction.

---

## Features
- User-friendly GUI for symptom input and disease prediction.
- Machine learning models (Decision Tree, Random Forest, Naive Bayes) for accurate predictions.
- Data preprocessing to map diseases and symptoms to numerical representations.
- Real-time results displayed in the GUI.

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: 
  - `tkinter` for GUI
  - `pandas` and `numpy` for data handling
  - `scikit-learn` for machine learning algorithms

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Disease-Prediction-ML.git
   cd Disease-Prediction-ML
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## Dataset
- **Source**: Training and testing datasets (`Training.csv`, `Testing.csv`).
- **Description**: Contains symptoms as features and corresponding disease labels.

---

## How to Use
1. **Run the Application**:
   ```bash
   AI project Disease Predictor.ipynb
   ```
2. **Select Symptoms**: Use the dropdown menus in the GUI to select up to 5 symptoms.
3. **Predict Disease**: Click on one of the prediction buttons (Decision Tree, Random Forest, or Naive Bayes) to view the predicted disease.
4. **Reset Fields**: Use the Reset button to clear inputs and results.

---

## Project Structure
```
Disease-Prediction-ML/
├── Training.csv          # Training dataset
├── Testing.csv           # Testing dataset
├── disease_predictor.py  # Main Python script
├── requirements.txt      # Required Python libraries
├── README.md             # Project documentation
```

---

## Results
The GUI displays the predicted disease based on the input symptoms for each model. 
- Example output:
  - Decision Tree Prediction: Disease A
  - Random Forest Prediction: Disease B
  - Naive Bayes Prediction: Disease A

## Acknowledgments
- Datasets used for training and testing.
- `scikit-learn` library for machine learning algorithms.

---

## Contact
For questions or suggestions, please contact shehab hosny at shehabhosny889@gmail.com.
