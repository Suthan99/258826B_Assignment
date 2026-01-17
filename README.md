🚀 FINAL STABLE AML PROJECT
Explainable Machine Learning Web Application using CatBoost & LIME

📌 Project Overview
This project is an Explainable AI (XAI) based Machine Learning web application developed to demonstrate how advanced ML models can be interpreted and explained in a user-friendly way.

The system uses:
CatBoost for robust classification
LIME (Local Interpretable Model-agnostic Explanations) for model explainability
Streamlit for an interactive web interface
The goal is to ensure model transparency, especially for real-world decision-making scenarios where understanding predictions is as important as accuracy.


⚙️ Technologies & Libraries
Python 3.10+
CatBoost
Scikit-learn
Pandas
Streamlit
Plotly
LIME
Joblib

🛠️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/FINAL_STABLE_AML_PROJECT.git
cd FINAL_STABLE_AML_PROJECT

2️⃣ Install Required Dependencies
pip install catboost streamlit pandas scikit-learn plotly lime joblib
💡 Tip: Using a virtual environment is recommended to avoid dependency conflicts.

3️⃣ Train the Machine Learning Model
python src/train_model.py
This will:
Load the dataset
Train the CatBoost model
Save the trained model for inference

4️⃣ Run the Streamlit Application
python -m streamlit run streamlit_app/app.py
After running, open your browser and navigate to:
http://localhost:8501

🧠 Explainable AI (XAI)
The application integrates LIME to:
Explain individual predictions
Highlight influential features
Improve trust and interpretability of ML decisions
This makes the system suitable for academic research, demos, and real-world decision support systems.

📊 Use Cases
Academic projects in Applied Machine Learning
Explainable AI demonstrations
Model transparency research
Decision-support systems
Teaching ML interpretability concepts

🚧 Known Issues & Notes
Ensure dataset contains no NaN values before running LIME
Python version mismatches may cause dependency issues
Tested primarily on Windows environments

📌 Future Improvements
Add automatic preprocessing pipeline
Improve error handling for missing values
Add Docker support for cross-platform stability
Extend explanations using SHAP

👩‍💻 Author
S Sivasuthan
MSc in Artificial Intelligence
University of Moratuwa, Sri Lanka

📜 License
This project is intended for educational and research purposes only.

