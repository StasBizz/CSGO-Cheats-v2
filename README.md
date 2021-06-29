# CSGO-Cheats-v2

Introduction
This is a collection of cheats for the video-game Counter-Strike: Global Offensive.

Code Samples
Gaining access to the CSGO application
The window is stored HWND hwnd = FindWindowA(NULL, "Counter-Strike: Global Offensive");
The process ID is retrieved GetWindowThreadProcessId(hwnd, &procId);
A handle is is created HANDLE hProcess = OpenProcess(PROCESS_ALL_ACCESS, NULL, procId);

How to read and write process memory
How to read process memory: RPM<variable type>(address + offsets);
Example: RPM<int>(0xD30B94 + 0x4);

How to write process memory: WPM<variable type>(address + offsets, newValue);
Example: int value = 999; WPM<int>(0xD30B94 + 0x4, value);

Installation
Update the addresses and offsets. I reccomend using Hazedumper for this.
Set the character set to Multi-Byte.
Build the application as x86 and run as an administrator.
Error trouble shooting
If you are having issues compiling check out the faq for common issues I've seen!
