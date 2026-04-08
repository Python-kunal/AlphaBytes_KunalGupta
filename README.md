# 🍲 Personalized Recipe Generator (AI Fine-Tuned SLM)

---

# 🧠 Team: Alpha Bytes

---

# 👥Team Members:
  - **Team Leader:** Kunal Gupta
  - **Member:** Mridul Agrawal, Vidhi Agrawal

---

## 🚀 Overview
The **Personalized Recipe Generator** is an AI-powered application that generates complete recipes based on user-provided ingredients.

This project was developed during a hackathon under the **AI / SLM Fine-Tuning track**, where we fine-tuned a **Gemma 270M Small Language Model** to generate culturally relevant recipes with a focus on Indian cuisine.

---

## 🎯 Problem Statement
Many users struggle to decide what to cook using available ingredients. Existing solutions lack personalization and cultural relevance.

---

## 💡 Solution
Our model:
- Takes **ingredients as input**
- Generates **complete recipes**
- Provides **step-by-step instructions**
- Focuses on **Indian cooking styles**

---

## 🧠 Model Details
- **Base Model:** Gemma 270M  
- **Type:** Small Language Model (SLM)  
- **Approach:** Fine-tuning  
- **Task:** Ingredient → Recipe generation  

---

## 📂 Dataset Creation
- Scraped recipe websites for:
  - Ingredients
  - Instructions
- Converted data into instruction format:

```json
{
  "input": "rice, tomato, onion, spices",
  "output": "Step-by-step recipe..."
}
