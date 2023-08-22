# ssh-brute.py
# SSH Brute Force Script

This repository contains a Python script for performing SSH brute force attacks on remote servers. The script attempts to log in using a list of passwords and reports whether a successful login is found.

**Please Note**: This script is provided for educational purposes only. Unauthorized access to systems is illegal and unethical. Use this script responsibly and only on systems you have explicit permission to test.

## Features

- Attempts SSH logins using a list of passwords against a specified host.
- Implements multithreading for parallel password attempts to speed up the process.
- Provides basic logging and reporting of login attempts.
- Customizable parameters such as host, port, username, and timeout.
- Educational tool for understanding the concept of brute force attacks.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install pwntools`.
3. Modify the script to specify the target host, port, username, and password list.
4. Run the script using Python: `python ssh-brute.py`.

## Disclaimer

This script is intended for educational and research purposes only. Do not use this script for any illegal or unauthorized activities. Unauthorized access to computer systems is illegal and punishable by law.

The authors and contributors of this repository are not responsible for any misuse of the script or any harm it may cause. Use this script responsibly and only on systems you have explicit permission to test.


