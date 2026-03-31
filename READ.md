        

Crop Recommendation System for Farmers in Madhya Pradesh

BYOP Project | CSA2001 \- Fundamentals of AI and ML | VIT Bhopal    
Student: Manita kalra | Registration no . \- 25BCE10983

Problem solution-

Farmers in Madhya Pradesh frequently choose the wrong crop due to varying soil nutrients (N, P, K), pH, temperature, humidity, and rainfall. Wrong selection leads to crop failure, financial loss, and food insecurity. This project uses \*\*supervised machine learning\*\* to recommend the best crop with 99%+ accuracy.

 1\. Features-

\- Interactive web app (built with Streamlit)  
\- 7 input parameters → 22 crop recommendations (Rice, Maize, Wheat, Cotton, etc.)  
\- Model: Random Forest Classifier (best performer after comparing 5 algorithms)  
\- Complete EDA, model comparison, and hyperparameter tuning  
\- Fully reproducible and well-documented

2 .How to Run Locally- 

1\. Clone the repo:  
     
   git clone https://github.com/YOUR-USERNAME/crop-recommendation-byop-ai-ml.git  
   cd crop-recommendation-byop-ai-ml

3.Install dependencies:

pip install \-r requirements.txt

 4\. Run the app 

streamlit run [app.py](http://app.py)

5.Project structure \- 

├── app.py                  \# Interactive Streamlit web app  
├── train\_model.py          \# Training script \+ model saving  
├── Crop\_recommendation.csv \# Dataset (download from Kaggle)  
├── requirements.txt  
├── model.pkl               \# Trained model (generated after running train\_model.py)  
├── notebooks/  
│   └── EDA\_and\_Model\_Comparison.ipynb  
├── README.md  
└── Project\_Report.pdf  

6\. Requirements.txt \- 

\`\`\`txt  
streamlit  
pandas  
scikit-learn  
seaborn  
matplotlib  
Joblib

