# 🎓 SDG 4 AI Study Assistant: Intelligence for Quality Education

[![UN SDG 4](https://img.shields.io/badge/UN_SDG-4:_Quality_Education-blue.svg)](https://sdgs.un.org/goals/goal4)
[![Platform](https://img.shields.io/badge/Built_With-Botpress_Cloud-blueviolet.svg)](https://botpress.com/)
[![Status](https://img.shields.io/badge/Status-Live-success.svg)](#)

## 🚀 Live Implementation
**Deploy the solution and interact with the AI Assistant here:**  
👉 [**Access Live Demo**] (https://cdn.botpress.cloud/webchat/v3.6/shareable.html?configUrl=https://files.bpcontent.cloud/2026/05/12/08/20260512084933-UWA0LE8G.json)
---

## 📌 Executive Summary
This project addresses **UN Sustainable Development Goal 4 (Quality Education)** by leveraging Generative AI to provide personalized, 24/7 academic support. The system is engineered to bridge the gap in educational resources, offering a "Private AI Tutor" experience that adapts its complexity to the student's academic level.

## 🏗️ System Architecture & Logic Flow
The core of this assistant is a robust **Visual State-Machine**. Unlike a simple chatbot, this system manages conversation states and context injection to ensure high-signal, accurate educational output.

### Technical Logic Flow:
![System Architecture]
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/f9c49cb2-035b-44ec-afae-b0d2805cf8bc" />


### The AI Pipeline:
1.  **State Initialization:** Capture user metadata (`user_grade`, `user_subject`).
2.  **Contextual Mapping:** Stores user parameters in workflow variables to build a persistent session state.
3.  **Prompt Engineering:** Dynamically injects variables into a specialized LLM instruction set.
4.  **Generative Output:** Produces grade-appropriate explanations tailored specifically to STEM curricula.

## 🛠️ Technical Stack & Innovations
*   **Architecture:** Visual Flow Orchestration (Botpress Cloud).
*   **AI Engine:** Generative Pre-trained Transformer (GPT) models via AI Task nodes.
*   **Dynamic Variables:** Utilizes `{{workflow.user_grade}}` and `{{workflow.user_subject}}` for context-aware processing.
*   **UI/UX:** Responsive Webchat integration for cross-platform accessibility.

## 📁 Repository Structure
*   **`SDG-AI-chatbot.bpz`**: Full source code export (Binary Botpress file).
*   **`README.md`**: Technical documentation and deployment guide.

## 🎯 Key Educational Impact
*   **Adaptive Complexity:** Concepts in Physics or Math are explained differently to a 9th grader vs a 12th grader.
*   **STEM Optimization:** Specialized in solving and explaining core concepts in Physics, Math, and Chemistry.
*   **Scalable Impact:** Designed for zero-cost deployment to help students in underserved regions.

---
**Technical Head / Developer:** Amit Waghmare  
*Milestone Project for LeapNext Internship.*
