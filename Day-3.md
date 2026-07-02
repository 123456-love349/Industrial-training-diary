Day 3 – Introduction to APIs, MCP and Transformer Algorithm
Objective

The objective of today's session was to understand how AI applications communicate with external services using APIs and the role of MCP (Model Context Protocol). We also explored the Transformer architecture, which is the foundation of modern Large Language Models.

1. API (Application Programming Interface)

An API is a communication interface that allows different software applications to exchange information with each other.

Instead of building every functionality from scratch, developers can use APIs to access external services like:

Weather information
Payment gateways
AI models
Maps
Databases
Authentication services
Working of API
Client
   ↓
API Request
   ↓
Server
   ↓
Process Request
   ↓
API Response

Example:

A chatbot needs current weather.

Instead of storing weather data itself, it sends a request to a Weather API.

The API returns:

Temperature
Humidity
Wind speed
Forecast

The chatbot simply displays the result.

Types of APIs
REST API
GraphQL API
SOAP API
WebSocket API

REST API is the most commonly used API in AI projects.

2. MCP (Model Context Protocol)

Model Context Protocol (MCP) is an open protocol that enables AI models to securely communicate with external tools, databases, applications, and APIs.

Instead of giving the AI direct access to every system, MCP acts as a standardized communication layer.

Why MCP is Needed

Without MCP:

AI → Custom Integration → Database
AI → Custom Integration → Email
AI → Custom Integration → Calendar

Many custom integrations are required.

With MCP:

AI
 ↓
MCP Server
 ↓
Database
Calendar
Email
Files
Browser
APIs

One protocol can connect multiple tools.

Benefits
Standardized communication
Better security
Easy tool integration
Reusable architecture
Faster AI development
3. MCP Project

We created a basic MCP project to understand:

MCP Server
MCP Client
Tool Registration
Request Handling
Response Generation

The project demonstrated how an AI model can call different tools through MCP instead of directly interacting with services.

4. Transformer Algorithm

The Transformer is the deep learning architecture behind modern Large Language Models like ChatGPT, Qwen, Llama and Gemini.

Unlike older RNN models, Transformers process words in parallel, making training much faster.

Main Components
Encoder

Reads and understands the input sentence.

Decoder

Generates the output sentence or response.

Self-Attention

Self-Attention allows every word to understand the importance of other words in the sentence.

Example:

"The animal didn't cross the street because it was tired."

The model understands that it refers to "animal."

Multi-Head Attention

Multiple attention layers analyze different relationships simultaneously.

Positional Encoding

Since Transformers process all words together, positional encoding tells the model the order of words.

Applications of Transformers
ChatGPT
Machine Translation
Text Summarization
Image Captioning
Question Answering
Code Generation
Speech Recognition
Learning Outcome

By the end of the day, I understood:

API fundamentals
API communication flow
MCP architecture
Tool integration using MCP
Transformer architecture
Self-Attention mechanism
Practical implementation through a small MCP project
