# FinanceTelegramBot

FinanceTelegramBot is a Telegram bot developed using Python to provide financial information and services to users.

## Overview

FinanceTelegramBot offers the following features:
- **Expense Tracking:** Record your expenses and categorize them for better organization.
- **Income Tracking:** Track your sources of income and monitor your financial inflows.
- **Statistics:** Generate statistics and visualize your financial data for better insights.
- **Graphical Representation:** View pie charts representing your income and expenses for easy understanding.

## Installation

To use FinanceTelegramBot, follow these steps:
1. Clone the repository: `git clone https://github.com/Markelloff2004/FinanceTelegramBot.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Create a Telegram bot and obtain the API token.
4. Configure the bot token in the `config.py` file.
5. Run the bot: `python bot.py`

## Usage

Once the bot is running, you can interact with it through Telegram. Start a chat with the bot and use the available commands to access financial information and services.

### Available Commands

- `/start`: Start the bot and view available commands.
- `/stock [symbol]`: Get real-time stock information for the specified symbol (e.g., `/stock AAPL`).
- `/convert [amount] [from_currency] [to_currency]`: Convert between currencies (e.g., `/convert 100 USD EUR`).
- `/news`: View the latest financial news headlines.
- `/portfolio`: Manage your investment portfolio.

## Contributing

Contributions to FinanceTelegramBot are welcome! If you have suggestions, bug reports, or want to contribute code, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
