# IAT-Hooking
## Overview
Creating a malware for import address table hooking. \
This project is a demonstration of Import Address Table (IAT) hooking

## Prerequisites
Microsoft Visual Studio (at least 2019) (for compilation) \
RemoteDll Injection Tool (for DLL injection)

## Setup and Usage
Compile the Project:

Use Microsoft Visual Studio to compile the project. Ensure all dependencies are correctly referenced.
Download a RemoteDll Injection Tool:
Recommended tool:  https://remotedll.en.lo4d.com/windows

Download and install the RemoteDll injection tool from the provided link.
Run the RemoteDll Injection: \
Open the RemoteDll injection tool.
Specify the path to the compiled DLL.
Choose a process for injection (e.g., Notepad++ for demonstration purposes).
Execute the injection.
After these steps, the DLL will be injected into the specified process, hooking the CreateFileW function from the KERNEL32.dll.

## Known Issues and Bugs
As of the current version, this project has some known bugs and issues that may affect performance or functionality. i am actively working on resolving these issues and welcome contributions and suggestions from the community.

### Acknowledgments
Thanks to John Hammond (GitHub) for his guidance.

### Contact
For questions, suggestions, or contributions, please contact through the project's GitHub page.
