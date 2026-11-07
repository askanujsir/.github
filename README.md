# About sammpad.ai

## Overview
**sammpad.ai** is an innovative, web-based AI study companion designed specifically for **CBSE Class 11–12 Computer Science (Python)** students and educators. Our goal is to deliver a **low-cost, teacher-controlled, and syllabus-grounded** tool that enhances classroom teaching, formative assessment, and self-paced board exam preparation in full alignment with the **National Education Policy (NEP) 2020**.

---

## Core Features & Functionality

### 1. Syllabus-Restricted AI Tutor
- **Strictly Grounded:** Answers student queries exclusively within the prescribed CBSE Class 11–12 Computer Science syllabus (covering Python, SQL, Computer Networks, and Data Structures).
- **Polite Redirection:** Politely redirects off-syllabus or out-of-bounds questions without unnecessary refusals.

### 2. PYQ Practice & Interactive Quizzes
- **Authentic Board Formats:** Offers real past-year question (PYQ) quizzes, including Multiple Choice Questions (MCQs), Assertion-Reason, output prediction, and code-fix problems.
- **Instant Marking & Feedback:** Features immediate scoring, answer key verification, and AI-driven step-by-step explanations.
- **Proper Code Rendering:** Python code snippets are formatted with dedicated code syntax, accurate indentation, and clear structure.

### 3. Smart Practice Agent & Board-Style Question Generation
- **Competency-Based Personalization:** Tracks session practice history to identify weak topics and recommend targeted exercises.
- **AI-Generated Questions:** Creates brand-new practice questions matching the exact difficulty, format, and style of CBSE board exams.
- **Executed Code Verification:** Automatically executes generated Python code snippets to verify answer correctness before displaying them to students.

### 4. Comprehensive Teacher Tools
- **Question Bank Audit & Extension:** Provides automated tools for paper-to-quiz conversion, allowing teachers to review and approve extracted questions prior to database inclusion.
- **Analytics & Insights:** Equipped with topic classification, question clustering (TF-IDF + KMeans), coverage auditing, and association rule mining to identify topics students frequently struggle with together.

### 5. Interactive Python Code Sandbox
- Allows students to write and safely run Python code directly within the browser with built-in time limits.
- Provides **AI Hint** and **AI Explain** features designed to guide problem-solving without revealing direct solutions.

---

## Tech & AI Architecture

- **User Interface:** Built using Streamlit (Multipage Web Application framework).
- **Coding Assistant:** Designed, refactored, and tested in partnership with Claude (Anthropic).
- **Flexible LLM Back-ends:** Supports drop-in model swapping (Groq API using `openai/gpt-oss-20b` by default, alongside Google Gemini `gemini-3.1-flash-lite`).
- **Machine Learning & NLP:** Powered by Python 3.11, `scikit-learn`, `sentence-transformers`, `pandas`, and `pypdf`.
- **Privacy & Security:** Features local/session-based state storage with no permanent server tracking, and environment-variable API key configurations.
