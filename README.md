# AI Agent

A research assistant AI agent built with LangChain that can perform web searches, access Wikipedia, and generate structured research responses.

## Features

- **Web Search**: Uses DuckDuckGo for web searches
- **Wikipedia Integration**: Access Wikipedia articles for research
- **Structured Output**: Generates research responses in a structured format using Pydantic
- **File Saving**: Save research results to text files
- **Multiple LLM Support**: Compatible with OpenAI GPT and Anthropic Claude models

## Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd AI-Agent
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
cp example.env .env
# Edit .env with your API keys
```

## Usage

Run the main script:
```bash
python main.py
```

## Project Structure

- `main.py` - Main application with agent setup and execution
- `tools.py` - Custom tools for web search, Wikipedia, and file operations
- `requirements.txt` - Python dependencies
- `example.env` - Environment variables template

## Dependencies

- langchain
- langchain-openai
- langchain-anthropic
- langchain-community
- pydantic
- python-dotenv

## Environment Variables

Create a `.env` file with the following variables:
```
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
```

## License

This project is open source and available under the MIT License.
