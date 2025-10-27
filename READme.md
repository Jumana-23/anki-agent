🧠 Anki Agent — Turn Your Notes Into Smart Flashcards
Tired of rewriting your study notes into flashcards?
Meet Anki Agent, an AI-powered script that transforms your PDFs, slides, and notes into clean, concise Anki flashcards — ready to memorize and review.
Built with GPT, PyMuPDF, and python-pptx, this project automates your learning workflow so you can focus on understanding, not formatting.
🚀 Features
🧾 Extracts text from PDFs and PowerPoint slides
💬 Generates high-quality question–answer flashcards using GPT
🧠 Outputs Anki-ready text for import or AnkiConnect integration
⚙️ Minimal setup — just your API key and a file to process
⚡️ Quick Start
Clone the repo
git clone https://github.com/<yourusername>/anki-agent.git
cd anki-agent
Set up your environment
python3 -m venv venv
source venv/bin/activate  # on Mac/Linux
venv\Scripts\activate     # on Windows
pip install -r requirements.txt
Add your API key
Create a .env file in the root directory:
OPENAI_API_KEY=your_key_here
Run the script
python anki_agent.py
📘 Example Output
Input (PDF or text):
Lecture: Network Security
Output:
Q: What is a Denial of Service (DoS) attack?
A: An attack that disrupts the normal functioning of a targeted server or network.
🧩 Tech Stack
OpenAI API — for generating flashcards
PyMuPDF (fitz) — for PDF parsing
python-pptx — for reading slide decks
Requests — for lightweight data handling
dotenv — for secure API key management
💡 Why I Built This
As someone who studies data science and cybersecurity, I wanted a faster way to retain complex topics without spending hours making cards manually.
This project automates that process — a small step toward AI-assisted learning.