
# AI Agent

This project is an AI-powered agent designed to assist with research by automatically gathering, summarizing, and saving information on a given topic. It integrates with various tools to provide a comprehensive, structured output.

## Key Features
#### Automated Research: 
The agent can perform research on any topic provided by the user.

#### Tool Integration: 
It utilizes a suite of tools, including a web search tool (DuckDuckGo), a Wikipedia search tool, and a custom file-saving tool to handle different research needs.

#### Structured Output: 
It delivers a clean, structured ResearchResponse that includes a summary, references, and a record of the tools used.

#### Output Persistence: 
The research results are automatically saved to a text file for easy access and record-keeping.

## How to Set It Up
Clone the Repository: Get a local copy of the project.

## Run Locally

#### Clone the Repository: 
Get a local copy of the project.
```bash
  git clone <repository_url>
  cd <project_directory>
```

#### Install Dependencies: 
Set up a Python virtual environment and install all the required libraries.
```bash
  python -m venv venv
  source venv/bin/activate
  pip install -r requirements.txt
```

#### Configure API Keys: 
Create a .env file in the project's root directory and add your necessary API keys, like the one for OpenAI.
```bash
  OPENAI_API_KEY="your_api_key"
```

#### How to Use
Run the script: Execute the main Python file from your terminal.
```bash
  python research_assistant.py
```

#### Enter Your Query: 
The script will prompt you for a research topic.

#### Get the Results: 
The agent will then use its tools to research the topic and provide a structured summary in the console and a saved text file.

## Support
For support, email jainmayukh@gmail.com

## Project Structure
`research_assistant.py`: The core script containing the agent's logic and execution flow.

`tools.py`: A separate file that defines the functions for the search and save tools.

`.env`: Your file for storing sensitive API keys.

`research_output.txt`: The text file where all research outputs are saved.

## Contribution
We welcome contributions! Please feel free to open issues or submit pull requests with any improvements or new features.
