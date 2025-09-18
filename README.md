# Language Translation Tool
**Author:** Mohamed Mostafa

## Features

- 🌐 Support for languages with auto-detection
- 📋 Copy-to-clipboard functionality
- 🔄 Language swap feature
- ⚡ Real-time translation powered by AI
- 📱 Responsive design for all devices

## Supported Languages

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/M-A-Yakout/CodeAlpha_Language-Translation-Tool.git
   cd CodeAlpha_Language Translation Tool
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure environment variables**
   - Copy `.env.example` to `.env` and add your Google Gemini API key
   - Get your API key from: https://aistudio.google.com/app/apikey
   ```bash
   cp .env.example .env
   # Edit .env and replace 'your_api_key_here' with your actual API key
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Access the application**
   Open your browser and visit: http://localhost:5000

## Project Structure

```
CodeAlpha_LanguageTranslation/
├── app.py                  # Flask backend application
├── templates/
│   └── index.html         # Frontend interface
├── requirements.txt       # Python dependencies
├── .env.example          # Environment variables template
├── .gitignore            # Git ignore file
├── LICENSE               # MIT License
└── README.md             # Project documentation
```

## Technology Stack

- **Backend:** Python 3.x + Flask
- **Frontend:** HTML5 + CSS3 + JavaScript
- **AI Service:** Google Gemini API
- **Styling:** Glass-morphism with luxury dark theme

## Author Information

**Mohamed Mostafa** - Full Stack Developer  
Language Translation Tool - 2024

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Author:** Mohamed Mostafa - Full Stack Developer
