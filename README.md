# 🥗 NutriWise — AI-Powered Nutrition Advisor

NutriWise is an AI-powered web application that delivers **personalized diet**, **restaurant**, and **workout** recommendations based on user health metrics and preferences. Built using **Flask**, **Tailwind CSS**, and powered by the **Grok Large Language Model (LLM)**, it provides intelligent, localized, and adaptive suggestions.

## 🚀 Features

- 🎯 Personalized diet plans based on age, gender, weight, height, region, allergies, and more
- 🍴 Restaurant recommendations with precise locations (area, street, city)
- ☀️ AI-curated breakfast & 🌙 dinner options
- 💪 Custom workout plans
- 🌗 Light & Dark theme toggle for better accessibility
- 🧠 Powered by **Grok LLM** for real-time, adaptive insights

## 🧠 Powered by Grok LLM

NutriWise integrates **Grok**, a cutting-edge large language model, to:
- Understand nuanced user preferences
- Recommend meals aligned with dietary needs and allergies
- Suggest nearby restaurants with hyper-local context
- Customize workouts based on goals and body profile

The backend uses structured prompt engineering to generate meaningful, formatted results from Grok for seamless front-end rendering.

## 🛠 Tech Stack

- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Backend**: Python, Flask
- **LLM Integration**: Grok API
- **Templating**: Jinja2

##📂 Project Structure
```bash
nutriwise/
│
├── static/              # CSS, JS, images
├── templates/           # HTML templates
│   ├── index.html       # Input form
│   └── result.html      # Output page
├── app.py               # Flask backend logic
├── requirements.txt     # Dependencies
└── README.md            # This file
```

## 🧪 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/nutriwise.git
cd nutriwise

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask server
python app.py


