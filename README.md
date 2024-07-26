### Frontend `README.md`

```markdown
# Chat Frontend

This is the frontend for a chat application that communicates with a FastAPI backend using OpenAI's GPT-4o-mini model.

## Requirements

- A modern web browser

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/a6s1/GPT-4o-mini-integration-frontend.git
   cd chat-frontend
   ```

2. Serve the static files. You can use a simple HTTP server. If you have Python installed, you can run:

   ```bash
   python -m http.server 8080
   ```

3. Open your web browser and navigate to `http://localhost:8080`.

## Usage

Enter a message in the input box and click "Send". The message will be sent to the backend server, and the response will be displayed in the chat box.

## Project Structure

- `index.html`: The main HTML file for the chat interface.
- `style.css`: The CSS file for styling the chat interface.
- `script.js`: The JavaScript file for handling user input and communication with the backend.


```