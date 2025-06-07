# nlp_project1
# 📘 IELTS Vocabulary Extractor from PDF

This project helps IELTS students improve their vocabulary by identifying difficult words from any uploaded PDF and providing their meanings and example sentences.

## ✨ Features

- Upload any English PDF
- Automatically extracts text
- Detects uncommon (difficult) words
- Provides:
  - 📖 Meaning
  - 💬 Usage example (if available)

## 🔧 How It Works

1. Upload a PDF file (e.g., an IELTS reading passage)
2. The code extracts all words
3. Common English words are filtered out
4. For each remaining difficult word:
   - Definition is fetched from [Free Dictionary API](https://dictionaryapi.dev/)
   - Example sentence is shown

## 📦 Requirements

- Google Colab
- Python libraries:
  - `PyMuPDF` (`fitz`)
  - `nltk`
  - `requests`

## ▶️ How to Run

1. Open the Colab notebook.
2. Run the cells to upload your PDF and view the word meanings.
3. Adjust the number of words if needed (`hard_words[:30]`).

## 📌 Use Cases

- IELTS/TOEFL exam prep
- Academic reading help
- Vocabulary enrichment

---

✅ **Simple, fast, and learner-friendly!**
