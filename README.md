AI Document Summarizer
This project is a versatile and reusable web application that serves as a mini-project for a document summarization model. It allows users to either paste text or upload a file (PDF, Word, or TXT) to generate a concise, AI-powered summary. The model can be seamlessly integrated into other projects, providing a powerful utility for improving other applications.

The application is built as a single-page web app, leveraging the Gemini API for its core summarization functionality. This project serves as an excellent example of building practical AI applications for everyday use, demonstrating skills in both web development and integration with large language models.

Key Features
Intelligent Summarization: Powered by the Gemini API, the app generates accurate and coherent summaries of long documents.

Multi-Format Support: Easily process text from the input field or upload .txt, .pdf, and .docx files.

Intuitive User Interface: A clean, modern, and fully responsive design built with HTML and Tailwind CSS ensures a seamless user experience on any device.

Client-Side Processing: File parsing for PDF and DOCX files is handled in the browser, minimizing server-side load.

Copy-to-Clipboard: A simple button allows users to quickly copy the generated summary.

Technologies Used
HTML5: For the application's structure.

Tailwind CSS: For a modern and responsive user interface.

JavaScript (ES6+): For all client-side logic, including API calls and file handling.

Gemini API: The core AI engine for summarization.

pdf.js: A library for parsing and extracting text from PDF documents.

mammoth.js: A library for converting DOCX files to plain text.

Getting Started
To run this project locally, you will need a Gemini API key.

Get a Gemini API Key: Visit the Google AI Studio and create a new API key.

Clone the Repository: Copy the HTML code into a local file named index.html.

Insert Your API Key: Find the apiKey variable in the script tag and replace the placeholder with your key.

const apiKey = "YOUR_API_KEY_HERE";


Open in Browser: Open the index.html file in your preferred web browser.

Once the page loads, you can start summarizing documents immediately!
