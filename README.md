# 🌏 LokKala – India's Cultural Clipbook 🇮🇳

LokKala is a lightweight, open-source Streamlit web app that enables users to contribute folk stories, local proverbs, and meme captions in Indian languages. It’s designed to work even in low-bandwidth or offline environments. Every contribution helps build a culturally rich AI corpus as part of the viswam.ai mission.

---

## 🚀 Project Overview

- 🎯 **Goal:** Collect high-quality, culturally diverse language data from Indian users
- 🌐 **Use Case:** A creative and accessible platform for crowdsourced contributions in Indian languages
- 📦 **Built With:** Streamlit, Hugging Face Transformers, PWA support for offline-first access

---

## 🔧 Features

- ✍️ Submit folk tales, proverbs, or meme captions
- 🧠 Optional AI assistance for caption generation or translation
- 🌐 Language selector with support for multiple Indian dialects
- 📶 Offline-first: Works in low or no connectivity and syncs later
- 💾 Saves contributions locally until sync is possible

---

## 🏗️ Architecture Overview

- **Frontend:** Streamlit (lightweight UI)
- **AI Backend:** Hugging Face Transformers (language detection, suggestion, etc.)
- **Offline Support:** PWA + IndexedDB for storing unsynced user content
- **Deployment:** Hugging Face Spaces

---

## 📦 Installation Instructions (For Developers)

1. **Clone the Repo**
   ```bash
   git clone https://code.swecha.org/<your-repo>.git
   cd lokkala
