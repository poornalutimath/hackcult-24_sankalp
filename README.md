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

2. Navigate to the project directory:
   bash
   Copy code
   cd resume-shortlist-ai
3. Install dependencies:
   bash
   Copy code
   pip install -r requirements.txt
   Run the application:
   bash
   Copy code
   python app.py
4. For Docker users:
   bash
   Copy code
   docker build -t resume-shortlist .
   docker run -p 5000:5000 resume-shortlist

## Usage
-**Upload resumes (PDF, DOCX, or text formats) and a job description.
-**View ranked candidates based on job fit.
-**Explore visual insights and download feedback for candidates.

## Future Enhancements
-** Integration with LinkedIn for real-time resume fetching.
- ** Support for multilingual resumes and job descriptions.
- ** Advanced bias detection to promote diversity in hiring.
- ** Cloud integration for scalable deployment in enterprise environments.

## Team Members
[Poorna]
Role: Backend Development & NLP
Contributions: Developed resume parsing and job matching algorithms.
Contact: poorna.email@example.com

[Teammate 1 Name]
Role: Frontend Development & Visualization
Contributions: Designed the user interface and insights visualization.
Contact: teammate1.email@example.com

[Teammate 2 Name]
Role: DevOps & Deployment
Contributions: Handled Dockerization and deployment.
Contact: teammate2.email@example.com

[Teammate 3 Name]
Role: Data Preprocessing & Model Optimization
Contributions: Prepared datasets and optimized the AI models.
Contact: teammate3.email@example.com

## Acknowledgments
We thank the hackathon organizers for providing a platform to innovate. Inspiration for this project was drawn from challenges faced in recruitment processes, and our goal is to make hiring fairer and more efficient.





