# portScanner

A simple TCP port scanning tool. It checks ports from 1 to 65534 on a given target IP address or domain name and shows the user which ones are open.

Features
Port Scanning: Tries to connect to all TCP ports from 1 to 65534 and reports whether they are open or closed.
Banner Display: Uses pyfiglet to display an ASCII-style heading in the console.
Time Information: Prints information such as when the scan started.
Quick Exit: Allows the user to stop the scan at any time using Ctrl + C (KeyboardInterrupt).
Installation
Download or clone the project files.
Required Library: pyfiglet is used.
Can be installed via pip. (Example: pip install pyfiglet)
Python 3 is recommended.
How It Works
Prompts the user for a target IP or domain name.
Iterates through the defined port range (1–65534) and checks each port via TCP.
If a connection is successful, the port is considered open and printed to the screen.
If the connection fails or times out, the port is considered closed.
Displays information such as the start time and target address.
Ends the scan after testing all ports.
Usage
Run with the python command in your terminal/console.
Enter the required target IP or domain when prompted.
All open ports will be listed in the console.
To cancel the scan, press Ctrl + C at any time.
Contributing
Fork this project.
Create a new branch.
Commit your changes and push them to your branch.
Submit a Pull Request.
License
You may choose any open-source license you prefer (for example, MIT, GPL, etc.).

This Port Scanner tool is a sample for network exploration and basic security testing. You can expand it with more features (like UDP scanning, multi-threading, etc.). By following the project files and setup steps, you can test it on your own system and check which ports are open.
