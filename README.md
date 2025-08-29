# Crypto Investment Chatbot

## Getting Started

To run this chatbot locally:

1. **Clone the repository**

   ```bash
   git clone git@github.com:farhanfahim00/CryptoChatbot.git
   git pull origin main
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Application**

   ```bash
   node server.js
   ```

   This will launch the backend server and serve the frontend interface at `http://localhost:3000`.

---

## Project Overview: Crypto Investment Chatbot

This project is a real-time chatbot designed to assist users in understanding cryptocurrency investment. It provides clear guidance on live market insights, definitions and simple portfolio suggestions in a conversational format.

Chatbot interacts dynamically with users understands their queries through keyword intent matching, and pulls real-time data from CoinGecko API. It’s built to be both informative and approachable offering help without requiring users to already be tech or crypto experts.

### Core Features

* **Platform & Wallet Guidance**: Provides how to get started info. Recommends beginner-friendly exchanges (like Binance or Coinbase) and explains how to safely store crypto using hot and cold wallets. 
* **Live Crypto Prices**: Users can ask for the current price of coins like Bitcoin, Ethereum, Solana, and many others. The bot uses the CoinGecko API to fetch real time prices using crypto names & their abbreviations. 
* **Trending Coins & Market Overview**: Returns up to date real time data on the overall crypto market and shows which coins are currently trending, based on live external data. 
* **Basic Portfolio Planning**: while asking the user's budget risk willingness and coin preferences,  the bot can suggest a balanced portfolio ensuring accurate matchmaking. 
* **Conversational Memory**: It remembers parts of the conversation (like user preferences or budget) to continue the interaction smoothly and contextually.
* **Crypto Education**: Provides beginner-friendly detailed explanations for common concepts like blockchain, cryptocurrency, wallets, and investing strategies.

### Tech Stack

* **Node.js + Express.js** – Backend server and API logic
* **Socket.IO** – Enables real-time chat communication
* **React.js** – Frontend built for responsiveness and smooth interaction
* **CoinGecko API** – Used to fetch real-time crypto prices and trending data
* **Custom Intent System** – Uses a keyword-based matching engine (`intents.json`) to understand and respond to user queries without relying on third-party NLP services

### Use Case

This chatbot is ideal for:

* Students and beginners who want to learn about crypto without getting overwhelmed
* Casual users who want quick market updates or price checks
* Developers looking to study or expand on real-time chat applications using web sockets and API integration

---

