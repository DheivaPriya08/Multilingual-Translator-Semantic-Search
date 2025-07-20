# Multilingual-Translator-Semantic-Search
Multilingual Translator with Semantic Search and BLEU Evaluation — AI-enhanced translation system that connects languages with Sanskrit knowledge through intelligent retrieval and scoring.
# 🌍 Multilingual Translator + Semantic Search (Enhanced)

This project is a smart multilingual translator web app that offers:

- ✅ **Automatic language detection**
- 🌐 **High-quality translation** between Indian and foreign languages
- 🧠 **Semantic search** to find similar Sanskrit-based concepts
- 📊 **Optional BLEU score evaluation** (with human reference)
- 📄 **Downloadable report** summarizing the output
- 🚫 **Input length handling** to avoid translation errors

> Developed using Hugging Face Transformers, Sentence Transformers, FAISS, and Gradio — and deployable to Hugging Face Spaces.

---

## ⚠️ Input Limit Notice

Please enter **up to 3 lines** or **2000 characters** maximum.

- If input is too long, the app will show an error and skip translation.

---

## 🚀 Live Demo

🔗 [Click here to try the app on Hugging Face Spaces](https://huggingface.co/spaces/DheivaCodes/Multilingual-translator)

---

## 🔧 Features

| Feature | Description |
|--------|-------------|
| **Language Detection** | Auto-identifies input language using `xlm-roberta-base-language-detection` |
| **Translation** | Uses Facebook’s `NLLB-200-distilled-600M` model |
| **Semantic Search** | Finds similar Sanskrit concepts using Sentence Transformers + FAISS |
| **BLEU Score** | Optional evaluation metric (if human reference is provided) |
| **Semantic Plot** | Horizontal bar chart for top 3 semantic similarity scores |
| **Download Report** | Creates a `.txt` file (includes all outputs + BLEU score) |
| **Error Handling** | Graceful messages for empty or long input |

---

## 🌐 Supported Languages

| Code       | Language  |
|------------|-----------|
| eng_Latn   | English   |
| hin_Deva   | Hindi     |
| tam_Taml   | Tamil     |
| tel_Telu   | Telugu    |
| san_Deva   | Sanskrit  |
| fra_Latn   | French    |
| spa_Latn   | Spanish   |
| deu_Latn   | German    |
| jpn_Jpan   | Japanese  |
| zho_Hans   | Chinese   |
| arb_Arab   | Arabic    |

---

## 📄 Downloadable Report

The app generates a `.txt` file containing:

- Detected source language
- Translated output
- Semantic matches (with similarity scores)
- BLEU score (if a human reference translation is given)

---

## 🚧 Future Enhancements

- 🎙️ Speech-to-text input support  
- 🔊 Text-to-speech audio output  
- 📸 OCR: Translate text from uploaded images  
- 🆕 Add more Indian languages and transliteration features

---

## 👩‍💻 Author

**Dheiva Priya V**  
M.Sc. Data Science, SASTRA University

---

## 📜 License

This project is licensed under the **MIT License**.
