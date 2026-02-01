# Awareness Training System against Phishing with LLM

# PhishingChatbot – CyberPhil  
AI-based Phishing Awareness Training (Proof of Concept → Research Prototype)

PhishingChatbot (**CyberPhil**) is an **interactive phishing awareness training system** developed as part of an FHNW research and coursework project.  
The project demonstrates how **chatbots and (later) Large Language Models (LLMs)** can be used to simulate realistic phishing scenarios and actively train users to recognize and respond to social-engineering attacks.

This repository represents the **technical Proof of Concept (PoC)** that bridges **academic research** and **practical implementation**.

---

## Why This Project Exists

Phishing remains one of the most effective cybersecurity attack vectors because it targets the **human factor** rather than technical vulnerabilities.  
Traditional awareness training is often **passive, static, and non-interactive**, which limits learning effectiveness.

This project addresses that gap by:
- simulating **realistic phishing scenarios**
- embedding a chatbot directly into a web environment
- providing **immediate, contextual feedback**
- supporting **interactive learning instead of passive instruction**

The PoC validates the feasibility of chatbot-based phishing simulations and serves as a foundation for adaptive, AI-driven training systems.

---

## Research Context & Publication

This project was developed in the context of academic research at **FHNW** and evolved beyond coursework into a **peer-reviewed research contribution**.

### Academic Paper (Published)

**Title:**  
*An Adaptive Phishing Awareness Training Environment Based on LLMs and Interactive Learning*

**Publisher:** IEEE  
**Conference:** 2025 IEEE 9th Forum on Research and Technologies for Society and Industry (RTSI)  
**Authors:** Kapischan Sriganthan, Felix Härer  

The paper presents:
- the theoretical foundation
- a structured literature review
- the training concept
- the chatbot architecture
- and the evaluation of this Proof of Concept

The PoC implemented in this repository directly supports and demonstrates the concepts discussed in the paper.

IEEE Xplore: https://ieeexplore.ieee.org/document/11212360
---

## Project Evolution (Versions)

This project exists in **three evolutionary stages**:

### Version 1 – Initial Proof of Concept (This Repository)
- Rule-based chatbot (intents.json)
- Flask backend
- Simulated website environment
- Static phishing scenarios
- Focus: **feasibility & interaction flow**

📌 Stored on FHNW GitLab due to storage and project constraints:  
https://gitlab.fhnw.ch/kapischan.sriganthan/phishingchatbot.git

---

### Version 2 – Improved Design (Paper Submission Version)
- UI/UX improvements
- Refined phishing scenarios
- Better visual integration of the chatbot
- Adapted for academic paper submission and demonstration

📌 Stored on FHNW GitLab due to storage and project constraints:  
https://gitlab.fhnw.ch/kapischan.sriganthan/tobit_poc.git

---

### Version 3 – LLM-Based Research Prototype (Conference Version)
- Conceptual integration of **Large Language Models**
- Adaptive feedback and contextual responses
- Research-grade prototype for conference presentation
- Focus: **interactive learning & adaptivity**

https://github.com/fhaer/adaptive-phishing-awareness-training.git
---

## What This Repository Contains

This repository contains the **first functional Proof of Concept**, intentionally kept simple and transparent to demonstrate:

- chatbot-website integration
- phishing simulation logic
- user interaction and feedback flow
- architectural feasibility without LLM dependency

The chatbot **CyberPhil** acts as:
- a guide
- a trainer
- and a feedback mechanism during phishing simulations

---

## Features

- Interactive phishing simulations
- Embedded chatbot (CyberPhil)
- Immediate feedback on user actions
- Rule-based intent handling via `intents.json`
- Web-based UI (HTML, CSS, JavaScript)
- Flask backend
- Lightweight and reproducible PoC architecture

---

## Technologies Used

- Python 3.8+
- Flask
- NLTK
- Torch (foundational ML support)
- HTML / CSS / JavaScript

---
