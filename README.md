🥗 Food Ingredient Reader (OCR + AI)
A simple web application that allows users to upload an image of a food packet’s ingredient list, extract the text using OCR, and generate a short, easy-to-understand summary of the ingredients using Google’s Gemini AI.
The app is designed for normal users who want to quickly understand what’s inside packaged food and whether it may be unsuitable for people with certain health conditions.
🚀 Features
📷 Upload an image of food ingredients
🔍 Extract text using Tesseract.js (OCR)
🤖 Generate a short, simple ingredient summary
⚠️ Highlights possible concerns for people with conditions like:
Diabetes
High blood pressure
Allergies
General health sensitivity
🌐 Runs fully in the browser (no installation required)
🛠️ Tech Stack
HTML, CSS, JavaScript
Tesseract.js – client-side OCR
Google Gemini API (Gemini 2.5 Flash) – AI summarization
📌 How It Works
User uploads an image of the ingredient label
OCR extracts the text from the image
Extracted text is sent to Gemini AI
AI returns a short, easy summary with health warnings
⚠️ Important Note
This project is for learning and demo purposes only.
The Gemini API key is used on the frontend (not safe for production)
For real-world use, a backend server should be used to protect the API key
📷 Example Use Cases
Understanding packaged food ingredients
Quick health checks before buying food
Learning how OCR + AI can work together
📄 License
This project is open-source and free to use for educational purposes
