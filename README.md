# Resume Matching with JD

Resume Matching with JD is an AI-powered Flask web application that helps recruiters and job seekers by comparing resumes with job descriptions. Using Natural Language Processing (NLP), it ranks resumes based on TF-IDF vectorization and cosine similarity.🚀

## 🎯 Features

✔️ Upload Multiple Resumes – Supports PDF, DOCX, and TXT formats  
✔️ Enter Job Descriptions manually for comparison  
✔️ AI-Powered Resume Matching using TF-IDF Vectorization  
✔️ Similarity Scoring – Uses cosine similarity to rank resumes  
✔️ Top Matching Resumes Displayed with similarity scores  


## 🛠 Technologies Used

**🚀 Frontend:**  
- HTML  
- CSS  
- Bootstrap  

**🐍 Backend:**  
- Flask (Python)  

**🧠 Machine Learning:**  
- Scikit-Learn (TF-IDF, Cosine Similarity)  

**📜 File Processing:**  
- PyPDF2  
- docx2txt  

## 🏗 Installation Guide

🔹 **Step 1: Clone the Repository**

```bash
git clone https://github.com/Chetannrevankar/Resume_Matching_with_JD.git
cd resume-matcher
```

🔹 **Step 2: Set Up a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

🔹 **Step 3: Install Dependencies**

```bash
pip install Flask PyPDF2 docx2txt scikit-learn
```

🔹 **Step 4: Run the Application**

```bash
python main.py
```

## 🎯 How to Use

1️⃣ **Open the Web App :**  Run the Flask app and open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

2️⃣ **Enter Job Description :**  Copy and paste the job description into the provided text box.

3️⃣ **Upload Resumes :**  Select and upload one or multiple resumes (PDF, DOCX, or TXT format).

4️⃣ **Match Resumes :**  Click the "Match Resumes" button to process the resumes.

5️⃣ **View Results :**  The app ranks resumes based on similarity and displays the top-matching resumes with similarity scores.


## 📌 Author

- Developed by [Chetan N Revankar](https://github.com/Chetannrevankar)

## 📜 License

[MIT](https://github.com/Chetannrevankar/Resume_Matching_with_JD/blob/main/LICENSE)

## 🌟 Acknowledgements

- [Flask](https://flask.palletsprojects.com/en/stable/) : for providing a lightweight and powerful web framework.  
- [Scikit-Learn](https://scikit-learn.org/stable/index.html) : for offering easy-to-use ML tools for text analysis.  
- [PyPDF2 & docx2txt]() : for enabling resume text extraction from different file formats.  
- [Bootstrap](https://getbootstrap.com/) : for helping create a clean and responsive UI.  
- [The Open-Source Community]() : for continuous inspiration and support! 💡

## 📸 Screenshots

- [Frontend](https://github.com/Chetannrevankar/Resume_Matching_with_JD/blob/main/ML_project/FrontEnd.png)
- [Uploading JD & Resume](https://github.com/Chetannrevankar/Resume_Matching_with_JD/blob/main/ML_project/Uploading_JD_Resume.png)
- [Result](https://github.com/Chetannrevankar/Resume_Matching_with_JD/blob/main/ML_project/Result.png)

