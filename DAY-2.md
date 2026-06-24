# Day 02 - Gemini API Integration and AI Interview Question Generator

**Date:** 25 June 2026

## Objective

The objective of today's session was to understand the concept of APIs, integrate the Gemini API into a Python application, and develop a real-world AI-powered project using Flask.

---

## Topics Covered

### 1. Application Programming Interface (API)

An Application Programming Interface (API) is a set of rules and protocols that allows different software applications to communicate with each other.

APIs enable developers to access the functionality of external services without building everything from scratch.

#### Benefits of APIs:
- Faster development
- Access to advanced services
- System integration
- Real-time data exchange
- Scalability

---

### 2. Gemini API

The Gemini API provides access to Google's Large Language Models, enabling developers to build intelligent applications capable of generating human-like responses.

#### Key Features:
- Text generation
- Question answering
- Content creation
- Code generation
- Conversational AI

#### API Workflow:
1. User submits a request.
2. Flask application receives the input.
3. Request is sent to Gemini API using an API key.
4. Gemini model processes the request.
5. Generated response is returned to the application.
6. Results are displayed to the user.

---

### 3. API Key Management

To access the Gemini API, an API key was generated and configured within the application.

#### Purpose of API Key:
- Authentication
- Secure access to services
- Usage tracking
- Access control

The API key was integrated into the Python application using the Google GenAI SDK.

---

## Practical Implementation

### AI Interview Question Generator

A real-world project named **AI Interview Question Generator** was developed using Flask and Gemini API.

The application allows users to enter a specific technology or domain and automatically generates interview questions related to that topic.

#### Example:

**Input:**


**Output:**
- What is Python?
- Explain Python decorators.
- What are Python generators?
- Difference between List and Tuple.
- Explain exception handling in Python.

---

## Technologies Used

### Python

Python was used as the primary programming language for developing the application logic and handling API requests.

### Flask

Flask is a lightweight Python web framework used to create web applications.

#### Responsibilities:
- Handling user requests
- Managing routes
- Rendering HTML templates
- Connecting frontend and backend

### HTML

HTML was used to design the user interface and collect user input.

### Gemini API

Gemini API was responsible for generating interview questions dynamically based on user input.

---

## Project Architecture

User Input (Technology Name)
↓
HTML Form
↓
Flask Backend
↓
Gemini API Request
↓
AI Processing
↓
Generated Interview Questions
↓
Display on Web Page

---

## Learning Outcomes

- Understood the concept and importance of APIs.
- Learned how API keys are generated and used securely.
- Integrated Gemini API with Python applications.
- Learned the fundamentals of Flask web development.
- Built a real-world AI-powered application.
- Understood request-response architecture.
- Explored how Large Language Models can be used in practical business applications.

---

## Challenges Faced

- Installing required Python packages.
- Configuring the development environment.
- Understanding API authentication.
- Connecting Flask routes with frontend forms.

---

## Conclusion

Today's session focused on practical implementation of Generative AI technologies. By integrating Gemini API with Flask, a functional AI Interview Question Generator was successfully developed. This project demonstrated how Large Language Models can be integrated into web applications to create intelligent and interactive solutions.
