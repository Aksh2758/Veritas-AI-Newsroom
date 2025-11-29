# 🏛️ Veritas: The Adversarial AI Newsroom
### *A Multi-Agent System for Combatting Misinformation*

<img width="1619" height="760" alt="Screenshot 2025-11-30 003752" src="https://github.com/user-attachments/assets/d7161bf9-9de0-450b-a7eb-ca28ff8d22bf" />

## 🚀 Project Overview
In the age of viral rumors and AI hallucinations, trusting a single AI response is risky. **Veritas** is an agentic workflow that simulates a human newsroom. Instead of one AI answering a question, three distinct AI agents work together—and against each other—to find the truth.

## 🎯 The Architecture
Veritas uses a **Sequential Multi-Agent Architecture** powered by **Google Gemini 1.5 Flash**:

1.  **🕵️ The Researcher:** Gathers factual evidence using Google Search Grounding.
2.  **🛡️ The Skeptic:** The "Devil's Advocate." It actively tries to debunk the Researcher's findings, looking for logical fallacies and missing context.
3.  **📰 The Editor:** Synthesizes the debate into a final, unbiased verdict.

## 🛠️ Tech Stack
*   **Language:** Python
*   **LLM:** Google Gemini 1.5 Flash
*   **Tools:** Google Search Grounding
*   **Visualization:** Custom HTML/CSS Dashboard (IPython Display)

## 📂 Project Structure
*   `veritas.ipynb`: The complete source code, agent logic, and test cases.

## 🎥 Video Demo
[Click here to watch the project demo](https://www.loom.com/share/17dafb7d9a04446b9b1f4a4225361186)

## 🏆 Use Case
This project was built for the **Google AI Agents Intensive** capstone to demonstrate how adversarial agent flows can reduce hallucination in Large Language Models.
