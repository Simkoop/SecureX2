# SecureX2



SecureX is Virtual Environment developed by ProGens to help keep you safe!
Be safer when running software outside of a VM.

To use just replace run.exe with an exe of your choice, make sure to rename it to run.exe then run SecureX2.exe
------------------------------------------------------------------

What this PROTECTS against:
 - Keyloggers: No keylogging can be done from withing or into the sandbox
 - Rats: All remote viewing priveleges of an application are limited to the sandbox
 - Malicious Startup Items: Startup items are reset after the sandbox closes
 - Process persistance: All processes running in the sanbox are closed on exit
 - VM Detection: This circumvents VM detection

What this DOES NOT PROTECT againts:
 - Info stealers: (FUTURE VERSION WILL PROTECT)
 - Crypters: Executables in the sanbox have full read write permissions
 - Rootkits: When you grant an app admin permissions it can still install a rootkit
 - System file injection

Stay safe and Enjoy :)

More info:
The program run in the VE is \files\app\run.exe (you can simply run this file without the sandbox)
The UI software run in the VE is \files\ui\SecureUI.ex

What is actually happening:
A secure desktop is used to isolate the exe from the rest of the running processes, 
and all startup items and processes are reverted after the program is closed.
