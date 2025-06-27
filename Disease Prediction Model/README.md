### 🧠 Disease Prediction Project

This project focuses on building a model to predict diseases based on symptoms using various machine learning techniques.

---

### 🚀 Project Steps

**Import Libraries**  
Import necessary libraries for data manipulation, analysis, visualization, and model building.

**Load and Prepare Data**  
Load the dataset, encode disease labels, visualize class distribution, and handle class imbalance using Random Over-Sampling.

**Cross-Validation**  
Evaluate multiple machine learning models using Stratified K-Fold Cross-Validation.

**Train Individual Models**  
Train individual models (SVC, Gaussian Naive Bayes, and Random Forest) on the balanced dataset.

**Visualize Performance**  
Generate Confusion Matrices to visualize the performance of each individual model.

**Combine Predictions**  
Combine predictions from the individual models for a more robust final prediction.

**Create Prediction Function**  
Develop a function to predict disease based on input symptoms using the combined model.

---

### 🤖 Models Used

- Support Vector Classifier (SVC)  
- Gaussian Naive Bayes  
- Random Forest Classifier

---

### 🛠️ How to Use

1. Clone the repository.
2. Ensure you have the required libraries installed (see the import section in the notebook).  
   You might need to install `imblearn` using:

   ```bash
   pip install imblearn
   ```

3. Place your `improved_disease_dataset.csv` file in the same directory as the notebook.
4. Run the notebook cells sequentially.
5. Use the `predict_disease` function defined in the notebook with a comma-separated string of symptoms to get a prediction.

---

### 📊 Dataset

The project uses the `improved_disease_dataset.csv` file.

---

### ✅ Results

The output shows predictions from three classifiers:

- **Random Forest** predicted: `Heart Attack`  
- **Naive Bayes** predicted: `Urinary tract Infection`  
- **SVM** predicted: `Impetigo`  

The final **combined prediction** was: `Heart Attack`.

We can further fine-tune this model to make predictions more accurate.

---

### 🔮 Future Work

- Explore other machine learning models and ensemble techniques.
- Incorporate more features or a larger dataset.
- Implement a user interface for easier interaction.
- Perform more extensive hyperparameter tuning for better model performance.
- Validate the model with external datasets.
