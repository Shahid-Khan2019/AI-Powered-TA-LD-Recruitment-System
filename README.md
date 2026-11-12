# AI-Powered-TA-LD-Recruitment-System
AI-powered recruitment and selection system for Teaching Assistants (TAs) and Lab Demonstrators (LDs), featuring automated shortlisting, AI interviews, RAG chatbot assistance, audio/video analysis, and intelligent candidate evaluation.

# AI-Powered TA & LD Recruitment System

> An intelligent recruitment and selection platform designed to automate the hiring process for **Teaching Assistants (TAs)** and **Lab Demonstrators (LDs)** in academic institutions.

## 📌 Project Overview

The **AI-Powered TA & LD Recruitment System** is a Final Year Project developed to automate and improve the recruitment process of Teaching Assistants and Lab Demonstrators in universities.

Traditional TA and LD recruitment involves manual application screening, candidate shortlisting, interviews, and responding to repetitive student queries. This process can be time-consuming and creates a significant administrative burden for faculty.

Our system introduces automation and Artificial Intelligence into the recruitment workflow through:

- Automated application processing
- Intelligent candidate shortlisting
- AI-powered interviews
- Audio and video analysis
- AI-generated interview questions
- Automated answer verification
- Coding question evaluation
- RAG-powered chatbot assistance
- Role-based dashboards for students, teachers, and administrators

The goal is to make the recruitment process more **efficient, transparent, scalable, and intelligent**.

---

# 🎯 Problem Statement

The traditional recruitment process for Teaching Assistants and Lab Demonstrators requires faculty members to manually:

- Review student applications
- Check eligibility criteria
- Shortlist candidates
- Conduct interviews
- Evaluate candidate performance
- Respond to repetitive student queries

This consumes valuable time and can make managing a large number of applications difficult.

The AI-Powered TA & LD Recruitment System aims to automate these processes and reduce the workload on academic staff while helping identify suitable candidates.

---

# 🚀 Key Features

## 👨‍🎓 Student Portal

Students can:

- Register and log into the system
- Create and manage their academic profile
- View available TA and LD positions
- Apply for positions
- Track application status
- Participate in AI-powered interviews
- Answer course-related questions
- Attempt coding questions
- Interact with the AI chatbot

---

## 👨‍🏫 Teacher Portal

Teachers can:

- View assigned courses
- Request Teaching Assistants for courses
- View allotted TAs and LDs
- View relevant applications
- Access AI chatbot assistance

---

## 👨‍💼 Admin Portal

Administrators can:

- Launch recruitment cycles
- Manage users and applications
- Monitor candidate selection
- Review shortlisted candidates
- Resolve allocation conflicts
- Approve allocations
- Generate reports
- Send notifications

---

# 🤖 AI-Powered Modules

## 1. Automated Candidate Shortlisting

The system evaluates candidate applications based on predefined eligibility and selection criteria.

This helps automate the initial screening and shortlisting process.

---

## 2. AI-Powered Interview

Shortlisted TA candidates can participate in an AI-powered interview.

The interview process evaluates candidates using multiple components, including:

- Audio analysis
- Video/sentiment analysis
- Course-related questions
- Answer verification
- Coding questions
- Overall candidate scoring

---

## 🎙️ Audio Analysis

Candidate audio responses are analyzed to evaluate characteristics such as:

- Confidence
- Tone
- Clarity

The project integrates AI and audio-processing technologies such as:

- Wav2Vec2
- Librosa

---

## 🎥 Video Sentiment Analysis

The system analyzes candidate video responses to extract visual and sentiment-related information during the interview process.

---

## 🧠 AI Question Generation

Interview questions can be generated dynamically based on the relevant course material.

This enables the system to generate course-specific questions for candidates during the interview.

---

## ✅ Answer Verification

Candidate responses are evaluated using automated answer verification techniques to assess their understanding of course-related concepts.

---

## 💻 Coding Question Evaluation

The system supports coding-based interview questions.

Candidates can write and submit code through the interview interface, where their solutions can be evaluated as part of the overall interview score.

---

## 💬 RAG-Powered AI Chatbot

The system includes an AI chatbot to assist users with:

- Frequently asked questions
- Eligibility requirements
- Application deadlines
- Course information
- Application-related queries

The chatbot uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information and provide context-aware responses.

---

# 🏗️ System Architecture

The system follows a **Three-Tier MVC Architecture**.

## 1️⃣ Presentation Layer

**Technologies:**

- HTML
- CSS
- JavaScript

### Components:

- Student Portal
- Faculty Dashboard
- Admin Panel
- Interview Interface
- Chatbot Interface

---

## 2️⃣ Application Layer

**Technology:**

- Flask
- Python

### Components:

- Authentication and Authorization
- Application Processing
- Candidate Filtering and Ranking
- Automated Selection Logic
- AI Interview Controller
- AI Question Generation
- Audio Analysis
- Video Sentiment Analysis
- Answer Verification
- Code Evaluation
- RAG Chatbot
- Notification Services
- REST APIs

---

## 3️⃣ Data Layer

**Technology:**

- MySQL

The database manages:

- User information
- Student profiles
- Applications
- Courses
- TA/LD positions
- Interview responses
- Candidate scores
- Selection results
- Chatbot knowledge base
- Audit logs

---

# 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, Flask |
| Database | MySQL |
| AI/ML | TensorFlow, NLP Libraries |
| Audio Analysis | Wav2Vec2, Librosa |
| Chatbot | Large Language Models (LLMs) |
| Retrieval | RAG |
| APIs | REST APIs |
| Computer Vision | Video/Sentiment Analysis Models |

> Note: The exact libraries and versions should be updated according to the final implementation.

# 🔐 User Roles

The system supports three primary roles:

| Role | Responsibilities |
|---|---|
| Student | Apply for TA/LD positions and participate in interviews |
| Teacher | Request and manage TA/LD allocations |
| Admin | Manage the complete recruitment process |

---

# 📊 Recruitment Workflow

```text
Student Registration
        ↓
Profile Creation
        ↓
TA/LD Application
        ↓
Eligibility Evaluation
        ↓
Automated Shortlisting
        ↓
AI Interview (TA Candidates)
        ↓
Audio + Video + Answer + Coding Evaluation
        ↓
Final Candidate Score
        ↓
Admin Review & Allocation
        ↓
Notification & Reporting
```

---

# 🔒 Security Features

The system is designed with:

- Role-Based Access Control
- User Authentication
- Authorization
- Input Validation
- Activity Logging
- Audit Records

---

# 📈 Future Improvements

Possible future enhancements include:

- Improved AI candidate ranking
- Advanced fairness and bias monitoring
- Enhanced interview proctoring
- More advanced emotion and sentiment analysis
- Cloud deployment
- Email and SMS notification integration
- Mobile application support
- Advanced analytics dashboard

---

# 👥 Project Team

| Name | Registration Number | Responsibility |
|---|---|---|
| **Shahid Ullah** | 22I-2019 | Frontend Development, AI Chatbot, Audio Analysis, Question Generation & Answer Verification |
| **Muhammad Salman** | 22I-2027 | Report work, Documentation, UI/UX, Forms & Testing |
| **Muhammad Hammad** | 22I-1944 | AI/ML, Model Training, Authentication, Database, APIs & Auto-Selection Logic |

---

# 🎓 Academic Information

**Project:** AI-Powered TA and LD Recruitment System

**Department:** Data Science

**University:** National University of Computer and Emerging Sciences (FAST-NUCES)

**Session:** 2022–2026

**Supervisor:** Mr. Sohail Abbas

---

# 📄 License

This project was developed as an academic **Final Year Project (FYP)**.

For academic and educational purposes only.

---

## ⭐ Acknowledgment

We would like to thank our supervisor and the faculty members of the Department of Data Science for their guidance and support throughout the development of this Final Year Project.

---

⭐ If you find this project useful, consider giving the repository a star.
