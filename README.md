# Automated-Meeting-Minutes-from-Audio-LLM-Speech-to-Text
# 📌 Automated Meeting Minutes from Audio  
**LLM + Speech-to-Text Powered AI System**

## 📖 Overview  
This project is an end-to-end **Generative AI pipeline** that converts raw meeting audio into **structured meeting minutes**, including:
- Full transcript  
- Meeting summary  
- Decisions taken  
- Owner-tagged action items  

It helps teams automatically generate business-ready documentation from long meeting recordings using **Speech-to-Text** and **Large Language Models (LLMs)**.

---

## 🎯 Problem Statement  
In most organizations, meeting notes are:
- Manually written  
- Incomplete  
- Inconsistent  
- Time-consuming  

Important decisions and action items are often missed or forgotten.  
This project automates the entire process by converting **audio → insights** using AI.

---

## 🧠 Solution Architecture  

Meeting Audio
↓
Whisper (Speech-to-Text)
↓
Transcript
↓
LLaMA-3 (LLM)
↓
Structured Meeting Minutes
(Summary, Action Items, Decisions, Owners)


---

## 📂 Dataset  
The system works on:
- Meeting audio files (MP3, WAV, M4A, etc.)  
- Long-form conversations (30+ minutes supported)  

The audio is automatically segmented and transcribed before being sent to the LLM.

---

## 🛠️ Technologies Used  

| Component | Tool |
|--------|------|
| Speech-to-Text | Whisper (HuggingFace) |
| Large Language Model | LLaMA-3 |
| Model Optimization | 4-bit Quantization (BitsAndBytes) |
| Deep Learning Framework | PyTorch |
| Transformers | HuggingFace Transformers |
| Environment | Google Colab / Jupyter Notebook |
| Hardware | NVIDIA T4 GPU |

---

## 🚀 Key Features  

- Converts long meeting audio into clean transcripts  
- Generates business-ready summaries  
- Extracts **action items with owners**  
- Identifies key decisions  
- Uses memory-efficient LLM inference (4-bit quantization)  
- Works for long recordings without breaking context  

---

## 📊 Output Example  

Meeting Summary:

Discussed Q1 sales targets and hiring plan

Action Items:

John → Prepare sales report

Sarah → Schedule recruitment interviews

Decisions:

Increase marketing budget by 15%


---

## ▶ How to Run  

1. Open the notebook  

2. Upload a meeting audio file when prompted  

3. Run all cells  

4. The notebook will:
- Transcribe the audio  
- Generate summary, action items, and decisions  

---

## 💡 Use Cases  

- Corporate meetings  
- Client calls  
- Interviews  
- Project reviews  
- Stand-ups  
- Training sessions  

---

## 👤 Author  

**Palak Gupta**  
AI Engineer | Data Scientist  
GitHub: https://github.com/Palakds  

