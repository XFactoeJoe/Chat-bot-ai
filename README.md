# Chat-bot-ai
Step 1: Open your Terminal

Press Ctrl + Alt + T on your keyboard. This opens the black command window where we type our instructions.
Step 2: Install Ollama

Copy the line below, paste it into your terminal, and press Enter:

Bash

curl -fsSL https://ollama.com/install.sh | sh

What this does: it downloads the "brain" for your AI bot and sets it up on your Ubuntu system automatically.

    Note: It might ask for your password. When you type it, you won't see any stars or dots—just type it and hit Enter.

Step 3: Run the Bot

Once the installation finishes, you need to tell it which AI model to use. We will use llama3.2 because it is fast and smart. Type this and press Enter:

Bash

ollama run llama3.2

Wait a moment: It will download the AI model (about 2GB). You’ll see a progress bar.

Step 4: Start Chatting!

When you see a message like >>> Send a message, your bot is alive!

    You can type: Hello, who are you?

    To leave the chat later, type /exit and press Enter.
