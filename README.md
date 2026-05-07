<div align="center">

# 🚀 CodeReview — PR Health Analyzer

### AI-powered NLP system for analyzing Pull Request quality

[![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)]()
[![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red?style=for-the-badge&logo=streamlit)]()
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge)]()
[![NLP](https://img.shields.io/badge/NLP-Powered-green?style=for-the-badge)]()

---

## 🌐 Live Demo

### 🔗 **[Try the Deployed App Here](YOUR_DEPLOYED_LINK_HERE)**

</div>

---

# 📌 Overview

**CodeReview** is an NLP-powered Pull Request Health Analyzer that evaluates the overall quality of a pull request using Machine Learning and Natural Language Processing techniques.

The system analyzes multiple aspects of a PR including:

- ✅ Variable & function naming quality
- ✅ Inline code comment quality
- ✅ Commit message effectiveness
- ✅ Review comment sentiment/tone

Based on these analyses, the system generates:
- Individual module scores
- Detailed flags/issues
- Actionable improvement suggestions
- An overall PR Health Score

---

# ✨ Features

## 🧠 1. Name Quality Module
Analyzes variable names, function names, and identifiers used in the code.

### Detects:
- Vague identifiers (`temp`, `x`, `data`, etc.)
- Non-descriptive naming conventions
- Poor readability patterns

### Output:
- Name Quality Score
- Flagged identifiers
- Better naming suggestions

---

## 💬 2. Comment Quality Module
Evaluates the usefulness and readability of inline code comments.

### Detects:
- Poor grammar
- Sparse comments
- Redundant comments that simply restate code

### Output:
- Comment Quality Score
- Grammar warnings
- Suggestions for meaningful documentation

---

## 📝 3. Commit Quality Module
Analyzes commit messages to determine clarity and professionalism.

### Detects:
- Vague commit messages
- Missing imperative verbs
- Overly long commit descriptions

### Output:
- Commit Quality Score
- Commit formatting issues
- Better commit writing suggestions

---

## 😊 4. Sentiment Analysis Module
Performs NLP-based sentiment analysis on PR review comments.

### Detects:
- Aggressive review tone
- Negative phrasing
- Non-constructive feedback

### Output:
- Review Tone Score
- Toxic/aggressive review indicators
- Constructive feedback suggestions

---

# ⚙️ How It Works

The user provides:
- Source code
- Inline comments
- Commit message
- Review comments from the pull request

The system processes all inputs through the 4 NLP modules and generates:

```text
Module Scores
        ↓
Issue Detection
        ↓
Suggestions
        ↓
Overall PR Health Score
