# Llama 3.1 405B Chatbot

This project is a web-based chatbot powered by Llama 3.1 405B and FastAPI. The chatbot utilizes OpenAI's language model to provide conversational responses. The frontend is built using HTML, CSS, and JavaScript, while the backend is built with FastAPI.

## Features

- **Conversational AI**: Powered by Llama 3.1 405B.
- **FastAPI Backend**: Handles API requests and responses.
- **Frontend**: Simple and interactive web interface.
- **CORS Middleware**: Allows secure cross-origin requests.
- **Memory Buffer**: Remembers the context of the conversation for better responses.

## Getting Started

### Prerequisites

- Python 3.7+
- FastAPI
- Uvicorn
- OpenAI API Key

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/llama-chatbot.git
    cd llama-chatbot
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1. **Start the FastAPI server**:

    ```bash
    uvicorn main:app --reload
    ```

    The server will start at `http://127.0.0.1:8000`.

2. **Open the frontend**:

    Open `index.html` in your web browser to interact with the chatbot.


## API Endpoints

### `/chat`

- **Method**: GET
- **Query Parameters**:
  - `api_key`: OpenAI API Key
  - `prompt`: User's message
  - `history`: Optional conversation history

- **Response**:
  - `response`: Chatbot's response

## Example Usage

1. **Send a message**:

    ![Send a message](screenshot-send-message.png)

2. **Receive a response**:

    ![Receive a response](screenshot-receive-response.png)

## Customization

- **Modify Frontend**: Update `index.html` and `chat.html` in the `templates` directory.
- **Modify Backend**: Update `main.py` for backend logic.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License.

---

Happy chatting! 🚀
