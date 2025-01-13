# **Machine Learning: Project Part 1 - Audio Analysis**

---

## **Objective**

This project aims to process audio files of interviews or debates and extract valuable information. The system:
- Identifies who speaks and when (speaker diarisation).
- Transcribes the audio for each speaker.
- Leverages large language models for sentiment analysis or speaker name identification.
- Provides a summary of each speaker’s total speaking time.

---

## Installation & Requirements

1. **Python Version**  
   - Recommended: Python 3.12. It will **not** work with Python 3.13.

3. **Environment Setup**  
   - Create a virtual environment to keep dependencies organized:
     ```bash
     python -m venv venv
     source venv/bin/activate    # On Linux/Mac
     .\venv\Scripts\activate     # On Windows
     ```
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```
---

## Usage

1. **Load Your Audio File**  
   - Place your `.wav` or `.mp3` file in the designated input folder (e.g., `./audio`).

2. **Open the Jupyter Notebook**  
   - From your project directory, launch Jupyter Notebook:
     ```bash
     jupyter lab
     ```
   - In your browser, navigate to the notebook file.

---