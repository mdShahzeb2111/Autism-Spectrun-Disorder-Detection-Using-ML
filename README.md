# 🧠 Autism Spectrum Disorder (ASD) Detection

This project uses machine learning techniques to detect the likelihood of Autism Spectrum Disorder (ASD) based on behavioral and screening data. ASD is a developmental disorder that affects communication and behavior, and early detection is key to effective intervention.

## 📌 Project Objectives

- Analyze ASD screening datasets
- Build a predictive model to classify individuals as ASD positive or negative
- Provide a simple interface (CLI, notebook, or web app) for predictions

## 📊 Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Autism+Screening+Adult)
- Attributes include:
  - Age
  - Gender
  - Screening responses (A1 to A10)
  - Family history of ASD
  - Who is completing the test
  - Country of residence, ethnicity

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
- Streamlit or Flask (for app deployment, optional)

## ⚙️ How It Works

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature selection

2. **Model Training**
   - Algorithms used: Logistic Regression, Random Forest, SVM, etc.
   - Train-test split
   - Model evaluation using accuracy, precision, recall, F1-score

3. **Model Deployment**
   - The best model is serialized using `joblib` or `pickle`
   - (Optional) Web app built using Streamlit or Flask

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/asd-detection.git
cd asd-detection

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook ASD_Detection.ipynb

# OR run the web app (if available)
streamlit run app.py
