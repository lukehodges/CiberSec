# Discord Hack Week bot
This bot is mainly focused on cyber security. The bot works like a command shell. You simply type in a Linux shell command, and the bot will return the output from the executed command.

# Installation
Clone the repository via:
```bash
$ git clone https://github.com/WodxTV/CiberSec.git
```

Python 3 has to be installed on the Linux machine in order to make this bot work

You can check the version of Python you've installed by executing this bash command:
```bash
$ python --version
```
If the command is not recognized, execute this bash command:
```bash
$ sudo apt update
$ sudo apt install python3.7
```
PIP (package-management system) for Python 3.7 also has to be installed.

Install PIP by executing this bash command:
```bash
$ sudo apt update
$ sudo apt install python3-pip
```

When you've both Python 3 and PIP installed, create a new client bot using this link:
```
https://discordapp.com/developers/applications/
```

Copy the client ID and paste this command into your browser to invite the bot to your Discord server:
```
https://discordapp.com/oauth2/authorize?client_id=CLIENT_ID_HERE&scope=bot&permissions=8
```

# Running the bot
I recommend you running the bot on a penetration testing Linux distribution like Kali Linux or Parrot OS, as these two distributions has a lot of pre-installed penetration testing/hacking tools installed.



Start the bot by using this Python bash command:
```bash
$ python3 cibersec.py
```

# Work in progress
* Auto create role 'CiberSec'
* Auto create category named 'CiberSec'
* Auto create text channel named 'Terminal' under category 'CiberSec'
* Auto create text channel named 'Command History' under category 'CiberSec'
* Handling +2000 chars outputs
* Handling changing/'animated' outputs
