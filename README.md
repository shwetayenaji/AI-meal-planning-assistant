# 🍲 AI Meal Planning Assistant

A smart assistant designed to help Indian students and bachelors plan meals based on available ingredients, time, budget, and cooking skills. It provides quick, personalized, and achievable Indian meal suggestions—especially for beginners—with clear recipes, cost estimates, and spice levels.

---

## 🧠 What It Does

- ✅ Suggests meals based on what you have (e.g., rice, dal, eggs, etc.)
- ✅ Adjusts for your skill level (beginner-friendly focus)
- ✅ Considers budget and time constraints
- ✅ Keeps track of user preferences across chats
- ✅ Offers a variety of Indian dishes—dry, gravy, bread-based

---

## 🎯 Target Audience

- Indian college students in hostels or PGs  
- Young working professionals cooking independently  
- Anyone with limited kitchen setup and basic ingredients  

---

## 🧩 Agent Architecture

### 🧾 1. Input Understanding
Extracts structured data like:
- Ingredients
- Cooking skill
- Time/Budget constraints
- Meal type
- Dietary preferences

### 🧠 2. State Tracker
Maintains user profile with:
- Skill level
- Preferred ingredients
- Past likes/dislikes
- Kitchen setup
- Budget range

### 🧭 3. Task Planner
Makes planning decisions based on:
- What user has
- Time/budget constraints
- Skill level
- History (feedback + preferences)

### 📝 4. Output Generator
Generates friendly, well-structured responses:
- 2-3 meals per reply
- Includes time, spice level, ingredients, cost
- Beginner-friendly instructions
- Friendly tone with pro tips

---

## 📊 Example Use Case

**User**: "I have rice, dal, and onions. Need something quick for dinner."  
**Assistant**:  
- 🍽️ Onion Dal Fry + Rice (⏰ 20 mins | 🌶️ | ₹30)  
- 🍽️ Masala Khichdi (⏰ 25 mins | 🌶️🌶️ | ₹35)  
- Includes cooking steps, cost, tip, and a follow-up question

---

## 📁 Project Files

- `AI_Meal_Assistant_Final_Report.pdf` – Complete project design and reflection
- `README.md` – Overview and usage

---

## 🔍 Reflection Highlights

- Most fun: Designing prompt layers that feel human and helpful
- Challenge: Making suggestions both spicy *and* beginner-friendly
- Learned: Prompt layering + memory = powerful customization

---

## 💡 Future Ideas

- Add voice input for mobile users
- Suggest shopping lists based on regular usage
- Support regional languages (Hindi, Tamil, etc.)
- Recommend leftovers or meal prep ideas

---

## 🧪 Try It With These Prompts

```txt
"I'm a beginner, have ₹100, and 20 minutes. I only have bread and eggs."
"I want a really spicy lunch. I have rice, dal, and onions."
"Give me something quick and healthy for dinner."

