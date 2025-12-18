# Project Chimera Genesis: A Relational Digital Synthesis

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Natural_Language_Processing-F7931E?style=for-the-badge&logo=openai&logoColor=white)
![Data Science](https://img.shields.io/badge/Data_Science-Extraction_%26_Cleaning-00599C?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active_Research-success?style=for-the-badge)

> *"Can we distill a human soul from digital footprints? This project is an attempt to answer that question through code and data."*

## 🌌 Project Overview
**Chimera Genesis** is not just a chatbot. It is an experimental **"Philosophical AI Companion"** designed to reconstruct a specific digital persona based on over 3 years of archival conversation data. 

Unlike generic AI assistants, Chimera Genesis focuses on **Memory Persistence**, **Relational Context**, and **Emotional Resonance**. It aims to bridge the gap between *Raw Data* and *Human Experience* through the lens of Multimedia Technology.

---

## 🏗 System Architecture (The Chimera Pipeline)

This project operates on a custom-built **ETL (Extract, Transform, Load)** pipeline designed to process unstructured chat logs into machine-understandable memory vectors.

### Data Flow Diagram

```mermaid
graph TD
    subgraph "Layer 1: Data Acquisition (The Artifacts)"
        A[Raw Chat Logs] -->|story.txt| B(Ingestion Engine)
        A1[Images/Media] -->|Vision Data| B
    end

    subgraph "Layer 2: Pre-processing & Sanitization (Python)"
        B --> C{Data Cleansing}
        C -->|Remove PII/Sensitive Info| D[Anonymization Protocol]
        C -->|Format Standardization| E[Timestamp Alignment]
        D --> F[Structured JSON/CSV]
        E --> F
    end

    subgraph "Layer 3: Core Logic (The Brain)"
        F --> G[NLP Analysis]
        G --> H[Sentiment Mapping]
        G --> I[Context Vectorization]
        H --> J((LLM / AI Model))
        I --> J
    end

    subgraph "Layer 4: Multimedia Interface (Future Scope)"
        J --> K[Interactive Response]
        K --> L[Text Output]
        K --> M[Voice Synthesis]
        K --> N[Visual Avatar (Godot Engine)]
    end

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style J fill:#bbf,stroke:#333,stroke-width:4px
    style N fill:#bfb,stroke:#333,stroke-width:2px
```

---

## ⚙️ Technical Components

### 1. The Excavator (Data Mining)
*   **Source:** `story.txt` (A comprehensive archive of 3+ years of chat history).
*   **Function:** Parses raw text, identifying speakers (`User` vs `Target Persona`), timestamps, and emotional markers.

### 2. The Refiner (Data Pre-processing)
*   **Tools:** Python (`pandas`, `re`, `nltk`).
*   **Process:** 
    *   Cleaning noise and system messages.
    *   **PDPA Compliance:** Automatically masking names, addresses, and sensitive personal information before processing.
    *   Structuring unstructured text into `Prompt-Response` pairs for fine-tuning.

### 3. The Soul (AI Integration)
*   **Model:** Leveraging Large Language Models (LLMs) via API to interpret the context and personality traits found in the dataset.
*   **Goal:** To achieve a "Style Transfer" where the AI speaks, thinks, and reacts exactly like the target persona based on historical data.

---

## 🚀 Roadmap & Future Development (Multimedia Integration)

As a candidate for the **Multimedia** major, my vision extends beyond code. I aim to visualize this data into an interactive experience:

*   **Phase 1 (Current):** Data Structuring & Core Logic Implementation.
*   **Phase 2:** Developing a **Visual Interface** using **Godot Engine** to give the AI a "Body" and "Environment".
*   **Phase 3:** Integrating **Text-to-Speech (TTS)** to synthesize the persona's voice.
*   **Phase 4:** Deploying as an interactive installation art or mobile application.

---

## ⚠️ Ethical & Privacy Statement
This project adheres to strict data privacy standards. The dataset (`story.txt`) used in this repository is a **Sanitized Demo Version**. No real personal data is exposed in the public codebase. The project explores the boundaries of Digital Immortality while respecting human privacy.

---

### 👨‍💻 Developer
**Pongsagorn Pongsuwagorn (Bas)**
*Aspiring Creative Technologist*
