# SpyWare-Tool
A comprehensive monitoring tool written in Python that captures various system activities and information. This tool is designed for educational purposes and ethical use only.
Features
Keystroke Logging: Records all keyboard inputs and saves them to a text file

System Information Gathering: Collects computer details (IP address, processor, system info) and stores in Excel format

Clipboard Monitoring: Captures clipboard contents and saves with timestamps

Browser History Extraction: Retrieves Google Chrome browsing history and exports to Excel

Screenshot Capture: Takes a screenshot of the current desktop

Disclaimer
This tool is intended for educational purposes only. Use only on systems you own or have explicit permission to monitor. Unauthorized use may violate privacy laws and regulations.
Installation

#Clone this repository:
bash
git clone https://github.com/yourusername/spyware-tool.git
cd spyware-tool

#Install required dependencies:
bash
pip install -r requirements.txt

Requirements
The tool requires the following Python packages:

pynput
pandas
pillow
requests
pywin32
sqlite3 (typically included with Python)

Usage
Update the Chrome history path in the script:

Locate this line: conn = sqlite3.connect('C:\\Users\\anubh\\AppData\\Local\\Google\\Chrome\\User Data\\Default\\History')
Replace the path with your Chrome history database location

Run the tool:
bash
python Spyware_tool.py
To stop the keystroke logging, press the Esc key

Output Files
The tool generates the following files:

> logs.txt - Recorded keystrokes
> keystrokes.xlsx - System information
> clipboard.txt - Clipboard contents with timestamps
> search_history.xlsx - Chrome browsing history
> screenshot.png - Desktop screenshot

Important Notes
Some features require administrator privileges
Close Chrome completely before running to avoid database lock errors
Antivirus software may flag this tool as potentially unwanted
Use responsibly and ethically

Legal and Ethical Considerations
Always ensure you have proper authorization before using this tool on any system. Unauthorized monitoring may violate:
Computer Fraud and Abuse Act
Electronic Communications Privacy Act
Various state and international privacy laws

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
