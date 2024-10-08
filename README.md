# DuTecZone Telegram Auto MsgBot
![DuTecZone GitHub](https://raw.githubusercontent.com/Alexdu1996/telegram-auto-msg-bot/046a4e8f521406ac4df746d839cc73f69ac19223/DuTecZone%20Github.svg)


Welcome to the DuTecZone Telegram Auto MsgBot! This Python-based automation tool is designed to simplify the process of forwarding messages from your Saved Messages to multiple Telegram groups. Whether you're managing communication for a community or need to distribute messages efficiently, this tool helps automate the process.

For a detailed guide and further insights, check out our [Telegram Bot Auto Send Message article](https://www.duteczone.com/auto-message-sender-bot-for-telegram-python/).

![telegram bot auto message sender](https://github.com/Alexdu1996/telegram-auto-msg-bot/blob/main/Telegram%20Bot%20Auto%20Message%20Sender.png?raw=true)
## Features

- **Automated Message Forwarding**: Automatically sends the latest message from your Saved Messages to multiple Telegram groups.
- **Dynamic Configuration**: Prompts for API ID, API HASH, phone number, and verification code as needed.
- **File Management**: Creates necessary files (`Credentials.txt` and `Groups.txt`) if they do not exist and handles file reading/writing.
- **Continuous Operation**: Restarts automatically after sending all messages, ensuring ongoing operation.
- **Error Handling**: Provides feedback and error messages to help troubleshoot any issues.

## Installation

To get started, clone the repository and install the required dependencies. Follow these steps:

### Clone the Repository

```bash
git clone https://github.com/yourusername/telegram-auto-msg-bot.git
cd telegram-auto-msg-bot
```
### Install Dependencies
Ensure you have Python 3.12.x installed. You can then install the required libraries using requirements.txt.
```bash
pip install -r requirements.txt
For a quicker setup, you can also execute the requirements_install.bat file.
```
### Usage
Run the Script
Execute the Python script to start the bot:
```bash
python TG_Auto.py
```
Provide Credentials
On first run, the script will ask for your API ID, API HASH, phone number, and verification code. These details will be saved in Credentials.txt for future use.

Configure Group URLs
Ensure that Groups.txt contains the URLs of the groups you want to forward messages to, listed in order. If Groups.txt does not exist, the script will create it, but you need to add the URLs manually. There is no limit to the number of groups you can include. Here is a sample of how to list the group URLs in Groups.txt:
```bash
https://t.me/Group1
https://t.me/Group2
https://t.me/Group3
https://t.me/Group4
```
Ensure each URL is on a new line. The bot will automatically send messages to these groups sequentially from top to bottom, and once it reaches the end, it will start over automatically.

Set Delay
You can set a delay between messages to avoid hitting Telegram’s rate limits. This is prompted during the script’s execution.

Important Notes
Read Telegram's API Policy: Ensure you are compliant with Telegram's API Policy to avoid any issues.
Avoid Overloading: Set an appropriate delay to avoid excessive messaging that may lead to bans or restrictions.
Contributing
Feel free to contribute to this project by submitting issues or pull requests. Your feedback and contributions are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or support, you can reach out to:

Credits
Alex David Du  
Email: [Alexdaviddu26091996@gmail.com](mailto:Alexdaviddu26091996@gmail.com)  
Telegram: [@Alexdu1996](https://t.me/Alexdu1996)  
Site: [DuTecZone](https://www.duteczone.com/)
