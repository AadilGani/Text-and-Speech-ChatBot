# AI Document Assistant 🤖

An intelligent document search and chat application that supports both text and voice interactions, built with Streamlit and LangChain.

## 🌟 Features

- **Multi-Modal Input**: Support for both text and voice input
- **Speech-to-Speech Conversations**: Full audio conversation capabilities
- **Document Search**: Semantic search across your document collection
- **Real-time Chat**: Interactive conversational interface
- **Analytics Dashboard**: Track usage and conversation metrics
- **Customizable Voice**: Multiple voice options for audio responses
- **Advanced Settings**: Configurable search and response parameters

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Language Models**: Azure OpenAI, Ollama
- **Embeddings**: Nomic Embed
- **Database**: PostgreSQL
- **Speech Services**: Azure Whisper (STT), Azure TTS
- **Vector Store**: PGVector

## 📋 Prerequisites

- Python 3.11+
- PostgreSQL database
- Azure OpenAI API access
- Ollama server running

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/AadilGani/Text-and-Speech-ChatBot.git
```

2. Create a virtual environment:
```bash
python -m venv emb
.\emb\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your environment variables:
```bash
# Create .env file with your credentials
AZURE_OPENAI_KEY=your_key_here
AZURE_OPENAI_ENDPOINT=your_endpoint_here
POSTGRES_CONNECTION=your_connection_string
```

## 🎯 Usage

1. Start the application:
```bash
streamlit run streamlitollama.py
```

2. Access the web interface at `http://localhost:8501`

3. Choose your input method (text/audio)

4. Start chatting with your documents!

## 🔧 Configuration

### Voice Settings
Available voices:
- alloy: Neutral, versatile voice
- echo: Clear, balanced voice
- fable: Warm, expressive voice
- onyx: Deep, authoritative voice
- nova: Professional, polished voice
- shimmer: Bright, energetic voice

### Search Parameters
- Number of similar documents (1-10)
- Minimum similarity score (0.0-1.0)
- Temperature for response creativity

## 📊 Features Breakdown

1. **Document Search**
   - Semantic similarity search
   - Configurable result count
   - Minimum similarity threshold

2. **Chat Interface**
   - Real-time streaming responses
   - Conversation history
   - Message timestamps

3. **Voice Integration**
   - Speech-to-Text conversion
   - Text-to-Speech synthesis
   - Multiple voice options

4. **Analytics**
   - Message counts
   - Question tracking
   - Conversation metrics

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Streamlit for the amazing web framework
- LangChain for the language model tooling
- Azure for AI services
- PostgreSQL for vector storage

## 📞 Support

For support, email a.gani@myw.ai or open an issue in the repository.
