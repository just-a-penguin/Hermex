# Hermex: AI Voice Assistant for E-commerce

Hermex is an advanced AI-powered voice assistant designed to revolutionize the e-commerce shopping experience. By leveraging cutting-edge natural language processing and speech recognition technologies, Hermex provides personalized product recommendations, handles customer inquiries, and facilitates seamless voice-based shopping interactions.

## Features

- **Voice-Activated Interaction**: Engage with customers through natural voice conversations.
- **Personalized Product Recommendations**: Utilize AI to suggest products based on customer preferences and browsing history.
- **Real-time Speech-to-Text**: Accurately transcribe customer voice inputs for processing.
- **Natural Language Understanding**: Comprehend and respond to a wide range of customer queries and commands.
- **Dynamic Text-to-Speech**: Generate human-like voice responses for a more natural interaction.
- **Multi-Voice Personalities**: Switch between different AI personas (e.g., Jerry and Jessica) to suit customer preferences.
- **Cart Management**: Allow customers to add items, view their cart, and checkout using voice commands.
- **Order Status Updates**: Provide real-time updates on order status and shipping information.

## Technology Stack

- **Speech Recognition**: Whisper model for accurate transcription
- **Natural Language Processing**: Meta-Llama/Llama-3.1-8B-Instruct-Turbo for understanding and generating responses
- **Text-to-Speech**: ElevenLabs API for high-quality voice synthesis
- **Vector Database**: Qdrant for efficient similarity search and product recommendations
- **Embedding Model**: Snowflake Arctic Embed for creating text embeddings
- **Audio Processing**: PyDub for audio file manipulation
- **User Interface**: Rich library for creating an engaging console-based UI

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/hermex-ecommerce-assistant.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Create a `.env` file in the root directory
   - Add your API keys for Together AI, ElevenLabs, and Qdrant

4. Download the necessary model files:
   - Whisper model
   - XTTS-v2 model files

5. Prepare your product database:
   - Ensure your product CSV is in the `dataset` folder

## Usage

Run the main script to start the Hermex assistant:

```
python main.py
```

Follow the on-screen prompts to interact with Hermex using your voice.

## Contributing

We welcome contributions to Hermex! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to submit pull requests, report issues, or suggest enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the creators of the open-source libraries and models used in this project.
- Special appreciation to the e-commerce community for inspiring this AI-driven solution.

---

Developed with ❤️ by [Your Name/Organization]
