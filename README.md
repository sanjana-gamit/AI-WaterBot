🌊 AI-Based Clean Water Predictor

Predict • Visualize • Analyze • Chat with WaterBot

An AI-powered web application built with Streamlit to analyze water quality parameters, predict potability, visualize insights, and interact with an AI helper (WaterBot) using Gemini API.

🚀 Live App: https://ai-waterbot-6zjc6ysfjtqhvfwzajnbfp.streamlit.app/


---

✨ Features

🔍 1. Single Sample Prediction

Enter values for:

pH

Turbidity (NTU)

TDS (mg/L)

Temperature (°C)


The model predicts whether the water is Safe or Unsafe.


---

📁 2. Batch Upload (CSV)

Upload a CSV with columns:

pH, tds, turbidity, temp

App generates predictions for every row.


---

📊 3. Visualization Dashboard

Interactive charts

Parameter distribution

Correlation heatmap

Safe vs Unsafe comparison



---

🤖 4. WaterBot (Chatbot)

AI-powered chatbot using Google Gemini API.

Helps with:

Water safety explanations

Environment awareness

Simple Q&A about clean water



---

🛠️ 5. Remote API Support

You can switch between:

Local ML model

Remote Flask API (if enabled)



---

🧪 Tech Stack

Component	Technology

Frontend	Streamlit
Backend ML	Python, Scikit-learn
Chatbot	Google Gemini API
Visualization	Matplotlib, Seaborn, Plotly
Deployment	Streamlit Cloud



---
🧠 Machine Learning Model

Trained on water quality dataset with features:

pH

Turbidity

TDS

Temperature


Model Output:

0 → Not Safe

1 → Safe


🎯 Purpose

The purpose of this project is to use AI to quickly check whether water is safe to drink. It provides easy prediction, visualization, and an AI chatbot to help users understand water quality and promote clean water awareness.

