```markdown
# Gevexa-beta CLI

> *"The results of the first trial were less intelligent and still less intelligent"*  
> — Honest assessment from the first prototype.

**Gevexa-beta** is a futuristic terminal-based AI assistant built with Python. This is an early-stage prototype that uses simple keyword matching and a JSON database. Currently, its intelligence is limited, but the terminal experience is stylish.

![Gevexa Screenshot](example.png)

---

## Features

- Interactive chat in terminal with AI-like responses
- Futuristic purple-themed interface
- Simple AI brain powered by `brain.json` (keyword-response pairs)
- Typing animation for realistic AI feel
- Conversation history
- Commands: `/clear` to reset chat, `exit` to quit

---

## Tech Stack

- Python 3
- JSON (for knowledge base)
- prompt_toolkit
- rich
- pyfiglet

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gevexa-beta.git
   cd gevexa-beta
```

1. Install required dependencies:
   ```bash
   pip install prompt_toolkit rich pyfiglet
   ```
   Or check the imports in run.py for the full list of required modules.

---

Usage

Run the application:

```bash
python run.py
```

Inside the app:

· Type your message and press Enter to chat with Gevexa
· Type /clear to clear conversation history
· Type exit or press Ctrl+C to quit

Adding knowledge

Edit the brain.json file in the same directory as run.py. Format:

```json
{
  "hello": "Hi there! How can I help you?",
  "your name": "I am Gevexa-beta, a simple terminal AI.",
  "help": "Available commands: /clear, exit. You can also ask me anything I know."
}
```

The AI matches keywords loosely, so "hello", "say hello", or "hello there" will trigger the same response.

---

Current Limitations

· No machine learning or NLP — purely keyword matching
· Small knowledge base by default
· No memory across sessions
· Responses are static and predefined

---

Project Status

Alpha / Prototype stage. This is a learning project and a foundation for future improvements.

---

License

MIT

---

Author

Your Name / Your GitHub

---

Example

example.png

Replace example.png with an actual screenshot of the terminal interface.

```