# simple-portscanner
Simple Port Scanner
This is a simple Python script that can be used to scan a range of ports on a target machine. It uses the socket library to open a connection to each port in the specified range and check if it is open.

Usage
To use the port scanner, follow these steps:

Clone the repository to your local machine.
Open the portscanner.py file in a text editor.
Modify the target variable to the IP address or hostname of the target machine.
Modify the port_range variable to the range of ports you want to scan (e.g. range(1, 100) will scan ports 1 through 99).
Save the file and run it using Python 3.
$ python3 portscanner.py
The script will output a list of all open ports in the specified range.

Disclaimer
This script is provided for educational purposes only. Do not use it to scan machines or networks without permission. Unauthorized port scanning is illegal in many jurisdictions and can result in severe legal consequences. Use this tool at your own risk.
