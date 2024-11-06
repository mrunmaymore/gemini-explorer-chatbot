# Gemini Explorer Chatbot 🤖

A powerful and interactive chatbot leveraging Google's Gemini Pro LLM through Vertex AI, with a sleek Streamlit interface.

## Overview 🌟

Gemini Explorer Chatbot is an AI-powered conversational interface that demonstrates the capabilities of Google's Gemini Pro Large Language Model. Built with Python and Streamlit, it provides an intuitive chat experience while maintaining conversation history and context.

## Features ✨

- 💬 Real-time interactive chat interface
- 🔄 Persistent conversation history
- 🎯 Context-aware responses
- 🎨 Clean and responsive UI
- 🔒 Secure environment variable handling
- 😊 Emoji-enhanced interactions
- 📱 Cross-platform compatibility

## Prerequisites 📋

Before you begin, ensure you have:

- Python 3.11 or higher installed
- Google Cloud Account with active billing
- Vertex AI API enabled
- Google Cloud Service Account with necessary permissions
- Basic knowledge of terminal/command line operations

## Installation 🚀

1. **Clone the Repository**
```bash
git clone https://github.com/mrunmaymore/gemini-explorer-chatbot.git
cd gemini-explorer-chatbot
```

2. **Set Up Virtual Environment**
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# For Windows
.\venv\Scripts\activate
# For macOS/Linux
source venv/bin/activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure Environment Variables**
Create a `.env` file in the project root:
```env
GOOGLE_CLOUD_PROJECT_ID=your_project_id
GOOGLE_APPLICATION_CREDENTIALS=path/to/your/credentials.json
```

## Project Structure 📁

```
gemini-explorer-chatbot/
├── .env                  # Environment variables
├── .gitignore           # Git ignore file
├── geminiexplorer.py    # Main application file
├── requirements.txt     # Python dependencies
└── README.md           # Project documentation
```

## Usage 💻

1. **Start the Application**
```bash
streamlit run geminiexplorer.py
```

2. **Access the Interface**
- Open your browser and navigate to `http://localhost:8501`
- The chatbot will introduce itself as ReX
- Start chatting by typing in the message input field

## Configuration ⚙️

### Google Cloud Setup

1. Create a new project in Google Cloud Console
2. Enable Vertex AI API
3. Create a service account and download credentials
4. Set up environment variables with credentials path

### Application Settings

The chatbot uses the following default configurations:
- Temperature: 0.4 (controls response creativity)
- Model: gemini-pro
- Location: us-central1

## Troubleshooting 🔧

Common issues and solutions:

1. **Authentication Errors**
- Verify your Google Cloud credentials path
- Ensure service account has proper permissions
- Check if environment variables are loaded correctly

2. **Installation Issues**
- Upgrade pip: `python -m pip install --upgrade pip`
- Verify Python version: `python --version`
- Check virtual environment activation

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments 🙏

- Google Cloud Platform and Vertex AI team
- Streamlit framework developers
- The open-source community

## Support 💪

If you encounter any issues or have questions, please:
- Open an issue in the repository
- Check existing issues for solutions
- Review the troubleshooting guide

---

Made with ❤️ by Mrunmay More

Last Updated: 11/6/2024