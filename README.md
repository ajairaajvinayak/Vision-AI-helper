# Vision AI Helper 🧠

Vision AI Helper is a Streamlit-powered web application designed to assist visually impaired users. The app provides essential AI-powered functionalities such as **image scene understanding**, **text extraction using OCR**, and **text-to-speech conversion**. With this tool, users can gain insights into their surroundings through image uploads, making it easier to navigate and interact with the world.

---

## Features 📌
- **🔍 Describe Scene**: 
  - Generates a scene description using **Google Gemini API** (Generative AI).
  - Provides a list of detected objects, their purpose, and suggestions for visually impaired users.
  
- **📝 Extract Text**: 
  - Uses **Tesseract OCR** to extract visible text from images.
  
- **🔊 Text-to-Speech**:
  - Converts extracted text into speech using the **pyttsx3** library.

---

## How It Works 💡
1. Upload an image (JPG, JPEG, PNG).
2. Choose a feature:
   - **Describe Scene** for a detailed analysis of the image.
   - **Extract Text** for text recognition using OCR.
   - **Text-to-Speech** to listen to the extracted text.
3. Experience seamless AI assistance in real-time!

---

## Installation and Setup ⚙️

### Prerequisites
- Python (>= 3.8)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) (Install and set the executable path)
- Google Gemini API key for Generative AI integration

### Clone the Repository
```bash
git clone https://github.com/ajairaajvinayak/vision-ai-helper.git
cd vision-ai-helper
