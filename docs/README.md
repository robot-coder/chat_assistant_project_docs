# Chat Assistant Documentation

## Overview
This documentation provides an overview of the Chat Assistant project, including installation instructions, usage examples, API references, and architectural overview.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/robot-coder/chat_assistant_project.git
   cd chat_assistant_project
   ```
2. Install the required dependencies for the backend:
   ```bash
   cd chat_assistant_project_backend
   pip install -r requirements.txt
   ```
3. Install the required dependencies for the frontend:
   ```bash
   cd chat_assistant_project_frontend
   npm install
   ```

## Usage Examples
- Start the backend server:
   ```bash
   uvicorn main:app --reload
   ```
- Open the frontend in your browser:
   ```bash
   open index.html
   ```

## API Reference
- **POST /chat**: Send a message to the chat assistant.
  - Request Body:
    ```json
    {
      "message": "Hello, how can I help you?"
    }
    ```
  - Response:
    ```json
    {
      "response": "I am here to assist you!"
    }
    ```

## Architectural Overview
The Chat Assistant consists of a frontend JavaScript interface and a backend Python FastAPI server. The frontend communicates with the backend to send and receive messages, allowing for a continuous conversation.

## Deployment
The Chat Assistant is deployed on Render.com. You can access it [here](https://render.com).

## Extensions
- Support for text file uploads to add to the prompt context.
- Support for image file uploads to send to multimodal LLMs.
- Side-by-side LLM response comparison of two models.

## Conclusion
This documentation serves as a guide to understanding and using the Chat Assistant project. For further assistance, please refer to the code comments and additional resources provided in the repository.