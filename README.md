# AI-Powered Resume Shortlisting Tool

🚀 **An intelligent and privacy-focused solution to automate the resume shortlisting process, ensuring fair, accurate, and actionable results for recruiters and applicants.**

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset Details](#dataset-details)
- [Future Enhancements](#future-enhancements)
- [Team Members](#team-members)
- [Acknowledgments](#acknowledgments)

---

## Overview
This project leverages **Artificial Intelligence** and **Natural Language Processing (NLP)** to streamline the recruitment process by automating resume evaluation. Given a set of resumes and job descriptions, the tool:
- Extracts key information.
- Matches skills, experience, and education to job requirements.
- Provides feedback for applicants on potential improvements.

### Hackathon Focus:
- **Innovation**: Advanced NLP techniques for semantic understanding.
- **Accuracy**: Ensures fair and unbiased shortlisting.
- **Usability**: Simple interface for both recruiters and applicants.

---

## Features
1. **Resume Parsing**:
   - Extracts structured data (e.g., skills, education, experience) from unstructured documents (PDF, Word).
2. **Job Matching**:
   - Ranks candidates using a weighted scoring algorithm based on the job description.
3. **Feedback Generation**:
   - Highlights missing skills, experience gaps, and suggests improvements.
4. **Insights Visualization**:
   - Provides graphical insights into candidate match scores.
5. **Privacy Focus**:
   - All data is processed locally with optional anonymization.

---

## Tech Stack
- **Backend**: Python, Flask
- **NLP Frameworks**: spaCy, BERT, Hugging Face Transformers
- **Frontend**: Streamlit for user interaction
- **Database**: SQLite (for demo purposes)
- **Visualization**: Plotly, Matplotlib
- **Deployment**: Dockerized application for portability

---

## Installation

### Prerequisites
- Python 3.8 or above
- Docker (optional)

### Steps
1. Clone the repository:
   ```bash
    git clone https://github.com/your-repo/resume-shortlist-ai.git
