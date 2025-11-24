# VITyarthi-project
...
# Jaundice Prediction Program

## Overview
This Python program predicts whether a person has jaundice based on key medical features entered by the user. It uses a machine learning approach with a Random Forest classifier trained on a small synthetic dataset of jaundice symptoms and signs.

## Features
- Accepts user inputs for relevant medical parameters including bilirubin level, yellowing of eyes and skin, age, dark urine, fatigue, and abdominal pain.
- Uses a trained Random Forest model to predict the presence of jaundice.
- Provides a risk percentage associated with the prediction.
- Displays common jaundice symptoms detected in the input.
- Advises consulting a medical professional for confirmation.

## Requirements
- Python 3.x  
- `scikit-learn` library  
- `numpy` and `pandas` libraries (for internal data handling)  

Install dependencies with:pip install scikit-learn numpy pandas

Specify your license here if any (e.g., MIT License).

## How to Run
1. Download the program file (e.g., `projectman.py`).  
2. Open a terminal or command prompt.  
3. Navigate to the directory containing the program.  
4. Run the program using:
5. Follow the on-screen prompts to enter patient details as numeric inputs (0 or 1 for binary symptoms, and age as an integer).

## Input Description
- **bilirubin level?** (0=no, 1=yes)  
- **Ocular discoloration?** (0=no, 1=yes)  
- **Skin yellowing?** (0=no, 1=yes)  
- **Age:** Patient's age in years (integer)  
- **Urine color?** (0=no, 1=yes)  
- **Fatigue or weakness?** (0=no, 1=yes)  
- **Abdominal pain?** (0=no, 1=yes)  

## Output
- Prediction result indicating if jaundice is detected or not.  
- Risk percentage score from 0% to 100%.  
- List of common jaundice symptoms found.  
- Advice to consult a doctor for confirmation.

## How It Works
The program contains a small synthetic dataset representing jaundice and non-jaundice patients with binary symptom indicators and age.  
It trains a Random Forest classifier on this dataset.  
When the user enters new patient data, the model predicts the presence or absence of jaundice and provides the probability associated.  
The program then prints the diagnosis along with symptom highlights.
