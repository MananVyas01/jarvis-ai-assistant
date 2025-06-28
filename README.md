# 🤖 JARVIS - Advanced AI Assistant

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Eel](https://img.shields.io/badge/Eel-GUI-orange.svg)](https://github.com/ChrisKnott/Eel)

**JARVIS** is an advanced AI-powered voice assistant with real-time search capabilities, content generation, image creation, and system automation features. Built with Python and a modern web interface.

## ✨ Features

- 🗣️ **Voice Recognition & Text-to-Speech** - Natural conversation with AI
- 🔍 **Real-time Search** - Get up-to-date information from the internet  
- 🎨 **Image Generation** - Create images from text descriptions
- 💻 **System Automation** - Control your computer with voice commands
- 📝 **Content Generation** - Write letters, essays, code, and more
- 🌐 **Web Interface** - Modern, responsive UI with dark theme
- 🔧 **Multi-API Support** - Integrates with Groq, Cohere, and Hugging Face

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- API keys for AI services (see setup below)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MananVyas01/jarvis-ai-assistant.git
   cd jarvis-ai-assistant
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements1.txt
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Edit `.env` file and add your API keys:
   ```env
   GroqAPI=your_groq_api_key_here
   CohereAPI=your_cohere_api_key_here
   HuggingFaceAPI=your_huggingface_api_key_here
   ```

4. **Run JARVIS**
   ```bash
   python main.py
   ```

5. **Open your browser** and go to `http://localhost:44444`

## 🔑 API Keys Setup

### Required APIs:

1. **Groq API** (Free tier available)
   - Go to: https://console.groq.com/
   - Used for: Main AI chat functionality

2. **Cohere API** (Free tier available)  
   - Go to: https://cohere.ai/
   - Used for: Advanced language processing

3. **Hugging Face API** (Free tier available)
   - Go to: https://huggingface.co/settings/tokens
   - Used for: Image generation and AI models

## 📱 Usage

### Voice Commands
- "Hello JARVIS" - Start conversation
- "Search for [topic]" - Real-time web search
- "Generate an image of [description]" - Create images
- "Open [application]" - System automation
- "Write a [letter/essay] about [topic]" - Content generation

### Web Interface
- **Home**: Main chat interface with voice controls
- **Settings**: Configure API keys and preferences
- **Voice Recognition**: Click microphone to start voice input

## 🏗️ Architecture

```
JARVIS/
├── Backend/           # Python modules
│   ├── Automation.py  # System automation & image generation
│   ├── Chatbot.py     # Main chatbot logic
│   ├── ChatGpt.py     # Alternative AI model support
│   ├── RSE.py         # Real-time search engine
│   ├── TTS.py         # Text-to-speech functionality
│   └── Extra.py       # Utility functions
├── web/              # Frontend files
│   ├── home.html     # Main interface
│   ├── settings.html # Configuration page
│   ├── spider.html   # Main container
│   └── eel.js        # Python-JavaScript bridge
└── main.py           # Entry point
```

## 🛠️ Technologies Used

- **Backend**: Python, Eel (GUI framework)
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **APIs**: Groq, Cohere, Hugging Face
- **Voice**: Web Speech API, Edge-TTS
- **Real-time Communication**: WebSockets via Eel

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Security Notice

- Never commit your `.env` file with real API keys
- Use `.env.example` as a template
- Keep your API keys secure and rotate them regularly

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- Thanks to the developers of Groq, Cohere, and Hugging Face for their APIs
- Eel framework for seamless Python-Web integration
- Edge-TTS for high-quality text-to-speech

## 📞 Support

If you have any questions or issues, please open an issue on GitHub.

---

**Developed by [Manan Vyas](https://github.com/MananVyas01)**