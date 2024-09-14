# Philosophy Discussant

Philosophy Discussant is a Streamlit-based application that uses AI to facilitate engaging philosophical discussions and debates. It leverages advanced language models to explore various philosophical topics, theories, and approaches, adapting to different discussion modes and user preferences.

## Features

- Interactive philosophical discussions with AI
- Customizable philosophical branches and approaches
- Multiple discussion modes (Open Dialogue, Socratic Method, Devil's Advocate)
- Support for various AI models (OpenAI and Ollama)
- Conversation saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/philosophy-discussant-streamlit100.git
   cd philosophy-discussant
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3. Enter your name and configure your philosophical discussion preferences in the sidebar:
   - Select philosophical branches of interest
   - Choose philosophical approaches
   - Set the discussion mode

4. Start sharing your philosophical thoughts or asking questions in the chat interface

5. Engage in a philosophical discussion with the AI, exploring ideas and arguments

## Customization

- Modify the `PHILOSOPHICAL_BRANCHES` and `PHILOSOPHICAL_APPROACHES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus
- Add new discussion modes or modify existing ones to suit different philosophical inquiry styles

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
