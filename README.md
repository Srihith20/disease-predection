
Disease Prediction

This project predicts diseases based on user-input symptoms using machine learning models. It uses a dataset of symptoms and diseases to train models and provides predictions from multiple classifiers.

Features

- Uses **Random Forest**, **Naive Bayes**, and **SVM** classifiers.
- Shows accuracy and confusion matrices for each model.
- Handles class imbalance with oversampling.
- Provides final predictions by combining results from multiple models.
- Visualizes disease distribution and model performance.

 Technologies Used

- Python (NumPy, Pandas, Scikit-learn, Seaborn, Matplotlib)
- Machine Learning: RandomForestClassifier, GaussianNB, SVC
- Data preprocessing with LabelEncoder and RandomOverSampler

## How to Run

1. Clone the repository**
   ```bash
   git clone https://github.com/Srhith20/disease-prediction.git
   cd disease-prediction

2. Install dependencies

pip install -r requirements.txt


3. Make sure the dataset file is present Ensure improved_disease_dataset.csv is in the project directory.


4. Run the script

python disease_prediction.py


5. Predict a disease Use the predict_disease() function inside the script:

predict_disease("Itching,Skin Rash,Nodal Skin Eruptions")



Example Output

{
  "Random Forest Prediction": "Fungal infection",
  "Naive Bayes Prediction": "Fungal infection",
  "SVM Prediction": "Fungal infection",
  "Final Prediction": modeResult
}

Notes

Ensure all required libraries are installed.

The system currently works with a predefined symptom list; adjust the predict_disease() input accordingly.

Visualization plots will open in separate windows.


License

This project is open-source under the MIT License.
