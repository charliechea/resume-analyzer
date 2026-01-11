# Resume Analyzer (Backend Project)

## Overview
This project is a backend web application that allows users to upload a resume file and receive structured feedback based on keyword analysis. The application extracts text from uploaded documents and evaluates how well the resume matches a predefined list of technical keywords.

This project was built to practice backend development, file handling, and API responses using Python and Flask.

---

## Features
- Resume file upload via HTTP POST
- Text extraction from uploaded documents
- Keyword matching and scoring
- JSON response containing:
  - Found keywords
  - Missing keywords
  - Resume score
  - Character count

---

## Tech Stack
- Python
- Flask
- REST API
- Text Processing

---

## Example Output
```json
{
  "filename": "resume.docx",
  "score": 13,
  "found_keywords": ["c", "embedded"],
  "missing_keywords": ["python", "flask", "linux", "git"],
  "chars": 3596
}
```
### The Start of the Resume Analyzer
![Resume Upload Interface](screenshots/Screenshot%202025-09-18%20191326.png)
What?
-Provides a simple interface for users to upload resume files for analysis
How?
-Implemented using Flask file upload handling.
-Validates file types and securely stores uploads for processing.
Results?
-Enables fast resume ingestion and prepares text for keyword analysis. Just think of it like a waiting room for a resume to be processed.

### Backend Code Structure
![Backend Code Structure](screenshots/Screenshot%202025-11-08%20124916.png)
What?
-Displays the structured feedback, like the coding process, that generates structured feedback from resume keyword analysis for the resume analyzer.
How?
-First, the coding structure extracts text from uploaded resumes.
-It compares resume content against predefined technical keywords that match the job requirements.
-Computes the resume score based on keyword coverage, like skill matching.
Results?
-It returns clear, machine-readable feedback, including:
  -Found keyword matching
  -Missing keywords
  -Resume score

### JSON Analysis Output
![Backend Code](screenshots/Screenshot%202025-12-19%20192916.png)
What?
-Displays the structured feedback that generates feedback from resume keyword analysis for the resume analyzer.
How?
-First, the coding structure extracts text from uploaded resumes.
-It compares resume content against predefined technical keywords that match the job requirements.
-Computes the resume score based on keyword coverage, like skill matching.
Results?
-It returns clear, machine-readable feedback, including:
  -Found keyword matching
  -Missing keywords
  -Resume score
