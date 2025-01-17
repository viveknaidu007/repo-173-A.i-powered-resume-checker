# repo-173-A.i-powered-resume-checker
here using an gemini api key , we can create our custom model checking based on our requirement


# ATS Resume Checker

This is an AI-powered resume checker that helps you optimize your resume based on a given job description. It evaluates the resume, provides a percentage match, lists missing keywords, and suggests improvements to align with the job description.


## Requirements
To run this project, you need to have the following packages installed:

```bash
pip install -r requirements.txt
```

Create a `.env` file in the root directory and paste your Google API key:

```bash
GOOGLE_API_KEY="PASTE_YOUR_API_KEY_HERE"
```

## Running the App
To start the application, run the following command:

```bash
streamlit run app.py
```

This will start a local Streamlit server where you can interact with the app.

## How It Works
1. Upload your resume in PDF format.
2. Paste the job description into the text area.
3. Click the "Submit" button, and the app will analyze your resume and provide the following details:
   - Job description match percentage.
   - Missing keywords.
   - A summary of how well your resume fits the job description.

## Technologies Used
- **Python**
- **Google Generative AI (Gemini Pro)**
- **Streamlit**: Used for building the web interface.
- **PyPDF2**: For extracting text from PDF files.
- **dotenv**: For managing environment variables.
