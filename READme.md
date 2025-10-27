# 🧠 Anki Agent — Turn Your Notes Into Smart Flashcards

Tired of manually making flashcards?  
**Anki Agent** automates the process using GPT — it reads your **PDFs, PowerPoint slides, or text notes** and turns them into ready-to-use **Anki flashcards** that make studying faster and smarter.

---

## 🚀 Features
- 📄 Extracts text from **PDF** and **PPTX** files  
- 💬 Generates high-quality **Q&A flashcards** using GPT  
- ⚙️ Simple setup — just add your OpenAI API key  
- 🧠 Saves output in an Anki-ready format  

---

## ⚡️ Quick Start

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<yourusername>/anki-agent.git
cd anki-agent
```

### 2️⃣ Set up your environment
```bash
python3 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

### 3️⃣ Add your API key
Create a file named `.env` in the root folder:
```
OPENAI_API_KEY=your_key_here
```

### 4️⃣ Run the script
```bash
python anki_agent.py
```

---

## 🧩 Example Output

Input:
```
PDF: Cybersecurity Lecture Notes
```

Output:
```
Q: What is a Denial of Service (DoS) attack?
A: An attack that disrupts the normal functioning of a targeted server or network.
```

---

## 🧰 Tech Stack
- **Python 3**
- **OpenAI API** — for intelligent flashcard generation  
- **PyMuPDF (fitz)** — for reading PDF content  
- **python-pptx** — for parsing PowerPoint slides  
- **python-dotenv** — for secure API key handling  
- **requests** — for lightweight HTTP requests  

---

## 🧠 Why I Built This
As a data science and cybersecurity student, I wanted to spend less time re-writing notes and more time *learning*.  
**Anki Agent** helps automate that — turning any study material into flashcards you can actually retain.

---

## 🧑‍💻 Author
**Jumana K. Alaarajee**  
[LinkedIn](https://www.linkedin.com/in/jumanaalaarajee)

---

## ⭐️ Contribute
If you find this helpful, consider giving it a ⭐️ on GitHub or contributing with new features like:
- CSV or JSON export  
- Integration with AnkiConnect  
- Streamlined GUI or web interface  

---

## ⚙️ Requirements
```
openai>=1.0.0
python-dotenv>=1.0.0
requests>=2.31.0
PyMuPDF>=1.24.0
python-pptx>=0.6.21
```

---

### 📜 License
This project is open-source and available under the **MIT License**.
