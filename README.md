# Interview Prep Buddy 🎯

**Interview Prep Buddy** is an AI-driven tool designed to help you sharpen your interview skills with real-time, personalized feedback — all while keeping your data private through 100% local processing.

## 🔍 Features at a Glance

- **🎤 Speech Recognition with Whisper**  
  Accurately transcribes your spoken answers for deeper analysis.

- **🤖 Intelligent Feedback via Ollama**  
  Evaluates your response for:
  - Content relevance and clarity  
  - Logical structure and coherence  
  - Overall delivery and tone

- **🔊 Audio Feedback with gTTS**  
  Converts AI-generated feedback into speech so you can listen and learn.

- **🎯 Role-Specific Question Generation**  
  Generates targeted interview questions based on your chosen job role.

- **🖥️ Intuitive UI with Streamlit**  
  Clean and responsive interface for a smooth practice experience.

- **🔒 100% Local AI Processing**  
  No cloud dependencies — all models run locally for privacy and performance.

---

## ⚙️ Requirements

Make sure you have the following before you get started:

- Python 3.7 or newer  
- Ollama installed and configured  
- A working microphone  
- Adequate system resources to run local AI models smoothly

---

## 🛠️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/sarmishra/Interview-Prep-Buddy.git
cd Interview-Prep-Buddy
```

2. **Create and activate a virtual environment:**

```bash
python -m venv env

# Activate it
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate
```

3. **Install Ollama:**

```bash
# Linux:
curl -fsSL https://ollama.com/install.sh | sh

# macOS/Windows:
# Download the installer from https://ollama.com/download
```

4. **Download the required Ollama model:**

```bash
ollama pull mistral
```

5. **Install Python dependencies:**

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

## 🚀 How to Use

1. **Ensure the Ollama service is running** in the background.
2. **Launch the app:**

```bash
streamlit run main.py
```

3. **Get started:**
   - Enter the job role you're preparing for
   - Receive a tailored interview question
   - Click the microphone to record your answer
   - Stop recording when you're done
   - Review the transcription of your answer
   - Read or listen to the AI-generated feedback
   - Optionally download the feedback audio for later review

---

## 🖼️ Preview

![Landing Page](https://github.com/sarmishra/Interview-Prep-Buddy/blob/main/landing_page_interview_prep_budy.png)
