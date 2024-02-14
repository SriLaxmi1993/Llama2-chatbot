# Llama 2 Chatbot

The Llama 2 Chatbot is a streamlined, user-friendly application built using Streamlit and powered by the Replicate platform, leveraging the advanced capabilities of the Llama 2 language models. This chatbot is designed to deliver engaging conversational experiences, allowing users to interact with the Llama 2 models in a seamless manner. Below is a guide on how to set up and use the chatbot.

## Features

- **Interactive Chat Interface**: Engage in conversations with a chatbot powered by Llama 2 models.
- **Customizable Model Parameters**: Choose between different Llama 2 models and adjust parameters such as temperature, top_p, and max_length to tailor the conversation according to your preferences.
- **Secure API Token Entry**: Enter your Replicate API token securely in the sidebar to authenticate and start using the chatbot.

## Setup

1. **Clone the repository** containing the Llama 2 Chatbot code to your local machine.
2. **Install dependencies**: Make sure you have Python and Streamlit installed, then install the `replicate` package using pip:

    ```bash
    pip install streamlit replicate
    ```

3. **Run the application**: Navigate to the directory containing the chatbot code and run:

    ```bash
    streamlit run your_script_name.py
    ```

4. **Enter your Replicate API Token**: Access the sidebar in the Streamlit app, enter your Replicate API token in the provided field, and select your desired Llama 2 model and conversation parameters.

## Usage

- **Starting a conversation**: Once you've entered your API token and selected your model and parameters, you can start chatting by typing your messages into the chat input box.
- **Customizing your experience**: Adjust the model and parameters at any time from the sidebar to explore different conversation dynamics.
- **Clearing chat history**: Use the 'Clear Chat History' button in the sidebar to start a new conversation thread.

## Requirements

- Python 3.6 or later
- Streamlit
- Replicate Python package

## Note

- Ensure your Replicate API token is valid. You can create or manage your API tokens at [Replicate's website](https://replicate.com/).
- This chatbot utilizes the open-source Llama 2 LLM model from Meta, showcasing the flexibility and power of modern language models for creating engaging conversational AI experiences.

The Llama 2 Chatbot is a demonstration of how easily accessible AI technologies can be integrated into applications for diverse and interactive user experiences. Enjoy exploring the capabilities of Llama 2 with this simple yet powerful tool.
