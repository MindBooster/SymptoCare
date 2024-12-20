# SymptoCare: Personalized Medical Recommendation System

## **Overview**
SymptoCare is a cutting-edge Personalized Medical Recommendation System designed to assist users in understanding and managing their health. Leveraging machine learning, the system predicts diseases based on user-input symptoms with high accuracy and provides tailored health recommendations, including descriptions, medications, precautions, workouts, and dietary advice.

---

## **Key Features**
- **Symptom-Based Disease Prediction**:  
  Predicts diseases using state-of-the-art machine learning models, including:  
  - Support Vector Classifier (SVC)  
  - Random Forest Classifier  
  - Gradient Boosting Classifier  
  - K-Nearest Neighbors (KNN)  
  - Multinomial Naive Bayes (MultinomialNB)  

- **Tailored Recommendations**:  
  Provides personalized suggestions for:  
  - Disease descriptions  
  - Precautions to follow  
  - Medications  
  - Suggested workouts  
  - Dietary advice  

- **Interactive User Input**:  
  Users can dynamically input symptoms to receive predictions and recommendations in real-time.

---

## **Technologies Used**
1. **Programming Language**:  
   - Python  

2. **Libraries**:  
   - `pandas` for data manipulation  
   - `sklearn` for machine learning models and evaluation  
   - `matplotlib` for data visualization  
   - `pickle` for saving and loading models  

3. **Data Source**:  
   The dataset is sourced from Kaggle: [Noor Saeed - Medicine Recommendation System Dataset](https://www.kaggle.com/datasets/noorsaeed/medicine-recommendation-system-dataset).

---

## **How It Works**
1. **Data Preprocessing**:  
   - The dataset is preprocessed by encoding the target labels (`prognosis`) and splitting into training and testing sets.

2. **Model Training and Evaluation**:  
   - Five machine learning models are trained and evaluated:  
     - Support Vector Classifier (SVC)  
     - Random Forest Classifier  
     - Gradient Boosting Classifier  
     - K-Nearest Neighbors (KNN)  
     - Multinomial Naive Bayes (MultinomialNB)  
   - Model performance is assessed using accuracy scores and confusion matrices.

3. **Single Prediction**:  
   - Users input symptoms, and the system predicts the disease and provides tailored health recommendations.

---

## **Repository Structure**
```
├── Training.csv                # Main dataset for training and testing
├── symtoms_df.csv              # Dataset with symptoms and descriptions
├── precautions_df.csv          # Dataset with precautions for each disease
├── medications.csv             # Dataset with recommended medications
├── diets.csv                   # Dataset with dietary recommendations
├── workout_df.csv              # Dataset with suggested workouts
├── description.csv             # Dataset with disease descriptions
├── SymptoCare_PMRS.ipynb       # Code for training and evaluating models
├── svc.pkl                     # Saved SVC model
├── README.md                   # Repository description (this file)
```

---

## **Usage**
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/medical-recommendation-system.git
   cd medical-recommendation-system
   ```

2. **Install required libraries**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Train and evaluate models**:  
   Open the notebook and run the code:  
   ```bash
   python SymptoCare_PMRS.ipynb
   ```

---

## **Future Enhancements**
- **Real-Time Data Integration**:  
  Integrate IoT or wearable devices for live symptom monitoring.

- **Mobile/Cloud Deployment**:  
  Develop a mobile app or deploy the system on the cloud for enhanced accessibility.

- **Expanded Dataset**:  
  Include more diseases and symptoms for broader coverage.

- **Multi-Language Support**:  
  Extend the system to support multiple languages for diverse user needs.

---

## **Contributing**
We welcome contributions! Feel free to open an issue or submit a pull request for any improvements or suggestions.

---

## **License**
This project is licensed under the [MIT License](LICENSE).  

