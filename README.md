# 🎙️ Text-to-Speech Converter Web App

A modern and user-friendly **Text-to-Speech (TTS) web application** that converts your written text into spoken words.  
Built using **HTML, CSS and JavaScript (Web Speech API)** — no external backend required.

---

## 🚀 Features

- Convert any text into speech instantly  
- Choose from multiple available system voices  
- Clean UI with responsive design  
- Works directly in the browser (no installation needed)

---

## 🧠 How It Works

This project uses the **Web Speech API**, specifically the `speechSynthesis` interface of the browser:

1. The user types text inside the textarea  
2. When the page loads, available system voices are fetched  
3. The user selects a voice from the dropdown  
4. On clicking **Listen**, the text is passed to the speech engine and audio is played

Core implementation files:
- HTML UI structure: `index.html` 
- Voice handling + speech execution: `script.js` 
- Styling and layout: `style.css` 

---
