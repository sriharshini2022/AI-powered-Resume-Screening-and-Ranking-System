# 🤖📄 AI-powered Resume Screening and Ranking System

A smart solution designed to automate and optimize the resume screening process using Artificial Intelligence (AI). This system helps organizations efficiently evaluate and rank resumes based on job descriptions, making the hiring process faster and more reliable.

---

## 📑 Table of Contents

- [Project Overview 🚀](#project-overview-🚀)  
- [Features 🎉](#features-🎉)  
- [Tech Stack 🛠️](#tech-stack-🛠️)  
- [Installation 📦](#installation-📦)  
- [Usage 🧪](#usage-🧪)  
- [Example 💻](#example-💻)  
- [Contributing 🤝](#contributing-🤝)  
- [License 📄](#license-📄)  
- [Acknowledgements 🙌](#acknowledgements-🙌)  

---

## Project Overview 🚀

The **AI-powered Resume Screening and Ranking System** leverages natural language processing (NLP) techniques and machine learning models to analyze resumes and match them to job descriptions. By using pre-trained models, it ranks resumes based on relevance and qualifications.

### Key Benefits:
- ✅ Reduces manual effort
- ✅ Minimizes hiring bias
- ✅ Speeds up the hiring process

---

## Features 🎉

- 🔍 **AI-powered Ranking**: Automatically ranks resumes based on relevance to the job description.  
- 📄 **Resume Parsing**: Extracts details like skills, education, experience, and contact info.  
- 📌 **Job Matching**: Compares resume content with job requirements.  
- 📊 **Data Visualization**: Displays match scores and top skills visually.  
- 🔧 **Customizable**: Scoring logic can be adjusted (skills, experience, education, etc.)  
- 🔄 **HR Workflow Integration**: Easily integrates into existing HR tools and pipelines.

---

## Tech Stack 🛠️

- **Python** – Core programming language  
- **TensorFlow / Keras** – AI and ML modeling  
- **spaCy / NLTK** – NLP and text analysis  
- **Scikit-learn** – Machine learning utilities  
- **Flask / FastAPI** – API development  

---

## Installation 📦

Follow these steps to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/sriharshini2022/AI-powered-Resume-Screening-and-Ranking-System.git
cd AI-powered-Resume-Screening-and-Ranking-System
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Create Virtual Environment (Optional)
```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
```

### 4. Run the Application

#### For Flask:
```bash
python app.py
```

#### For FastAPI:
```bash
uvicorn app:app --reload
```

Then navigate to [http://localhost:8000](http://localhost:8000)

---

## Usage 🧪

### Input:
- **Job Description**: Upload as a text file or document.
- **Resumes**: Upload multiple resumes (PDF, DOCX, TXT).

### Process:
1. Upload job description.
2. Upload resumes.
3. System parses and compares each resume.
4. Resumes are ranked based on job relevance.

### Output:
- 🔢 **Ranked Resume List**
- 🧠 **Match Scores**
- 📈 **Skill/Experience Visualizations**

---

## Example 💻

### Job Description:
Looking for a **Data Scientist** with skills in Python, Machine Learning, Data Analysis, and Statistics.

### Resume:
**John Doe** – Skills include Python, SQL, Data Visualization, Machine Learning.

### Result:
John Doe is ranked highly due to strong alignment with the required skills.

---

## Contributing 🤝

We welcome contributions from the community!  

### Steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make changes and commit:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push and open a Pull Request:
   ```bash
   git push origin feature-branch
   ```

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) and include tests where needed.

---

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements 🙌

- [spaCy](https://spacy.io/) and [NLTK](https://www.nltk.org/) for Natural Language Processing  
- [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) for machine learning  
- [Scikit-learn](https://scikit-learn.org/) for traditional ML  
- Open-source contributors and the community for ongoing improvements  
