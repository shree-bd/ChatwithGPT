
# ChatbotAI with OpenAI's ChatGPT

A simple Python-based chatbot application using OpenAI's ChatGPT API. This chatbot engages in conversation and provides responses based on the prompt given by the user.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Configuration](#configuration)
- [Example](#example)
- [License](#license)

## Overview
ChatbotAI with ChatGPT is a lightweight chatbot built in Python that leverages the OpenAI ChatGPT API to generate conversational responses. It listens to user inputs and responds until the user decides to exit. This project serves as a great starting point for building more advanced chat applications with OpenAI's capabilities.

## Features
- Real-time conversation with OpenAI's ChatGPT API.
- Simple command-line interface.
- Easy to extend and customize.

## Setup
Follow these steps to set up and run the chatbot locally:

### Prerequisites
- Python 3.7 or higher
- An OpenAI API key (available with a Pro version account)

### Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shree-bd/ChatwithGPT.git
   cd ChatbotAI-OpenAI
   ```

2. **Create a Virtual Environment (optional but recommended):**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows, use .venv\Scripts\activate
   ```

3. **Install Required Packages:**
   ```bash
   pip install openai
   ```

4. **Set Your API Key:**
   Open `main.py` and replace `"YOUR_API_KEY"` with your actual OpenAI API key:
   ```python
   openai.api_key = "YOUR_API_KEY"
   ```

   Alternatively, you can set the API key as an environment variable:
   ```bash
   export OPENAI_API_KEY="YOUR_API_KEY"  # On Windows use 'set' instead of 'export'
   ```

## Usage
To start the chatbot, run the following command in the terminal:

```bash
python main.py
```

### Stopping the Chatbot
To end the conversation, type any of the following: `quit`, `exit`, or `bye`.

## Configuration
In `main.py`, you can adjust parameters like model and prompt type to customize the chatbot's behavior as supported by the OpenAI API.

## Example
Here's an example interaction with ChatbotAI:
```plaintext
You: Hello
Chatbot: Hello! How can I assist you today?

You: Tell me a joke.
Chatbot: Why did the computer go to the doctor? Because it had a virus!

You: bye
Chatbot: Goodbye! Have a great day!
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
