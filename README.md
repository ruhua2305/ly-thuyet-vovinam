<div align="center">
  <img src="Phu_hieu_vovinam.png" alt="Vovinam Logo" width="120" />

  # Vovinam Theory Q&A System 🥋

  *A Web-based application designed to help Vovinam practitioners study and test their knowledge of martial arts theory using Speech-to-Text technology.*

  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
  ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

  [👉 Visit the Live Demo](https://ruhua2305.github.io/ly-thuyet-vovinam/)
</div>

---

## 📖 Introduction
This project is a standalone Single-Page Application (SPA) built with Vanilla JavaScript. It is designed to assist Vovinam practitioners (especially students at FPT University) in reviewing martial arts theory. The system simulates a real-world oral examination environment through automated text-to-speech questioning and voice-based answer recording and grading.

## 📸 Screenshots

| Dashboard & Statistics | Voice-based Practice Interface |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/ruhua2305/ly-thuyet-vovinam/main/trang-chu.png" width="400"> | <img src="https://raw.githubusercontent.com/ruhua2305/ly-thuyet-vovinam/main/luyen-tap.png" width="400"> |

## ✨ Key Features
- 🎙️ **Voice Interaction:** Automatically reads questions (Text-to-Speech) and recognizes user answers via Microphone (Speech-to-Text).
- 🧠 **Intelligent Grading (Keyword Matching):** Automatically analyzes, normalizes text, and matches keywords to calculate percentage scores (%).
- 🎯 **4 Practice Modes:**
  - `Mock Exam`: Selects 3 random questions (length-balanced) with a timer.
  - `Study Mode`: Sequential review of the entire question bank.
  - `Flashcard`: Quick flip-card mode for memorization without a microphone.
  - `Weak Questions`: Automatically filters questions with <50% accuracy for targeted practice.
- 📊 **Local Progress Tracking:** Securely stores scores directly in the browser; no database required. Supports data Import/Export via `.json` files.
- ⚡ **Offline-Ready:** A lightweight SPA that runs entirely without backend dependencies.

## 🛠 Setup & Development
This project is built using pure HTML, CSS, and JS. No complex build environments (like Node.js) are required.

1. **Clone this repository:**
```bash
   git clone [https://github.com/ruhua2305/ly-thuyet-vovinam.git](https://github.com/ruhua2305/ly-thuyet-vovinam.git)
