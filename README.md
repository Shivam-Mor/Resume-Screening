# Resume Screening

## Overview
This project automates resume screening using Natural Language Processing (NLP) and Machine Learning (ML) techniques. It extracts relevant details from resumes and ranks them based on job descriptions.

## Features
- Parses resumes in PDF and DOCX formats
- Extracts key details like name, skills, experience, and education
- Matches resumes with job descriptions using NLP
- Ranks candidates based on relevance
- Provides insights and analytics

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `spaCy` (NLP for text processing)
  - `NLTK` (Tokenization and text preprocessing)
  - `scikit-learn` (Machine Learning models)
  - `pandas` (Data handling and analysis)
  - `pdfplumber` & `python-docx` (Resume parsing)
- **Database**: SQLite / PostgreSQL (optional for storing resume data)
- **Web Framework (Optional)**: Flask / FastAPI for API development

## Installation
### Prerequisites
- Python 3.8+
- Virtual environment (recommended)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Shivam-Mor/Resume-Screening.git
   cd Resume-Screening
   ```
2. Set up a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python main.py
   ```

## Usage
- Upload resumes in the `/resumes` directory
- Provide a job description in the `/job_descriptions` directory
- Run the script to get ranked candidates

## API (If Using Flask/FastAPI)
- `POST /upload-resume` → Upload a resume
- `POST /upload-job-description` → Upload a job description
- `GET /ranked-candidates` → Get ranked candidates

## Future Improvements
- Improve resume parsing for different formats
- Enhance NLP model with deep learning techniques
- Add a web-based interface for easier usage

## Contributions
Feel free to open an issue or submit a pull request if you’d like to contribute!

## License
This project is licensed under the MIT License.

