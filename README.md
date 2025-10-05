# Medicine Recommendation System

## Introduction
This project, developed by **Pravin Gupta (Reg No: 229310184, Section 7A)** for the course *Recommender Systems | AI 4103*, focuses on building an intelligent Medicine Recommendation System. With the growing availability of health data and advancements in machine learning, the project demonstrates how AI can assist individuals in identifying potential illnesses based on their reported symptoms.

## Problem Statement
Many individuals experience symptoms but may not have immediate access to medical professionals for an initial consultation. This leads to uncertainty about possible health conditions and next steps.  
The goal of this project is to design a system that:
- Accepts **user-provided symptoms** as input.
- Predicts the most probable disease.
- Provides **relevant recommendations**, including:
  - Disease description
  - Associated symptoms
  - Recommended medications
  - Necessary precautions
  - Dietary suggestions
  - Workout recommendations

This system aims to offer users **preliminary guidance and awareness** before consulting a healthcare professional.

## Project Overview
The system uses a **machine learning model trained on symptom–disease datasets**.  
Given a list of symptoms, the system predicts the corresponding disease and presents a comprehensive report.

Key outputs include:
- **Disease Description:** Brief explanation of the illness.  
- **Associated Symptoms:** Commonly observed related symptoms.  
- **Recommended Medications:** Suggested medications or treatments.  
- **Precautions:** Preventive or cautionary measures.  
- **Dietary Recommendations:** Food and nutrition advice.  
- **Workout Recommendations:** Suitable exercises or physical activities.  

## Dataset
The dataset consists of:
- Symptom–disease mappings  
- Detailed descriptions of diseases  
- Recommended medications, precautions, diet, and workout information  

The data was preprocessed to ensure consistency and suitability for training.

## Methodology
1. **Data Preprocessing**  
   - Handling missing values, normalization, and transformation.  
2. **Model Training**  
   - Machine learning algorithms (e.g., Decision Trees, Random Forest, etc.) were trained on the dataset.  
   - Cross-validation and evaluation were performed to select the best model.  
3. **Prediction & Recommendation**  
   - Input: Symptoms from user  
   - Output: Predicted disease + Recommendations (medication, diet, workout, precautions)  

## Results
- The system successfully predicts probable diseases based on given symptoms.  
- Provides a structured recommendation report, enhancing user awareness and decision-making.  
- Acts as a **preliminary guidance tool**, not a replacement for professional consultation.  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medicine-recommendation-system.git
   cd medicine-recommendation-system
   ```
2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:
```
jupyter notebook medicine_recommendation_system.ipynb
```

4. Input symptoms in the interface/code cell and receive predictions with recommendations.

## Future Improvements

- Expand the dataset with more diseases and symptoms.

- Integrate with a web or mobile app for better accessibility.

- Use deep learning models or transformer-based approaches for improved accuracy.

- Incorporate real-time data (e.g., wearable devices, health trackers).

## Conclusion

The Medicine Recommendation System showcases the potential of recommender systems in healthcare.
By leveraging symptom–disease mapping and machine learning, it provides users with preliminary insights and guidance. While it cannot replace medical professionals, it serves as a supportive tool for health awareness and decision-making.

Author: Pravin Gupta
Course: Recommender Systems | AI 4103
