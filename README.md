# Portfolio-Chatbot# Peter's Custom Chatbot

Welcome to Peter's Custom Chatbot! This project integrates a **Voiceflow AI chatbot** into a web page, optimized for embedding in **Google Sites** or other personal portfolio websites.

## 📌 Features
- **Interactive AI Chatbot** powered by Voiceflow
- **Optimized for Google Sites** (works via iFrame)
- **Custom Welcome Message**: "🚀 Welcome! Click below to interact with Peter's custom chatbot!"
- **Modern UI Design** with shadow effects and a responsive layout

## 🚀 Deployment & Hosting
Since Google Sites blocks inline JavaScript, **this chatbot must be hosted externally** before embedding. Here’s how:

### 1️⃣ **Host on GitHub Pages (Recommended)**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/custom-chatbot.git
   ```
2. Navigate into the directory:
   ```bash
   cd custom-chatbot
   ```
3. Enable GitHub Pages:
   - Go to **Settings → Pages**
   - Select "Deploy from `main` branch"
   - GitHub will provide a live URL (e.g., `https://yourusername.github.io/custom-chatbot`)

### 2️⃣ **Host on Netlify (Drag & Drop Method)**
1. Go to [Netlify](https://app.netlify.com/)
2. Upload the `index.html` file
3. Copy the generated URL

### 3️⃣ **Host on Replit (Quick Hosting)**
1. Create a new HTML Repl at [Replit](https://replit.com/)
2. Paste the code from `index.html`
3. Click **Run** and get your hosted URL

## 📥 Embedding in Google Sites
Once hosted, embed the chatbot using an iFrame:
```html
<iframe src="https://yourhostedchatbot.com"
        width="100%" height="550px"
        style="border:none; border-radius:10px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);">
</iframe>
```

## 🛠️ Technologies Used
- **HTML/CSS** for structure & styling
- **JavaScript** for chatbot integration
- **Voiceflow API** for chatbot functionality
- **GitHub Pages / Netlify / Replit** for hosting

## 🤝 Contributions
Feel free to fork and customize this chatbot for your own portfolio! If you find improvements, open a **pull request** or submit an **issue**.

## 📄 License
MIT License. You are free to use, modify, and distribute this project.

