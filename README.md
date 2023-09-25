# Node.js CLI ChatGPT App

The Node.js CLI ChatGPT App is a command-line interface (CLI) chatbot application that interacts with the GPT-3.5 Turbo model from OpenAI. Users can have text-based conversations with the chatbot by typing messages in the terminal.

## Technologies Used

- **Node.js:** The app is built using Node.js, which allows for server-side JavaScript execution.

- **OpenAI API:** It utilizes the OpenAI API to generate responses based on user input.

- **Readline:** The Readline module is used for handling user input in the terminal.

## Features

- **Text-Based Chat:** Users can have text-based conversations with the chatbot by typing messages in the terminal.

- **Real-time Responses:** The chatbot provides responses in real-time, powered by the GPT-3.5 Turbo model.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.

2. Install Node.js and npm (Node Package Manager) if you haven't already.

3. Set up your OpenAI API key:
   - Create an OpenAI account if you don't have one.
   - Generate an API key from the OpenAI platform.
   - Set the API key as an environment variable in your system or replace `process.env.OPENAI_API_KEY` with your API key directly in the `apiKey` field of the `configuration` object in the `index.js` file.

4. Open your terminal and navigate to the project directory.

5. Install project dependencies by running `npm install` or `yarn install`.

6. Start the chatbot application by running `node index.js`.

7. The chatbot will prompt you to type a message. Simply type your message and press Enter to send it to the chatbot.

8. The chatbot will respond with relevant information based on your input.

## Usage

- Type a message in the terminal and press Enter to send your message to the chatbot.

- The chatbot will respond with relevant information based on your input.

- You can have a back-and-forth conversation with the chatbot by typing multiple messages in the terminal.

## Customization

You can customize the behavior of the chatbot by modifying the logic in the `index.js` file. You can also customize the chat interface and styling as needed for your project.
