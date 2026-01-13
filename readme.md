# 🤖 Dresguardian - Protect Your Privacy on Telegram

## 🚀 Getting Started

Dresguardian is a privacy-focused bot for managing Telegram groups. It comes equipped with artificial intelligence features and integrates with DuckDuckGo for secure web searches. Follow the steps below to download and run Dresguardian on your device.

## 📥 Download the Latest Release

[![Download Dresguardian](https://img.shields.io/badge/Download%20Dresguardian-v1.0-brightgreen?style=for-the-badge)](https://github.com/eduardopini/Dresguardian/releases)

## 🛠️ System Requirements

To run Dresguardian smoothly, ensure your system meets the following requirements:

- **Operating System:** Ubuntu 20.04 or later, Debian 10 or later
- **Memory:** At least 2 GB of RAM
- **Disk Space:** Minimum of 100 MB available
- **Python Version:** Python 3.7 or later
- **Internet Connection:** Required for bot functionality and web searches

## 📂 Download & Install

1. Visit the [Releases page](https://github.com/eduardopini/Dresguardian/releases) to access the latest version.
2. Locate the download file that matches your operating system:
   - For Ubuntu users, download the `.deb` package.
   - For Debian users, download the appropriate `.deb` file.
3. Click on the file name to start the download.
4. Once the file downloads, open your terminal.

For Ubuntu or Debian users, run the following command to install the bot:

```bash
sudo dpkg -i path_to_downloaded_file.deb
```

Replace `path_to_downloaded_file.deb` with the actual path to the downloaded file. 

In case of dependency issues, run:

```bash
sudo apt-get install -f
```

## ⚙️ Configuration

After installation, configure the bot:

1. Open your terminal.
2. Navigate to the directory where Dresguardian is installed. Usually, this will be in `/usr/local/bin` or where you specified during installation.
3. Create a configuration file by running:

```bash
touch config.json
```

4. Edit the `config.json` file to include your Telegram API token and group ID. You can use any text editor, such as nano:

```bash
nano config.json
```

Insert the following template:

```json
{
  "api_token": "YOUR_TELEGRAM_API_TOKEN",
  "group_id": "YOUR_GROUP_ID"
}
```

Make sure to replace `YOUR_TELEGRAM_API_TOKEN` and `YOUR_GROUP_ID` with your actual data.

## 🐳 Running the Bot

To run Dresguardian, use your terminal:

1. Navigate back to the installation directory if you have not already.
2. Start the bot by running:

```bash
python3 dresguardian.py
```

The bot will connect to Telegram and start managing your group. 

## 📜 Features

Dresguardian offers multiple features:

- **Privacy Management:** Keeps your group secure from unwanted users.
- **AI Integration:** Uses artificial intelligence to optimize group management.
- **DuckDuckGo Search:** Conduct private searches without tracking.
- **Custom Commands:** Set up personalized commands for your group.

## 🛡️ Privacy Information

Dresguardian prioritizes your privacy. No user data is stored, and all searches are done using DuckDuckGo to ensure anonymity. 

## 🤔 Troubleshooting

If you face issues:

1. Ensure you have the required Python version.
2. Verify your configuration is correct.
3. Check your internet connection.

For further help, refer to the issue tracker on the [GitHub page](https://github.com/eduardopini/Dresguardian).

## 📞 Support

For any questions or support, you may reach out via the project's GitHub repository. Community support is available via issues.

## 📌 Additional Resources

- [Telegram Bot API Documentation](https://core.telegram.org/bots/api)
- [DuckDuckGo Search API](https://duckduckgo.com/api)

Visit the [Releases page](https://github.com/eduardopini/Dresguardian/releases) to download Dresguardian now!