# Interactive AI assistant with MCP-enabled tool access and memory

![](https://github.com/HarichandanaGonuguntla/Interactive-AI-Assistant-with-MCP-Enabled-Tool-Access-and-Memory/blob/main/mcp.png)

This project demonstrates how to build an interactive AI assistant/chatbot that leverages the MCP (Model Control Protocol) ecosystem for tool-augmented conversations, with built-in conversation memory for better context and continuity.

**Key Features:**

**Conversational AI Agent:** Uses MCPAgent and MCPClient to manage conversations and interact with external tools/servers.
**Memory-Enabled Chat:** The agent maintains conversation history, allowing for more context-aware and natural interactions.
**Tool Integration via MCP Servers:** The project is configured to connect to various MCP servers (such as Playwright for browser automation, Airbnb, and DuckDuckGo search) via a JSON config file, enabling the agent to perform actions like web browsing, searching, and more.
**LLM Integration:** Utilizes a large language model (e.g., Llama-3 via Langchain and Groq) to generate responses and drive the conversation.
**Environment Configuration:** Uses environment variables (via .env and dotenv) for API keys and other sensitive settings.

