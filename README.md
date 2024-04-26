# Microsoft Teams Automation Bot

This project is a Python-based automation bot designed to interact with Microsoft Teams. Utilizing the Selenium WebDriver, it provides functionalities to navigate through Teams' channels, identify active meetings, and manage participation in them.

## Features
- **Automated Channel Navigation**: Traverse through team channels to find active meetings.
- **Blacklist Management**: Exclude specific channels from the bot's operation based on a configurable blacklist.
- **Meeting Interaction**: Join and leave meetings automatically, with support for custom timing.

## How It Works
The bot uses the Selenium WebDriver to control a web browser session of Microsoft Teams. It reads from a configuration file to determine which teams and channels to interact with, and which to avoid based on the blacklist settings.

## Configuration
Users can specify teams, channels, and meeting preferences in a JSON configuration file. The bot will use this information to operate accordingly.

## Usage
To use the bot, ensure you have the necessary drivers installed and the configuration file set up. Then, simply run the script, and the bot will begin its operation.

## Disclaimer
This bot is intended for educational purposes only. Please adhere to Microsoft's Terms of Service when using automation tools.

## Contributions
Contributions to the project are welcome. Please ensure to follow the contribution guidelines outlined in the repository.

---

Please note that this is a preliminary description. You may want to add more details about installation, usage instructions, dependencies, and any other relevant information that users might need.
