

# Ebook-LLaMA2-Chatbot

This is a Streamlit-based chatbot app built using LLaMA2, which allows users to interact with multiple LLaMA2 API endpoints hosted on Replicate. The chatbot maintains session chat history and enables users to configure model hyperparameters directly from the app interface. The app also includes an option to use GPT-based chat models.

[**Live Demo**](https://vinayak-ebook-llama2-bot.streamlit.app/)

## Features

- **Multi-Endpoint Support**: Select from multiple LLaMA2 API endpoints available on Replicate.
- **Session Chat History**: Keeps track of the conversation within the session.
- **Hyperparameter Configuration**: Easily configure model settings from the sidebar to customize responses.
- **User-Friendly Interface**: Simple, clean design with a responsive input field for chat interaction.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher
- Streamlit installed (`pip install streamlit`)
- Access to LLaMA2 API endpoints on Replicate (sign up [here](https://replicate.com/) if you need access)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ebook-llama2-chatbot.git
   cd ebook-llama2-chatbot
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables for the LLaMA2 and GPT API keys:

   ```bash
   export LLAMA2_API_KEY="your_llama2_api_key"
   export GPT_API_KEY="your_gpt_api_key"
   ```

## Usage

1. Start the Streamlit app:

   ```bash
   streamlit run app.py
   ```

2. In the app interface:
   - **Select an API Endpoint**: Choose a LLaMA2 model endpoint from the sidebar.
   - **Configure Model Hyperparameters**: Adjust settings like temperature, max tokens, etc., from the sidebar.
   - **Chat**: Type your question in the input field at the bottom of the app and press enter to interact with the chatbot.

## Key Components

- **`app.py`**: Main application file for the Streamlit app.
- **`utils.py`**: Contains utility functions for interacting with the LLaMA2 and GPT APIs.
- **`requirements.txt`**: Lists the required Python libraries to run the app.

## API Endpoints

- The app is configured to use multiple LLaMA2 API endpoints on Replicate. You can add or modify these endpoints in the configuration section of the code.
- Support for GPT models is also integrated.

## Additional Resources

- For more details and documentation, visit: [Coding4Vinayak](https://coding4vinayak.github.io)

## Contributing

Contributions are always welcome! If you have suggestions for improving the app, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



