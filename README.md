Telegram Bot with Node.js
This is a simple Telegram bot created using Node.js that provides various functionalities such as sending messages, searching the web, and handling commands.

Prerequisites
Node.js installed on your system
A Telegram bot token obtained from the BotFather on Telegram
Setup
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/Varshi45/Sports-Scheduler
Install the required dependencies using npm:
Copy code
npm install
Replace the placeholder Telegram bot token in the code with your actual bot token:
javascript
Copy code
const bot = new TelegramBot('<your_bot_token>', { polling: true });
Run the bot:
Copy code
node index.js
Usage
Start the bot by sending the /start command to initiate a conversation.
Use the /alert command to receive a message guiding you on how to use the search functionality.
Utilize the /search <query> command to search the web for information based on the provided query.
Dependencies
node-telegram-bot-api: A Telegram Bot API wrapper for Node.js.
axios: A Promise-based HTTP client for making HTTP requests.
