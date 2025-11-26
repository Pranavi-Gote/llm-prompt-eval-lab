# 🧪 LLM Prompt Evaluation Lab

This is a side project where I built a system to A/B test different AI prompts. It automatically grades how well an AI summarizes text using data science metrics.

## 🛠️ Tech Stack
* **Python** (Jupyter Notebook)
* **LLM API:** Groq (Llama-3.1-8b)
* **Metrics:** ROUGE Score, BLEU Score, Token Count, Latency (Speed)
* **Data Cleaning:** Regex

## 🚀 What it does
1.  Connects to the Groq API.
2.  Sends 3 different prompt styles (Lazy, Strict, Simple) to the AI.
3.  Cleans the output using Regex to remove hallucinations.
4.  Grades the output against a "Gold Standard" human answer.
5.  Visualizes the winner on a chart.

## 📊 Results
In my experiment, the **"One Sentence Summary"** prompt performed the best, achieving the highest BLEU score with the lowest token usage.
