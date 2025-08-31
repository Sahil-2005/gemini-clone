🤖 Gemini Clone

A sleek and minimal AI-powered chatbot interface built with React + Vite, powered by Google's Gemini API. This project replicates the core functionality of Google's Gemini chat experience — allowing users to interact with an AI assistant in real-time.

Think of it as your personal Gemini assistant — lightweight, fast, and responsive. 🚀

✨ Features

🔹 Real-time AI Chat – Send prompts and receive intelligent responses from Gemini
🔹 Recent Chats – View and revisit your previous prompts
🔹 New Chat Functionality – Start a fresh conversation anytime
🔹 Responsive UI – Clean, animated layout inspired by Gemini
🔹 Streaming Text Loader – Smooth word-by-word text reveal
🔹 Prompt Suggestions – Quick suggestions to get started
🔹 Built-in State Management – Context API for managing global state
🔹 Dark-like Theme – Professional look with subtle animations

🛠️ Tech Stack

Frontend: React + Vite

Styling: CSS (Custom)

State Management: React Context API

AI Integration: @google/generative-ai

Linting: ESLint with React plugins

📁 Project Structure
gemini-clone/
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── config/
│   │   └── gemini.js       # Handles Gemini API integration
│   ├── context/
│   │   └── context.jsx     # Manages global chat state
│   ├── components/
│   │   ├── Main/           # Chat UI + interactions
│   │   └── Sidebar/        # Sidebar for new/recent chats
│   ├── assets/             # Image assets used in UI
└── gemini-clone-assets/
    └── assets/             # Duplicate asset directory (can be merged)

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/Sahil-2005/gemini-clone.git
cd gemini-clone

2️⃣ Install Dependencies
npm install

3️⃣ Run the Development Server
npm run dev


The app should now be live at 👉 http://localhost:5173

🔐 Gemini API Setup

This project uses the @google/generative-ai package with an API key.

📌 Important:

Make sure to secure your API key in production. It is currently hardcoded in src/config/gemini.js, which is not safe for deployment.

For local testing, the existing setup will work, but consider using environment variables like .env for security in the future.

📈 Roadmap

 Authentication (login sessions)

 Gemini Pro model integration

 Export chat history

 Voice input support

 Dark mode toggle

🤝 Contributing

Contributions are welcome!

Fork the repo

Create your feature branch:
git checkout -b feature-name

Commit your changes:
git commit -m "Added feature"

Push to the branch:
git push origin feature-name

Open a Pull Request 🚀

🧑‍💻 Author

Sahil Gawade

🌐 Portfolio: sahil-gawade.netlify.app

💼 LinkedIn: linkedin.com/in/sahil-gawade-920a0a242

📌 GitHub: Sahil-2005


📜 License

This project is licensed under the MIT License – feel free to use and modify it for your own projects.

⭐ Support

If you found this project helpful or inspiring:

🌟 Star the repo
🔁 Share it
🧠 Build something cool with it!