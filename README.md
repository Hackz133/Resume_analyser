# AI Resume Analyzer

An AI-powered Resume Analysis application built using LangChain, Streamlit, and LLM APIs.

This project evaluates resumes against job descriptions using a multi-agent workflow that analyzes:

* Skill & Education Fit
* Work Experience Alignment
* Salary-Market Relevance

## Features

* Upload Resume PDF
* Upload Job Description PDF
* AI-powered candidate evaluation
* Multi-agent architecture
* Streamlit web interface
* PDF text extraction
* Tool-integrated analysis workflow

## Tech Stack

* Python
* LangChain
* Streamlit
* Groq API
* DuckDuckGo Search
* Wikipedia API
* Pydantic
* PyPDF

## Project Structure

```bash
main.py
requirements.txt
README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Hackz133/Resume_analyser.git
cd Resume_analyser
```

Create virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

### Windows

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file locally:

```env
GROQ_API_KEY=your_api_key
```

For Streamlit Cloud deployment, use:

```python
st.secrets["GROQ_API_KEY"]
```

## Run Locally

```bash
streamlit run main.py
```

## Deployment

This project is deployed using Streamlit Community Cloud.

## Learning Outcomes

This project was built as part of hands-on learning in:

* AI Agents
* LangChain
* Prompt Engineering
* LLM APIs
* Tool Calling
* Streamlit Deployment
* Multi-Agent Workflows

## Future Improvements

* ATS score calculation
* Better UI/UX
* Database integration
* Resume feedback suggestions
* Authentication system

## Author

Abdul Hafeez
