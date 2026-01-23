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
-Shows the files being opened up, having backend, frontend, and README.md included in the file.
-It is the process of sorting the files out before we open up Visual Studio Code (VSC).
-We have these files so we can implement them into our coding, so our process works to achieve the project's result.

### Backend Code Structure
![Backend Code Structure](screenshots/Screenshot%202025-11-08%20124916.png)
How?
-Based on the image of the coding structure from Visual Studio Code (VSC), we incorporate application developments such as front-end and backend in our coding structure.
-If you look at the coding structure in the image how it works is that we build our back end and front end by using Python which makes it for that the front end is for users and applicants to interact by submitting their resume in the files and the back end generates the JSON so it can extract text and grade the resume based on the skill matching of the job.
-This image is just the coding process for the AI Resume Analyzer before it launched.

### JSON Analysis Output
![Backend Code](screenshots/Screenshot%202025-12-19%20192916.png)
Results?
-The resume returns clear, machine-readable feedback, including:
  -Found keyword matching
  -Missing keywords
  -Resume score
-It resulted in scoring the resume by AI before its handed over to a human.

