# First ChatBot

A chatbot built using [LangGraph](https://github.com/langchain-ai/langgraph), memory, streaming, and Grok API.

## Features

- **LangGraph:** Orchestrates complex conversational flows with graph-based state management.
- **Memory:** Maintains conversation history for contextually aware interactions.
- **Streaming:** Real-time responses for seamless user experience.
- **Grok API Integration:** Harnesses Grok's AI for enhanced conversational intelligence.

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
   Configure your environment for Grok API access (see `.env.example` if available).

2. **Run the Bot with uvicorn:**
   ```bash
   uvicorn app:app --reload
   ```

3. **Interact:**
   Open your browser or API client to the provided URL (usually http://127.0.0.1:8000) and start chatting with your bot!

## Example

```
You: Hi, what's up?
Bot: Hello! How can I assist you today?
```

## Contributing

Pull requests and suggestions welcome!

## License

This project is licensed under the MIT License.
