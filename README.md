# Time Log Parser
This Python script is designed to parse a time log provided as a text file and calculate the total hours logged. Each entry in the time log file should follow the format: MM/DD/YY: start_time - end_time activity_description. The script can be run using the command: python tlparser.py timelog.txt, where timelog.txt is the name of the time log file.

How to Use
Prerequisites: Ensure you have Python installed on your system. If not, you can download it from Python's official website.

Download the Script: Download the tlparser.py script from this repository.

Prepare your Time Log File: Each line in the time log file should represent a single entry with the format: MM/DD/YY: start_time - end_time activity_description.

Example:
2/23/12: 9:10pm-11:40pm getting familiar with Flash
2/29/12: 12:50pm-2:00pm getting familiar with Flash
Run the Script: Open your terminal or command prompt and navigate to the directory containing tlparser.py and your time log file.

Run the script using the following command:
python tlparser.py timelog.txt
Replace timelog.txt with the name of your time log file.

View Output: The script will output the total hours logged based on the entries in the time log file.

Example
Suppose you have a time log file named timelog.txt with the following entries:
2/23/12: 9:10pm-11:40pm getting familiar with Flash
2/29/12: 12:50pm-2:00pm getting familiar with Flash
Running the script with this time log file:

python tlparser.py timelog.txt
The output will be:
Total Hours Logged: 4.67 hours


Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute this code for your own projects.
