# Bifocal: AI-Powered Digital Safety & Communication Analysis

Bifocal is an advanced AI-driven platform designed to analyze digital communications for patterns of manipulation, emotional abuse, and concerning behaviors. Built for both research and real-world impact, Bifocal empowers users to understand, track, and protect their digital well-being through state-of-the-art machine learning and a modern, intuitive interface.

---

## 🚀 Key Features

- **AI Message & Voice Analysis**: Upload text or voice messages to detect gaslighting, stalking, coercive control, and more using custom-trained NLP and audio models.
- **Pattern Detection**: Uncover hidden behavioral trends and emotional shifts in conversations over time.
- **Interactive Dashboard**: Visualize risk levels, flagged contacts, and communication statistics with beautiful, responsive charts.
- **Personalized Journaling**: Document experiences and receive real-time, supportive feedback powered by AI.
- **Resource Finder**: Instantly connect with local and national support resources tailored to your needs.
- **Privacy-First**: All analysis is performed securely, with user data protection as a core principle.

---

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript, Vite, Emotion (CSS-in-JS), Recharts
- **Backend**: Python (Flask), Scikit-learn, HuggingFace Transformers, Joblib
- **ML/NLP**: Custom-trained Random Forest classifiers, TF-IDF vectorization, Sentiment Analysis, RAG (Retrieval-Augmented Generation) for clinical text
- **DevOps**: Docker-ready, CORS-enabled API, modular monorepo structure

---

## 🏁 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/bifocal.git
cd bifocal
```

### 2. Install Frontend Dependencies
```bash
cd safeguard
npm install
```

### 3. Start the Frontend
```bash
npm run dev
```

### 4. Set Up the Backend (ML Server)
```bash
cd ml_server
pip install -r requirements.txt
python app.py
```

### 5. (Optional) Train or Export Models
- See `export_model.py` and `HACKAI.ipynb` for model training and experimentation.

---

## 📊 Example Use Cases
- **Survivors & Advocates**: Identify and document patterns of digital abuse for personal safety or legal support.
- **Researchers**: Analyze large-scale communication datasets for behavioral science and public health.
- **Developers**: Integrate Bifocal’s ML pipeline into other digital safety tools.

---

## 🤝 Contributing
I welcome contributions from the community! Please open issues or submit pull requests for new features, bug fixes, or improvements.

---

## 📄 License
MIT License. See [LICENSE](LICENSE) for details.

---

> **Bifocal: Making the invisible visible, one message at a time.**
