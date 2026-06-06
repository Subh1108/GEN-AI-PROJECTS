# AI Resume Analyzer using Llama 3 & Ollama

## Overview

This project is an AI-powered Resume Analysis System built using **Python**, **LangChain**, **Ollama**, and **Llama 3**. It extracts resume content from a PDF and performs multiple career-focused analyses, including recruiter-style evaluation, job matching, career recommendations, salary estimation, skill-gap analysis, and company readiness assessment.

The goal is to simulate how recruiters and hiring managers evaluate candidates while providing actionable insights for career growth.

---

## Features

### Resume Extraction
- Reads resume PDFs using **PyPDF**
- Extracts text automatically
- Prepares resume data for LLM analysis

### Recruiter Evaluation
Provides:
- Overall resume score
- Strengths and weaknesses
- Missing skills
- Recommended projects
- Internship suggestions

### Job Description Matching
Compares a resume against a target job description and returns:
- Match score
- Missing skills
- Strong matches
- Interview readiness
- Improvement recommendations

### Career Path Analysis
Evaluates suitability for:
- Machine Learning Engineer
- Data Scientist
- Data Analyst
- Software Engineer

### Salary Prediction
Generates estimates for:
- Entry-level salary
- Salary after 2 years
- Salary after 5 years
- Remote opportunities
- High-income skill recommendations

### Industry Benchmarking
- Missing technologies
- Missing certifications
- Missing projects
- Recruiter concerns
- Improvement roadmap

### Big Tech Readiness Assessment
Evaluates preparedness for:
- Google
- Microsoft
- Amazon
- Meta
- Nvidia

### Future Career Recommendations
Analyzes:
- Full-time job
- Higher studies
- Research
- GATE
- MS Abroad

---

## Tech Stack

- Python
- Jupyter Notebook
- PyPDF
- LangChain
- Ollama
- Llama 3

---

## Installation

```bash
pip install pypdf langchain langchain-ollama
```

Install Ollama and pull Llama 3:

```bash
ollama pull llama3
```

---

## Project Structure

```text
.
├── Resume_Analyzer.ipynb
├── README.md
└── requirements.txt
```

---

## Author

**Subhadeep Banerjee**
