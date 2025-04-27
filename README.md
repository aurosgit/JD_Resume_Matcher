# JD_Resume_Matcher
# Resume Matcher App 🚀

This is a Flask-based web application that allows you to upload multiple resumes (PDF, DOCX, or TXT) and a job description.  
The app will match resumes against the job description and suggest the top 3 best-matching resumes based on TF-IDF similarity.

## Live Demo
🌐 [App Link](https://your-app-link-here.onrender.com)  
(Will update after deployment!)

## Features
- Upload multiple resumes at once
- Supports PDF, DOCX, and TXT formats
- Match resumes based on Job Description using Machine Learning (TF-IDF + Cosine Similarity)
- Shows top 3 matched resumes with their matching scores

## How to Run Locally
1. Clone the repository
    ```bash
    git clone https://github.com/yourusername/resume-matcher.git
    cd resume-matcher
    ```

2. Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app
    ```bash
    python app.py
    ```

4. Visit `http://localhost:5000` in your browser.

## Deployment
- Hosted on Render.com (Free Hosting)
- Uses Gunicorn server for production

## Tech Stack
- Python 🐍
- Flask 🌟
- HTML5/CSS3
- scikit-learn
- PyPDF2
- docx2txt


