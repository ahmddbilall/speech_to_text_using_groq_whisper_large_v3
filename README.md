# Speech-to-Text Application Using Groq

Welcome to the Speech-to-Text application built with Groq and Streamlit! This application allows you to convert audio files into text using the Groq API.

## Features

- Upload audio files in `.mp3` or `.wav` format.
- Transcribe audio to text using Groq's Whisper model.
- Simple and interactive web interface powered by Streamlit.

## How to Use

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/repository.git
cd repository
```

### 2. Set Up Environment Variables
Create a .env file in the root directory of the project and add your Groq API key:
```
GROQ_API_KEY="YOUR_KEY"
```

### 3. Install Dependencies
Install the required Python packages using pip:

```python
pip install -r requirements.txt
```

### 4. Run the Application
Start the Streamlit application:
```
streamlit run main.py
```
