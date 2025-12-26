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
