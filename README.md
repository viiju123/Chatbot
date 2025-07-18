# Chatbot
A dynamic learning assistant chatbot using OpenRouter API
#  Learning Assistant Chatbot

An interactive web-based chatbot that helps users identify their skill level (Beginner, Intermediate, Advanced) based on what they want to learn — like React, JavaScript, HTML, etc. It then suggests personalized learning resources using AI.



##  Features

- Ask the user what they want to learn
- Dynamically assesses user knowledge through follow-up questions
- Determines the user's current skill level
- Recommends free resources (like MDN, YouTube, FreeCodeCamp)
- Easy to extend with new topics or levels



## Built With

- **HTML**, **CSS**, **JavaScript**
- [OpenRouter](https://openrouter.ai/) API (uses GPT-like models)
- AI Prompt Engineering (custom system prompt for tailored behavior)



##  How It Works

1. User types: `I want to learn React`
2. Bot asks follow-up questions like:
   - Do you know JavaScript?
   - Do you know HTML & CSS?
   - Have you worked with any JS framework?
3. Based on the answers, it analyzes your level and suggests what to learn next, including links to helpful resources.


##  Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/viiju123/Chatbot.git
cd Chatbot
const API_KEY = "your-api-key-here";
