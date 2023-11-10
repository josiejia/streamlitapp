
# Introduction of app

# Author: Jiao Ma
# Cancer Patient Data Analysis App

## Dataset 

The dataset contains 1000 rows of hypothetical patient data, with each row representing one patient.

It has the following columns:

- Patient Id - Unique ID for each patient 
- Age - Patient's age
- Gender - 1 for male, 2 for female
- Air Pollution - Level of air pollution in the patient's environment
- Alcohol use - Patient's alcohol consumption behavior  
- Dust Allergy - Patient's dust allergy level
- Occupational Hazards - Level of hazards in patient's occupation
- Genetic Risk - Patient's genetic predisposition to cancer
- Chronic Lung Disease - Whether patient has chronic lung disease 
- Balanced Diet - Whether patient eats a balanced diet
- Obesity - Patient's obesity level
- Smoking - Whether patient smokes
- Passive Smoker - Whether patient is exposed to passive smoking
- Chest Pain - Level of chest pain
- Coughing of Blood - Level of coughing blood symptom
- Fatigue - Severity of fatigue
- Weight Loss - Severity of weight loss
- Shortness of Breath - Severity of breathlessness 
- Wheezing - Severity of wheezing
- Swallowing Difficulty - Severity of difficulty swallowing
- Clubbing of Finger Nails - Severity of nail clubbing symptom
- Frequent Cold - Frequency of cold/cough
- Dry Cough - Severity of dry cough
- Snoring - Frequency of snoring
- Level - Cancer stage (Low, Medium, High)

## App Overview

This app allows interactive exploration of the cancer patient dataset. Key features:

**Query 1:** Visualize the impact of external factors like air pollution and occupational hazards on cancer stage. Users can switch between factors.

**Query 2:** Filter patients by age and gender, analyze lifestyle factors like smoking, diet, obesity etc. Plots distributions.

**Query 3:** Show prevalence of symptoms like fatigue, weight loss, across cancer stages via interactive pie chart.

**Landing Page:** Introduces dataset and app. Provides navigation options.

st.header('Welcome to the Cancer Patient Analysis App')
st.write('This app allows you to explore and analyze data on 1000 hypothetical cancer patients. Use the sidebar to navigate between different pages.')

st.subheader('About the data')
st.write('The dataset contains synthetic data on patient demographics, lifestyle factors, symptoms, and cancer stage. It was randomly generated for this demonstrative app.')

st.subheader('App features')
st.write('Query 1 - Analyze external factors like pollution and work hazards')
st.write('Query 2 - Filter data and visualize lifestyle factors') 
st.write('Query 3 - Explore prevalence of symptoms across cancer stages')

