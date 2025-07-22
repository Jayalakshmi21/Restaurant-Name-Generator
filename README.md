# 🍽️ Restaurant Name Generator

A fun and interactive web application that generates creative restaurant names and menu items based on different cuisines using AI-powered language models.

## 🌟 Features

- **Interactive Web Interface**: Built with Streamlit for a clean, user-friendly experience
- **Multiple Cuisines**: Support for Indian, Italian, Mexican, Arabic, and American cuisines
- **AI-Powered Generation**: Uses OpenAI's language models via LangChain for creative suggestions
- **Dynamic Menu Items**: Generates relevant menu items based on the restaurant name
- **Real-time Results**: Instant generation with a simple cuisine selection

## 🚀 Demo

Select a cuisine from the sidebar and watch as the AI generates a unique restaurant name and matching menu items!

## 🛠️ Technologies Used

- **[Streamlit](https://streamlit.io/)** - Web application framework
- **[LangChain](https://python.langchain.com/)** - LLM application framework
- **[OpenAI API](https://openai.com/api/)** - AI language model
- **Python** - Programming language
- **Git** - Version control

## 📋 Prerequisites

Before running this application, make sure you have:

- Python 3.7 or higher
- An OpenAI API key ([Get one here](https://platform.openai.com/api-keys))
- Git (for cloning the repository)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jayalakshmi21/Restaurant-Name-Generator.git
   cd Restaurant-Name-Generator
   ```

2. **Install required packages**
   ```bash
   pip install langchain langchain-community langchain-openai python-dotenv streamlit
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the project root directory:
   ```bash
   touch .env
   ```
   
   Add your OpenAI API key to the `.env` file:
   ```
   API_KEY=your_openai_api_key_here
   ```
   
   ⚠️ **Important**: Never commit your `.env` file to version control. It's already included in `.gitignore`.

## 🚀 Usage

1. **Run the application**
   ```bash
   streamlit run main.py
   ```

2. **Open your browser**
   
   The application will automatically open in your default browser at `http://localhost:8501`

3. **Generate restaurant names**
   - Select a cuisine from the sidebar dropdown
   - Watch as the AI generates a creative restaurant name
   - Explore the suggested menu items for your restaurant

## 📁 Project Structure

```
Restaurant-Name-Generator/
│
├── main.py                 # Streamlit web application
├── langchain_helper.py     # LangChain integration and AI logic
├── .env                    # Environment variables (not tracked)
├── .gitignore             # Git ignore file
└── README.md              # Project documentation
```

## 🔍 How It Works

1. **User Selection**: User selects a cuisine type from the Streamlit sidebar
2. **Chain Processing**: The application uses LangChain's SequentialChain to:
   - Generate a creative restaurant name based on the cuisine
   - Create relevant menu items based on the generated restaurant name
3. **Display Results**: The results are displayed in an organized format on the web interface

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Add more cuisine types
- [ ] Include restaurant theme generation
- [ ] Add export functionality for generated content
- [ ] Implement user feedback system
- [ ] Add restaurant logo generation
- [ ] Support for multiple languages

## ⚠️ Important Notes

- **API Costs**: This application uses OpenAI's API, which may incur costs based on usage
- **Rate Limits**: Be mindful of OpenAI's rate limits
- **Security**: Never expose your API key in code or public repositories

## 🐛 Troubleshooting

### Common Issues

1. **ModuleNotFoundError**: Make sure all required packages are installed
   ```bash
   pip install langchain langchain-community langchain-openai python-dotenv streamlit
   ```

2. **API Key Error**: Ensure your `.env` file is properly configured with a valid OpenAI API key

3. **Rate Limit Exceeded**: Check your OpenAI account billing and usage limits

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Jayalakshmi** - [GitHub Profile](https://github.com/Jayalakshmi21)

## 🙏 Acknowledgments

- OpenAI for providing the language model API
- LangChain team for the excellent framework
- Streamlit team for the amazing web app framework
- The open-source community for inspiration and support

---

⭐ **If you found this project helpful, please give it a star!** ⭐
