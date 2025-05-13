# Resume Draft Builder AI

A Streamlit-based web application that uses Google's Generative AI (Gemini) to help users create professional, ATS-friendly resumes quickly and efficiently.

## Features

- Interactive web interface for inputting resume details
- AI-powered resume generation using Google's Gemini model
- ATS-friendly resume formatting
- Multiple download options (DOCX and TXT formats)
- Customizable sections including:
  - Contact information
  - Professional experience
  - Education
  - Technical skills
  - Certifications
  - Projects

## Prerequisites

- Python 3.12
- Google API key for Gemini model access

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Sophyia7/resume-ai-assistant 
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate # On Mac and Linux
venv\Scripts\activate # On Windows
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
  - Create a `.env` file in the root directory
  - Add your Google API key:
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Usage

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically `http://localhost:8501`)

3. Fill in your resume details in the form

4. Click "Generate Resume" to create your resume

5. Download your resume in either DOCX format

## Project Structure

- `app.py`: Main Streamlit application and user interface
- `resume_agent.py`: Resume generation logic using Google's Generative AI
- `utils.py`: Utility functions for document creation and formatting
- `config.py`: Configuration settings and environment variable management
- `requirements.txt`: Project dependencies

## Environment Variables

- `GEMINI_API_KEY`: Your Google API key for accessing the Gemini model

## Dependencies

Key dependencies include:
- streamlit
- google-generativeai
- python-docx
- python-dotenv

For a complete list of dependencies, see `requirements.txt`.

## License

MIT License


Have fun using this!