# Project Chimera Genesis: A Relational Digital Synthesis

![Status](https://img.shields.io/badge/Status-Research_%26_Design-blue?style=for-the-badge&logo=appveyor)
![Type](https://img.shields.io/badge/Type-Interactive_Media_Art-purple?style=for-the-badge)
![Core](https://img.shields.io/badge/Core-Data_Driven-green?style=for-the-badge)

> *"What if we could distill a soul from the digital footprints we leave behind?"*

## 🌌 Project Overview
**Chimera Genesis** is an experimental project that explores the intersection of **Memory**, **Technology**, and **Human Interaction**. It aims to reconstruct a digital persona from unstructured personal data (chat logs, images, and audio) collected over 3 years.

This is not just a chatbot. It is a **"Philosophical AI Companion"** designed to simulate a specific human relationship, preserving the emotional context and shared history between the user and the digital entity.

---

## 🧠 Core Concept: Digital Archaeology
The project treats historical data not as mere text, but as **"Digital Fossils"**. By excavating these fossils, we can reconstruct the personality, tone, and memories of a lost connection.

*   **Subject:** "Da" (A digital representation of a past friend)
*   **Source:** Real-world chat logs (anonymized) from 2021-2024
*   **Goal:** To create an interactive experience where the user can converse with this "memory" in a meaningful way.

---

## 🏗️ System Architecture & Data Flow

This diagram illustrates how raw data is transformed into an interactive experience.

```mermaid
graph TD
    subgraph "Phase 1: Data Acquisition (The Past)"
        A[Raw Data Sources] -->|Extract| B(Text Logs 'story.txt')
        A -->|Extract| C(Audio & Images)
    end

    subgraph "Phase 2: Processing Core (The Present)"
        B -->|Python Script| D{Data Cleansing & Structuring}
        D -->|Normalize| E[Structured Dataset (JSON/CSV)]
        E -->|Fine-tune| F[AI Model (LLM)]
    end

    subgraph "Phase 3: Interactive Experience (The Future)"
        F -->|API| G[Interactive Interface]
        G -->|Input/Output| H((User))
        
        style G fill:#f9f,stroke:#333,stroke-width:2px
        style H fill:#bbf,stroke:#333,stroke-width:2px
    end
```

### **Process Breakdown:**

1.  **Ingestion:** Collecting raw conversation data from various platforms.
2.  **Sanitization:** Removing Sensitive PII (Personally Identifiable Information) to ensure privacy and data ethics.
3.  **Synthesis:** Training/Fine-tuning a Language Model to mimic the specific speech patterns and memories of the subject.
4.  **Visualization:** (Future Goal) Developing a visual interface using **Godot Engine** or **Unity** to give the AI a "Body" and "Environment".

---

## 🛡️ Data Ethics & Privacy
This project strictly adheres to **PDPA** guidelines. All data used is:
*   **Consented:** Obtained with permission from the subject.
*   **Anonymized:** Real names, addresses, and sensitive details are stripped before processing.
*   **Local-First:** The core dataset is stored locally to prevent leakage.

---

## 🚀 Future Roadmap (Why Multimedia?)
The current phase focuses on the **Back-end (Logic & Data)**. The next crucial step is to develop the **Front-end (Media & Experience)**, which aligns with my goal to study **Multimedia Technology**.

*   [x] Data Collection (100% Complete)
*   [x] Data Structuring (60% Complete)
*   [ ] **Visual Avatar Design (0% - To be developed at MSU)**
*   [ ] **Voice Synthesis (TTS) (0% - To be developed at MSU)**
*   [ ] **Interactive Environment (0% - To be developed at MSU)**

---

### 💻 Tech Stack
*   **Language:** Python
*   **Tools:** VS Code, Google AI Studio
*   **Future Tools:** Godot Engine, Blender, Stable Diffusion

---
*Developed by **Bas616** as a part of the Admission Portfolio for Multimedia, MSU.*
