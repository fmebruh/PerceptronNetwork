PerceptronNetwork - Blockmesh Bot
A Python-based bot for interacting with the Blockmesh network, designed for efficiency and ease of use.
 ██████╗███████╗
██╔════╝██╔════╝
██║     ███████╗
██║     ╚════██║
╚██████╗███████║
 ╚═════╝╚══════╝

Features ✨
Multi-Account Support: Run the bot with multiple accounts simultaneously.

Proxy Integration: Supports using proxies for all network requests.

Real-time WebSocket: Establishes a WebSocket connection for real-time communication.

Easy Configuration: Simple setup using account.txt and proxies.txt files.

Cross-Platform: Compatible with any operating system that supports Python.

Installation & Usage 🚀
Clone the repository:

git clone https://github.com/fmebruh/PerceptronNetwork

Navigate to the project directory:

cd PerceptronNetwork

Install the required dependencies:

pip install -r requirements.txt

Configure your accounts and proxies (see below).

Run the bot:

python main.py

You will be prompted to choose whether to use proxies.

Configuration ⚙️
account.txt: Add your Blockmesh accounts to this file. Each account should be in the format email:password, with one account per line.

example1@email.com:password123
example2@email.com:password456

proxies.txt (Optional): If you want to use proxies, add them to this file. The script supports HTTP proxies in the format http://user:pass@host:port, with one proxy per line.

Disclaimer ⚠️
This tool is for educational purposes only. The developers are not responsible for any misuse or damage caused by this program.

Support 💬
For any questions or support, feel free to join our Telegram channel:

Telegram: @ChainScripters
