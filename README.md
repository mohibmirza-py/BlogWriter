# BlogWritingCrew App

## Overview
BlogWritingCrew is an automated application designed to streamline the process of planning, writing, and editing blog articles. The app leverages various AI models to fulfill distinct roles in the content creation process: Content Planner, Content Writer, and Editor. Each role is designed to work collaboratively to produce high-quality blog content.

## Features
- **Content Planner**: Plans engaging and factually accurate content.
- **Content Writer**: Writes insightful and factually accurate opinion pieces.
- **Editor**: Edits the content to ensure quality and coherence.

## Installation

### Prerequisites
- Python 3.8+
- [pip](https://pip.pypa.io/en/stable/installation/)
- [Streamlit](https://streamlit.io/)
- [Langchain](https://github.com/hwchase17/langchain)
- [dotenv](https://github.com/theskumar/python-dotenv)

### Clone the Repository
```bash
git clone https://github.com/yourusername/BlogWritingCrew.git
cd BlogWritingCrew 
```
### Install dependencies
```bash
pip install -r requirements.txt
```
### Environment Variables
Create a `.env` file in the root directory and add the necessary environment variables:
```bash
 .env
 Add your environment variables here
 ```

### Run the App
```bash
streamlit run app.py
```

