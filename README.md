# First ChatBot

A chatbot built using [LangGraph](https://github.com/langchain-ai/langgraph), memory, streaming, Grok API, and advanced integrations.

## Features

- **LangGraph:** Orchestrates complex conversational flows with graph-based state management.
- **Memory:** Maintains conversation history for contextually aware interactions.
- **Streaming:** Real-time responses for seamless user experience.
- **Grok API Integration:** Harnesses Grok's AI for enhanced conversational intelligence.
- **Tools Support:** Integrates a suite of tools, including custom-built operations.
- **Build and Multiply Tool:** Includes custom tools for arithmetic operations like build and multiply.
- **Tavily Web Search:** Integrates with Tavily to provide real-time web search capabilities within conversations.
- **ReAct Agent:** Employs the ReAct paradigm for reasoning and acting in conversations.
- **Human-in-the-Loop:** Allows human intervention when needed for accuracy and safety.
- **MCP Server (Scratch Implementation):** Custom implementation of an MCP (Multi-Component Processing) server for managing workflows and extensibility.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Bhawneet1/First-ChatBot.git
   cd First-ChatBot
   ```

2. **Install Dependencies:**
   Ensure you have Python 3.9+ and pip installed.
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Set Up Environment Variables:**
   Configure your environment for Grok API and Tavily API access (see `.env.example` if available).

2. **Run the Bot with uvicorn:**
   ```bash
   uvicorn app:app --reload
   ```

3. **Interact:**
   Open your browser or API client to the provided URL (usually http://127.0.0.1:8000) and start chatting with your bot!

## Example

```
You: Multiply 8 and 12
Bot: The result is 96.

You: Search "latest AI news"
Bot: [Web search results from Tavily...]
```

## Contributing

Pull requests and suggestions welcome!

## License

This project is licensed under the MIT License.
