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
### Resume Upload Interface
![Resume Upload Interface](screenshots/Screenshot%202025-09-18%20191326.png)

### JSON Analysis Output
![JSON Output](screenshots/Screenshot%202025-11-08%20124916.png)

### Backend Code Structure
![Backend Code](screenshots/Screenshot%202025-12-19%20192916.png)
