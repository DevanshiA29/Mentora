# Mentora

### AI-Powered Academic & Career Intelligence Platform

Mentora is a multi-service AI SaaS platform designed to assist students in **learning, research, coding, and career preparation**.

The platform combines machine learning, NLP, and analytical tools to provide **actionable academic insights and intelligent automation** for common student workflows.

Rather than solving a single problem, Mentora acts as an **AI-powered academic assistant**, offering multiple integrated tools through a unified interface.

---

# Project Vision

Students today struggle with:

• understanding complex research papers
• identifying weak academic concepts
• predicting academic performance
• optimizing programming solutions
• preparing resumes for job applications

Mentora addresses these challenges by integrating **six intelligent services** into one system.

The goal is to create a **student intelligence platform** that supports both **academic growth and career readiness**.

---

# Platform Features

## 1. Concept Gap Detector

Identifies weak areas in a student's understanding based on performance data.

### Input

* quiz scores
* test results
* topic-level performance

### Output

* concept mastery analysis
* weak topic identification
* recommended learning focus

### Purpose

Helps students prioritize study efforts by highlighting **knowledge gaps that impact performance**.

---

## 2. Resume & Cover Letter Generator (Using Job Descriptions)
Job match detector
Generates tailored resumes and cover letters aligned with specific job descriptions.

### Input

* job description
* user skills
* experience details

### Output

* ATS-optimized resume
* customized cover letter
* keyword match analysis

### Purpose

Improves the chances of passing **Applicant Tracking Systems (ATS)** used by recruiters.

---

## 3. Code Time Complexity Analyzer

Analyzes programming solutions and suggests possible performance improvements.

### Features

* Abstract Syntax Tree (AST) parsing
* nested loop detection
* complexity estimation
* optimization suggestions

### Example Output

Estimated Complexity: O(n²)

Detected Issues:

* Nested loops
* Unnecessary repeated operations

Suggested Optimization:

* Use hashing or memoization to reduce complexity.

### Purpose

Encourages students to write **efficient algorithms and understand performance tradeoffs**.

---

## 4. Research Paper Simplifier

Summarizes complex research papers into concise, readable insights.

### Input

* uploaded PDF research paper

### Output

* simplified summary
* key contributions
* explanation of technical terms

### Purpose

Helps students quickly understand **academic literature without reading entire papers line by line**.

---

## 5. Exam Score Predictor

Predicts a student's expected exam score using a trained regression model.

### Input Features

* study hours
* attendance
* mental health rating
* sleep hours
* part-time job status

### Output

* predicted exam score
* feature importance analysis
* performance insights

### Model Details

The prediction system evaluates multiple regression models and selects the best-performing one based on evaluation metrics.

### Purpose

Provides insight into how study habits influence academic performance.

---

## 6. Study Material Generator

Generates structured learning resources for any academic topic.

### Input

Topic Example:
Dynamic Programming

### Output

* concept explanation
* practice problems
* mini quiz
* flashcards

### Purpose

Allows students to **quickly generate personalized learning material for revision and practice**.

---

# System Architecture

Mentora follows a modular architecture:

Frontend

* Streamlit interactive dashboard

Backend

* Python-based services
* machine learning pipelines
* NLP processing modules

Machine Learning

* regression models for score prediction
* NLP summarization models
* code analysis via AST parsing

---

# Tech Stack

Programming Language
Python

Frameworks
Streamlit

Libraries

* scikit-learn
* pandas
* numpy
* matplotlib
* joblib

AI / NLP Tools

* transformers
* document processing libraries

---

# Project Structure

Mentora/
│
├── app.py
├── models/
│   └── exam_score_model.pkl
│
├── services/
│   ├── concept_gap_detector.py
│   ├── resume_generator.py
│   ├── code_complexity_analyzer.py
│   ├── research_paper_simplifier.py
│   ├── exam_score_predictor.py
│   └── study_material_generator.py
│
├── data/
│   └── training_dataset.csv
│
├── requirements.txt
└── README.md

---

# Installation

Clone the repository

git clone https://github.com/yourusername/mentora.git

Navigate to the project directory

cd mentora

Create a virtual environment

python3 -m venv venv

Activate the environment

source venv/bin/activate

Install dependencies

pip install -r requirements.txt

---

# Running the Application

Launch the Streamlit interface

streamlit run app.py

The application will start locally and open in the browser.

---

# Future Improvements

• advanced ML models for performance prediction
• integration with coding platforms for automatic code analysis
• personalized learning recommendations
• dashboard analytics for long-term student performance tracking

---

# Author

Devanshi Awasthi

B.Tech Computer Science Student
Backend and AI Enthusiast

---

# License

This project is intended for educational and research purposes.
