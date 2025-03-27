License

This project is for **personal portfolio and job application purposes only**.  
Reproduction, distribution, or commercial use of this code is **not permitted** without explicit permission from the author.

# Morpheus AI
Morpheus is a sleek, fully offline AI chatbot UI powered by [Ollama](https://ollama.com/) and open source large language model. It runs entirely on your local machine — no internet, no API keys, and no external dependencies. Perfect for personal assistants, experimentation, and private LLM workflows.

---

🔧 Features

- 🧠 Powered by `llama2-uncensored` via Ollama
- 💻 100% local — no cloud or external APIs
- 🎨 Apple-style modern UI (light/dark mode)
- 🕒 Timestamps, message styling, and typing animation
- 💬 Voice input (Chrome supported)
- 💾 Download full conversation history
- 🧹 Clear chat session instantly

---

🚀 Getting Started

1. Install [Ollama](https://ollama.com/) and pull the model:
```bash
ollama pull llama2-uncensored
```

2. Clone the repo:
```bash
git clone https://github.com/yourusername/morpheus-ai.git
cd morpheus-ai
```

3. Start Ollama in one terminal:
```bash
export OLLAMA_ORIGINS='*' && ollama serve
```

4. In a second terminal, serve the frontend:
```bash
npx serve .
```
> Or, if Node.js is not installed:
```bash
python3 -m http.server 3000
```

5. Open your browser:
```
http://localhost:3000
```

📁 Project Structure
```
├── index.html        # Main chatbot UI
├── styles            # Optional: externalize CSS
├── README.md         # This file
```


⚙️ Customization
- Change the LLM model in `index.html`
- Update system prompts for different personalities
- Fork and style the UI to match your brand


💡 Use Cases
- Private journaling or thinking assistant
- Offline productivity or writing aid
- Custom domain-specific assistants (e.g., coding, studyaid, Q&A, personal assistant, more secure version of chatgpt)


🤝 Credits
- Built using Ollama and open source large language models
- Inspired by OpenAI's ChatGPT UX
- Developed by Salman Butt (https://github.com/Salman1298)


Ready to go? Fire up Ollama and meet Morpheus.
















© 2025 Salman Butt. All rights reserved.
