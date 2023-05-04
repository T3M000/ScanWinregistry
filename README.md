# ScanWinregistry
This Python code is designed to scan the Windows Registry for known malware keys and values. It uses the winreg module to interact with the Registry and regular expressions to match obfuscated or random registry key names.

The code defines a list of well-known registry keys that are commonly associated with malware or attacks. It then checks whether these keys exist in the Registry and adds them to a list if they are found. It then checks the values of these keys to look for suspicious file paths, file signatures, and other indicators of malware.

If a suspicious value is found, the code prints a message indicating the registry key and value name. If a file with a known malware signature is found, the code prints a message indicating the file path and the registry key that references it.

This code can be useful for security analysts and IT professionals who need to quickly identify potential malware infections on Windows systems. It can also be used as a starting point for developing more advanced malware detection and remediation tools.

# Requirement 
-  pip install winreg os re 
 
