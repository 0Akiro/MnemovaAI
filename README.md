# MnemovaAI - Chat Application with OpenAI GPT-3.5 Turbo

## Overview
Welcome to MnemovaAI, an interactive chat application powered by OpenAI's GPT-3.5 Turbo model. This repository provides a seamless way to engage in natural language conversations with a virtual assistant. Users can input text messages and receive AI-generated responses, making it an excellent tool for various applications.

## Prerequisites
Before you embark on your chat journey with MnemovaAI, ensure that you have the following prerequisites in place:

1. **Python**: MnemovaAI relies on Python, so make sure you have it installed on your system. If not, you can easily obtain it from the [official Python website](https://www.python.org/downloads/).

2. **OpenAI API Key**: To access the GPT-3.5 Turbo model, you'll need an API key from OpenAI. If you don't have an API key, you can create one by following these steps:

   a. **Sign Up for OpenAI**: If you haven't already, sign up for an account on the [OpenAI platform](https://platform.openai.com/).

   b. **Create an API Key**: Once you're logged in, navigate to your dashboard and create a new API key. You may need to follow their documentation for specific instructions.

   c. **Replace API Key**: After obtaining your API key, make sure to replace `'your_api_key'` in the code with your actual API key.

Now you have all the prerequisites in place to get started with MnemovaAI.

## Installation
To set up and run MnemovaAI, follow these straightforward installation steps:

1. **Clone or Download**: You can either clone this repository or download the code as a ZIP file and then extract it to your local machine.

2. **Install Dependencies**: Open your terminal, navigate to the project directory, and install the required Python packages using pip:
   ```bash
   pip install openai
   ```

Now that you have MnemovaAI ready to roll, let's dive into using it:

1. **Create a Prompt**: Define your initial conversation prompt in a file named `prompt.txt`. This serves as the introduction to the conversation.

2. **Run the Application**: Execute the chat application with the following command:
   ```bash
   python MnemovaAI.py
   ```

3. **Conversation Interaction**: The application will prompt you for text inputs. Begin the conversation by typing your message and hitting Enter. The AI assistant will respond with its generated text.

4. **Exiting the Conversation**: To exit the conversation, simply type ```exit```  and press Enter. This will conclude the conversation and close the application.

5. **Clearing Conversation History**: To wipe the conversation history and start anew, type ```deconv``` and press Enter. This will clear the entire conversation history.

## Conversation History
MnemovaAI keeps a record of the entire conversation in a text file named `conversation.txt`. You can review this file to track the progress of your conversation and refer back to it as needed. Enjoy conversing with MnemovaAI!
