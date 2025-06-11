💱 Currency Converter Automation (n8n Workflow)

 ## This n8n automation workflow converts currency values using a real-time exchange rate API and sends the results via Telegram.

📌 Features
- Accepts two currency codes and an amount.
- Retrieves live exchange rates via an API (ExchangeRate-API or similar).
- Calculates the converted amount.
- Sends the result to a Telegram user via message.

🔧 Workflow Structure
1. Telegram Trigger – Listens for a message input in this format:  
   `USD to INR 10`
2. Function Node – Parses the message and extracts source currency, target currency, and amount.
3. HTTP Request – Fetches exchange rate from API.
4. Function Node – Calculates the converted amount.
5. Telegram Node – Sends a reply message with the conversion result.

🌐 Tools & Services Used
- [n8n](https://n8n.io)
- [ExchangeRate-API](https://www.exchangerate-api.com/) (Free tier)
- [Telegram Bot](https://core.telegram.org/bots)

📲 Connect with Me
- 💼 [LinkedIn: ashleymathia10](https://linkedin.com/in/ashleymathia10)
- 💻 [GitHub: AshleyMathias](https://github.com/AshleyMathias)
