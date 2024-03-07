# Telegram Bot

This is a simple Telegram bot implemented in Python using the python-telegram-bot library. The bot provides basic functionalities such as responding to commands and echoing messages.

## Functionality

The bot serves as a virtual assistant for real estate businesses, offering information about their social media profiles and other online platforms. Users can interact with the bot to access links to the business's social media profiles, website, and other relevant online resources.

## Requirements

- Python 3.x
- python-telegram-bot 13.5

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies by running:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Obtain a Telegram bot token from the BotFather on Telegram.
2. Replace `"YOUR_TELEGRAM_BOT_TOKEN"` in the `bot.py` file with your actual bot token.
3. Run the bot by executing:

    ```bash
    python bot.py
    ```

4. Interact with the bot on Telegram by sending messages or using commands.

## Features

- /start: Start a conversation with the bot.
- Any other message: The bot will echo back the message.
