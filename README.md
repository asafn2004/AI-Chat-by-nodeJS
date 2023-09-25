 ## AI Chat

This is a simple Node.js application that allows you to chat with an AI using OpenAI's GPT-3.5-turbo API.

### Prerequisites

To run this application, you will need the following:

* Node.js installed on your system
* An OpenAI API key

### Installation

1. Clone this repository to your local machine.
2. Install the dependencies by running `npm install`.
3. Create a `.env` file in the project directory and add your OpenAI API key to it. The file should look like this:

```
OPENAI_API_KEY=<your-api-key>
```

### Usage

To start the application, run `node index.js`. You will then be able to chat with the AI by typing messages into the console.

### Code Explanation

The code for this application is relatively simple. The main file, `index.js`, imports the OpenAI API client and creates a new instance of it. It then sets up a readline interface to allow
the user to input messages.
When the user enters a message, the application sends it to the OpenAI API and prints the response to the console.
