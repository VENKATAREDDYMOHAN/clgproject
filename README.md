Dynamic Question Paper Generator Using NLP
📌 Project Overview

The Dynamic Question Paper Generator is a Flask-based web application that automates the creation of question papers for B.Tech R20 syllabus. It integrates Google Gemini AI to dynamically generate questions aligned with Bloom’s Taxonomy and Course Outcomes (COs). The system reduces manual effort, ensures compliance, and provides secure access for faculty.

✨ Features

🔒 Faculty authentication & secure syllabus input

🤖 AI-generated questions using NLP (Google Gemini API)

📝 Automatic .docx paper generation with institutional headers & exam codes

📑 Two-part exam structure:

Part A – 10 short questions (2 marks each)

Part B – 5 descriptive questions with OR options (10 marks each)

🎯 Questions mapped to COs & Bloom’s Taxonomy levels

📂 Professional formatting using python-docx

🛠️ Tech Stack

Backend: Flask (Python)

AI/NLP: Google Gemini API

Document Handling: python-docx

Frontend: HTML, CSS, Bootstrap (for faculty interface)

Database: SQLite/MySQL (for faculty authentication & logs)
📊 Output

Automatically generated .docx question papers

CO & Bloom’s Taxonomy levels labeled in the document

🔮 Future Enhancements

Multi-language support for question generation

Export to PDF along with DOCX

Role-based access (Admin, Faculty, Reviewer)

Analytics dashboard for question paper history
