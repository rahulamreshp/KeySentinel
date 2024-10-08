# PRODIGY_CS_04
# KeySentinel: Stroke Logger

The Stroke Logger is a discreet monitoring utility designed to capture keyboard input and log it into a text file. It serves as a tool for tracking user activity, often employed for security auditing, parental control, or employee monitoring purposes.

# Usage
pip install requirements.txt

python3 keylogger.py

# Modules

Keylogging Functionality

1. The program captures keyboard input in real-time using the pynput library, specifically the Listener class, allowing it to track every keystroke made by the user.

2. It filters and processes the keystrokes, converting them into a readable format and storing them in a designated log file.

3. Special keys such as space, shift, control, and enter are handled to ensure accurate representation of the logged text.

4. The logging process commences upon execution of the program, running silently in the background without user intervention.


Logging Information

1. Each logged entry includes the timestamp of the keystroke, providing insight into the timing of user interactions with the keyboard.

2. The log file records the start time of logging, facilitating easy tracking and analysis of keyboard activity over time.

3. Keyboard input is appended to the log file, allowing for continuous monitoring and accumulation of data until the program is terminated.

4. The program ensures that logging begins from a new line in the file each time it is executed, maintaining clean and organized log records.


Security and Privacy Considerations

1. While keyloggers can be valuable tools for legitimate purposes, their usage raises significant privacy and security concerns.

2. Users should exercise caution and ensure compliance with applicable laws and regulations when deploying keylogging software.

3. It is recommended to use keyloggers responsibly and transparently, with proper authorization and consent from relevant parties.

4. To mitigate potential risks, users should secure access to the log file and implement safeguards to prevent unauthorized access or misuse of recorded data.
