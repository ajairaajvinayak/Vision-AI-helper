Vision AI helper: Assisting visually impaired users
This Streamlit application provides an AI-powered tool for visually impaired users to understand their surroundings. It offers functionalities like:

Describe Scene: Get insights about the image, including objects and suggestions using Google Gemini API.
Extract Text: Extract text from the image using Tesseract OCR.
Text-to-Speech: Hear the extracted text aloud using pyttsx3.
Features:

User-friendly interface with clear instructions.
Support for various image formats (JPG, JPEG, PNG).
Scene descriptions tailored for visually impaired individuals.
Extracted text displayed and spoken aloud for better accessibility.
How it works:

Upload an image.
Choose a feature: Describe Scene, Extract Text, or Text-to-Speech.
The application will process the image and provide the desired output.
Technology Stack:

Streamlit: Web framework for building data apps.
Google Gemini API: Scene understanding and image generation.
Tesseract OCR: Optical Character Recognition for text extraction.
pyttsx3: Text-to-speech engine.
Getting Started:

Clone this repository.
Install required libraries (pip install streamlit Pillow pytesseract google-generativeai langchain_google_genai pyttsx3).
Replace GEMINI_API_KEY in the code with your own Google API key. (See instructions on Google Cloud Platform)
Set the path to your Tesseract installation (refer to Tesseract documentation).
Run the application using streamlit run app.py (replace app.py with your actual file name).
Demo:

A live demo of the application can be found at [link to your deployed app] (if applicable).

Developer: Ajai Raaj

Contact:

Email: ajairaajvinayak@gmail.com
LinkedIn: [Link to your LinkedIn profile]
GitHub: [Link to your GitHub profile]
Additional Notes:

Consider adding badges for libraries used.
You can add screenshots or a GIF showcasing the app's functionality.
Include a license file (e.g., MIT) to clarify usage rights.
This is a well-structured README that effectively explains the purpose, functionalities, and usage of your code. It also provides valuable information for developers who want to contribute or deploy the application.














Gemini can make mistakes, so double-check it

