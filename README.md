# :unlock: Windows Process Injection

![C](https://img.shields.io/badge/language-C-blue)
![Windows](https://img.shields.io/badge/platform-Windows-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## :page_with_curl: Description

This project contains a sample C code that demonstrates the technique of process injection in the Windows environment. The code attempts to inject shellcode into the "explorer.exe" process. :warning: The provided shellcode is intended for a Unix system, so it won't actually work in this context.

## :gear: Usage

To compile and run the program, use the following commands:

```
gcc injection.c -o injection
./injection
```
Please use this responsibly and do not attempt to inject code into processes without proper authorization.

# :warning: Disclaimer
This code is provided for educational purposes only. Process injection techniques can be used maliciously and can lead to security issues if misused. :no_entry_sign: Please do not use this code for malicious purposes.

# :book: License
This project is licensed under the MIT License - see the LICENSE.md file for details
