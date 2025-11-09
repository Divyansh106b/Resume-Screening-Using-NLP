# Resume-Screening-Using-NLP

This project automates *resume screening* using *Natural Language Processing (NLP)* and *Machine Learning*.  
It classifies resumes into various *job categories* (like Data Science, Web Development, Testing, etc.) based on their content.

---

##  Features
- Cleans and preprocesses text using Regex & NLTK  
- Extracts features using *TF-IDF Vectorizer*  
- Trains a *Logistic Regression* model for classification  
- Achieves around *97% accuracy*  
- Visualizes resume category distribution  

---

##  Technologies Used
- Python, Pandas, NumPy  
- NLTK, Regex  
- Scikit-learn  
- Matplotlib, Seaborn

---

##  Dataset
- *File:* UpdatedResumeDataSet.csv  
- *Columns:*  
  - Category — Job role/category  
  - Resume — Resume text  

Total: *962 resumes*

---

## 📈 Model Performance
*Accuracy:* ~96.9%  
*Model Used:* Logistic Regression  
*Feature Extraction:* TF-IDF  

---

## ✨ Future Scope
- Deploy using *Streamlit* or *Flask*  
- Add *semantic similarity* for smarter matching  
- Integrate with *ATS systems*

