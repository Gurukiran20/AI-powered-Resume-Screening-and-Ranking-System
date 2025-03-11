# AI-powered-Resume-Screening-and-Ranking-System
This project is designed to automate the resume screening and ranking process using Artificial Intelligence (AI) and Natural Language Processing (NLP) techniques. It helps recruiters save time and reduce human bias by efficiently evaluating resumes based on their relevance to a provided job description. Using TF-IDF vectorization and cosine similarity, the system ranks candidates based on their suitability, ensuring fast and accurate shortlisting.

## Introduction
The AI-Powered Resume Screening and Ranking System is built to address the challenges faced by recruiters in shortlisting candidates from a large pool of resumes. Manual resume screening is time-consuming, inefficient, and often leads to human bias. This project provides an automated and scalable solution by evaluating resumes based on their alignment with the job description, ensuring that only the most suitable candidates are highlighted.

## Problem Statement
Recruiters often spend hours manually reviewing hundreds of resumes, which is prone to oversight and subjective bias. This results in inefficient hiring and the potential for overlooking qualified candidates. An AI-powered resume screening and ranking system automates this process, ensuring faster, more accurate, and unbiased candidate evaluation.
## Technologies Used
Programming Language: Python
Development Environment: Google Colab
Libraries:
PyPDF2: For extracting text from PDF resumes
scikit-learn: For implementing TF-IDF vectorization and cosine similarity
ipywidgets: For interactive file upload and user interface
## System Architecture
![Updated_Resume_Screening_Flowchart](https://github.com/user-attachments/assets/01c126d8-9ae9-4527-afcb-a8b322fd3aef)

## How It Works
### Upload PDF Resumes:
Users upload multiple resumes in PDF format using Google Colab’s interactive file upload feature.

### Extract Text:
The PyPDF2 library extracts text content from each resume, preparing it for analysis.

### Input Job Description:
The user enters a job description that serves as the reference for candidate evaluation.

### Text Processing and Vectorization:
The TfidfVectorizer converts the text data into numerical representations, highlighting important terms while reducing noise.

### Calculate Similarity:
Using cosine similarity, the system measures how closely the resumes align with the job description.

### Rank Resumes:
Resumes are ranked based on their similarity scores, with higher scores indicating a better match for the job.

### Display Results:
A ranked list of resumes with their respective similarity scores is displayed for easy candidate evaluation.

## Future Enhancements
Support for additional file formats like Word documents.
Advanced NLP models like BERT or spaCy for better text understanding.
Weighted scoring for prioritizing job requirements (skills, experience, certifications).
Sentiment analysis and soft skill evaluation from cover letters.
Integration with Applicant Tracking Systems (ATS) for end-to-end recruitment management
