# 🎙️ VocabVoice - AI Voice Vocabulary Coach

An interactive, AI-powered voice vocabulary learning agent prototype built for language learners. Practice vocabulary through real-time speech recognition, speech synthesis, active recall quizzes, and pronunciation training.

🔗 **Live Prototype Link:** [https://nikhilkumarjha62.github.io/vocab-voice-agent/](https://nikhilkumarjha62.github.io/vocab-voice-agent/)

---

## 🌟 Key Features

1. **🎙️ Real-time Two-Way Voice Interaction:**
   - Powered by Web Speech API (`SpeechRecognition` & `SpeechSynthesis`).
   - Listen to words, definitions, and example sentences spoken naturally.
   - Speak your answers and practice your pronunciation hands-free.

2. **📚 Interactive Learning Modes:**
   - **Learn New Word:** Step-by-step introduction of curated vocabulary with phonetic spelling, part of speech, definition, and contextual example.
   - **Pronunciation Practice:** Repeat the target word and get instant speech evaluation.
   - **Active Recall Quiz:** Answer definition-based questions with smart fuzzy matching to test true comprehension.
   - **Spelling Bee:** Audio-first listening and spelling challenge.
   - **Word of the Day:** Fresh daily recommendation to build consistent habits.
   - **Review Mode:** Inspect all words mastered so far.

3. **🎮 Gamification & Retention:**
   - Dynamic streak tracking 🔥
   - Real-time quiz accuracy score
   - Level progression system (Starter → Beginner → Intermediate → Advanced → Master)
   - Local persistence with `localStorage` so progress is never lost.

4. **📱 Responsive & Accessible UI:**
   - Works across desktop and mobile browsers (optimized for Google Chrome & Edge).
   - Seamless fallback between voice mic input and text input.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/nikhilkumarjha62/vocab-voice-agent.git
   cd vocab-voice-agent
   ```
2. Open `index.html` in any modern web browser (Google Chrome or Microsoft Edge recommended for full Web Speech API support).
   Or serve with any static web server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```
