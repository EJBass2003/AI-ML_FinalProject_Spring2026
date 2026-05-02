# Predicting Heart Disease: A Machine Learning Approach

- <a href="https://colab.research.google.com/drive/1QZaDN01HinPW8Y1btfd0YAFc7m18rCFs">Final Project Notebook</a><br>

# Project Overview:
This project developed a Random Forest pipeline to predict heart disease presence using the UCI Heart Disease Dataset. The mission is personal because the condition runs in my family. Accurate early intervention is vital since heart disease is the leading cause of death globally. By leveraging 303 clinical records with 14 gold standard features like max heart rate and thalassemia type, I created a tool that aligns mathematical predictions with medical intuition to support life-saving clinical decisions.

# Performance at a Glance:
- Accuracy: **91.8%**
- AUC: 0.90   
- Precision: 0.92   
- Recall: 0.88   

# Dataset at a Glance:
- Rows: 303   
- Features: 14   
- Target Type: Binary Classification   
- Source: UCI Machine Learning Repository

# Top 5 Clinical Predictors
- Cat_thal_3.0 (Thalassemia): This was the strongest predictor in the model and refers to a normal result on a thalassemia blood test. In a diagnostic context, this specific category helps the model distinguish healthy heart function from those with genetic blood flow defects.  
- Num_thalach (Maximum Heart Rate): This represents the highest heart rate achieved by a patient during a stress test. It is a critical biometric indicator because a lower maximum heart rate during exercise often correlates with a higher risk of cardiovascular issues.  
- Num_oldpeak (ST Depression): This metric measures the stress on the heart by looking at ECG abnormalities during exercise relative to rest. High "oldpeak" values are a classic medical sign of reduced blood flow to the heart muscle.  
- Cat_cp_4.0 (Asymptomatic Chest Pain): This category identifies patients who experience "silent" or asymptomatic chest pain. This is a high-priority predictor because patients without obvious symptoms can often be at higher risk due to a lack of early warning signs.  
- Cat_ca_0.0 (Major Vessels): This refers to the absence of major blood vessels colored during a fluoroscopy test. A value of zero typically indicates clear, unobstructed blood flow, which serves as a vital mathematical anchor for the model to identify healthy patients.

# Visualizations:

**ROC Curve**
<img width="572" height="582" alt="Screenshot 2026-05-01 212457" src="https://github.com/user-attachments/assets/e6075b4c-c90a-4a52-8d54-5a495f1b57de" />

**Correlation Heatmap**
<img width="991" height="925" alt="Screenshot 2026-05-01 212521" src="https://github.com/user-attachments/assets/ec4068ef-804f-439a-b668-c04bd0b1dc78" />

**Confusion Matrix**
<img width="549" height="499" alt="Screenshot 2026-05-01 212539" src="https://github.com/user-attachments/assets/50e9db2b-1cd0-4d1b-91a8-95b5c38cc369" />

**Feature Importance**
<img width="1038" height="743" alt="Screenshot 2026-05-01 212553" src="https://github.com/user-attachments/assets/d2aa4b69-8de5-42ab-ab4c-dde60e0fb5b9" />
