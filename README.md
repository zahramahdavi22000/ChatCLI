# Chat CLI
This repository contains a simple chat room implementation using SocketIO with python3.

## Prerequisites
Make sure you have the following installed:

- Python 3
- `eventlet` library: Install it using `pip install eventlet`
- `socketio` library: Install it using `pip install python-socketio websocket-client`

## Usage

### Server

To run the server:

```bash
python chat-server.py
```

The server will start at `http://localhost:5000`.

### Client CLI

The client script (`chat-cli.py`) provides a command-line interface (CLI) for interacting with the chat room.

```bash
python chat-cli.py
```

Follow the prompts to enter your name and start sending messages.

### Messages Monitor

The `chat-monitor.py` script monitors and displays incoming messages from other users in the chat room.

```bash
python chat-monitor.py
```

This script connects to the server and listens for incoming messages and join events.

Feel free to modify and extend this code as needed for your project!