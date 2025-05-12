
# Automated Essay Feedback System

This project is a mini-project developed as part of an academic curriculum, focusing on the development of an intelligent, automated system for providing feedback on student essays using Natural Language Processing (NLP).

## 🔍 Overview

In the domain of Educational Technology, timely and personalized feedback significantly enhances student learning outcomes. This project introduces an **Automated Essay Feedback System** that evaluates essays by detecting reasoning gaps, logical flaws, and argumentative inconsistencies using advanced NLP techniques like Sentence-BERT and rule-based logic.

## 🎯 Objectives

- Identify logical inconsistencies and weak argumentative links in student essays.
- Provide real-time, context-aware, constructive feedback.
- Personalize feedback based on the student’s proficiency level.
- Reduce the workload of educators through scalable automation.

## ⚙️ Features

- **Logical Gap Detection**: Uses Sentence-BERT to analyze coherence between consecutive sentences.
- **Rule-based Feedback Generation**: Highlights weak transitions and suggests improvements.
- **Personalization Module**: Feedback is tailored for beginner, intermediate, or advanced students.
- **Scalability**: Can process multiple essays from a directory.

## 🛠️ Tech Stack

- Python
- NLP: [Sentence-BERT (SBERT)](https://www.sbert.net/)
- Libraries: `nltk`, `sentence-transformers`, `pandas`, `os`

## 📁 Project Structure

```
project/
├── code.txt               # Main Python script
├── sample_essays/         # Folder with sample essay .txt files
├── Abstract.docx          # Project abstract
├── Automated essay feedback.pptx  # Presentation file
└── README.md              # Project documentation (this file)
```

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install sentence-transformers nltk pandas
   ```

2. Download NLTK tokenizers:
   ```python
   import nltk
   nltk.download('punkt')
   ```

3. Place sample essays in the `sample_essays/` directory (as `.txt` files).

4. Run the script in `code.txt`.

## 📌 Example Output

For a sample essay, the system identifies weak logical links between sentences and generates feedback such as:

```
--- Context ---
Sentence 1: ... 
Sentence 2: ...

Feedback:
These sentences may lack a clear logical connection. Consider adding a transitional phrase or elaborating the reasoning.
```

## 👨‍💻 Contributors

- Nikhil B
- Nithishwaran A
- Parvesh Mushraf
- Arul Kumaran P

## 📄 License

This project is intended for academic and educational use only.
