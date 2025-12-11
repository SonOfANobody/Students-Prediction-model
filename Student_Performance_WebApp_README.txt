
🎓 Student Performance Prediction Web App
=========================================

A machine learning-powered web application built with Flask that predicts students' academic performance based on multiple personal, academic, and social features.

⚠️ Note: Deployment of the model was not fully completed. The backend model and interface are ready, but integration and hosting are still pending.

🚀 Features
-----------
• Predicts performance class: High, Medium, or Low
• Displays model prediction probabilities
• Trained with Random Forest/XGBoost classifiers
• Easy form input for user data
• Responsive web interface using HTML + CSS (Bootstrap)

🏗️ Project Structure
--------------------
├── app.py                  # Main Flask application
├── model.pkl               # Trained ML model
├── forms.py                # WTForms for input validation
├── templates/              # HTML templates (index.html, result.html)
├── static/                 # CSS, images, JS files
├── requirements.txt        # Python dependencies
└── README.txt

📥 Installation
----------------
1. Clone this repository:
   git clone https://github.com/yourusername/student-prediction-app.git
   cd student-prediction-app

2. Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  (On Windows: venv\Scripts\activate)

3. Install required packages:
   pip install -r requirements.txt

4. Run the Flask app:
   python app.py

5. Open your browser at:
   http://127.0.0.1:5000/

🛠️ Technologies Used
---------------------
• Python 3.x
• Flask
• WTForms
• Scikit-learn
• Pandas
• NumPy
• HTML/CSS (Bootstrap)
• Jinja2

💡 Usage
---------
• Fill out the student information form on the homepage.
• Click Submit to get a prediction.
• The app will return:
  - Predicted performance class
  - Probability scores for each class

📈 Model Training (Optional for Devs)
-------------------------------------
To retrain the model:
python train_model.py

📜 License
-----------
This project is licensed under the MIT License. See LICENSE for details.

🙌 Acknowledgments
-------------------
• Kaggle Machine Learning Repository for datasets
• Scikit-learn documentation
• Flask and Bootstrap communities
