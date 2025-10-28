# Orbit-Chatbot 🚀  
A lightweight web chatbot powered by Google’s Generative Language API.

## 🔍 Overview  
Orbit-Chatbot is a simple and clean web interface where users type a message and receive a smart response via a large-language model. Built with vanilla HTML, CSS and JavaScript, it’s easy to deploy and customise.

## 🧩 Features  
- Minimal, clean UI with chat bubbles for user + bot.  
- Dark / modern theme built with CSS.  
- Uses the Google Generative Language API for responses.  
- Lightweight: no heavy frameworks required.  
- Easy to customise: swap out models, update styling, extend functionality.

## 📦 Technologies  
- HTML5  
- CSS3  
- JavaScript (ES6)  
- Google Generative Language API – the backend AI.

## 🚀 Setup & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/arpittak027/Orbit-Chatbot.git
   cd Orbit-Chatbot
````

2. Obtain your API key from Google.
3. In your JavaScript file (e.g., `main.js` or `script.js`), update:

   ```js
   const API_KEY = "YOUR_API_KEY_HERE";
   const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/YOUR_MODEL_NAME:generateContent?key=${API_KEY}`;
   ```

   Replace `YOUR_MODEL_NAME` with a valid model name supported by your key.
4. Open `index.html` in your browser. Start chatting!

## 🗂 Project Structure

```
Orbit-Chatbot/
│
├─ index.html        ← Main entry point  
├─ style.css         ← Styles & theme  
├─ script.js         ← Chat UI logic & API calls  
└─ (assets/)         ← Optional: logos, images, icons  
```

## 🔧 Customisation & Extending

* Change the UI layout or colours via `style.css`.
* Add avatars, timestamps, animations in the chat UI.
* Upgrade the backend: add a Node.js/Express server to hide the API key, log chats, implement sessions.
* Store chat history in `localStorage` or a database.
* Deploy to a static host (GitHub Pages, Netlify, Vercel) or a full stack server.

## ✅ Things to Note

* Make sure your model supports the `generateContent` method.
* Avoid exposing your API key in a public repo—use environment variables or a backend proxy for production.
* Monitor usage to avoid hitting rate limits/costs with the API.

## 📜 License

Licensed under the **MIT License** — feel free to use, modify and distribute.

## 🙋 Author

Created by [@arpittak027](https://github.com/arpittak027).
If you build something cool with this, I’d love to hear about it!

```





