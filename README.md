A simple and efficient Python script to automate Cisco device configurations using the Netmiko library.

📝 What does this script do?
Interactive Login: Prompts you for your username and password securely (using getpass).

Dynamic Configuration: Asks for the Loopback number and IP address you want to configure for each device.

Auto-Provisioning: Logs into the router, creates the interface, and assigns the IP and description.

Config Persistence: Automatically runs write memory to save your changes to the NVRAM.

⚙️ Requirements
Python 3.x installed.

Netmiko library. You can install it using:
Bash
pip install netmiko

🚀 How to Run
Download the script file: loopback script.py.
Open your terminal and run:
Bash
python loopback script.py
