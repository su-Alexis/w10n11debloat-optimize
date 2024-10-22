# w10n11debloat-optimize

  Hi, I'm Alexis! This project started as a way to pass the time during quarantine and to learn PowerShell. 
Initially, I attempted to build this script in .bat, but quickly realized it wasn't the right tool for the job—it felt like digging a river with a spork! 
After some research, I discovered Syncex's script, and I'd like to extend a huge thanks to them and all their contributors for their work. 
This project builds upon their debloater, with additional functions I've added for optimization, system tweaks, stability, gaming enhancements, and network improvements.
  
This script aims to be an all-in-one solution for anyone, like my friends and me, who needed a tool that simplifies system optimization after a reformat or major Windows update. Special thanks also go out to Dan Pollock and their contributors for their fantastic Hosts file—your work deserves all the recognition!
  
In short, this script is designed to help users get the most out of their machine with minimal hassle.
 
I hope it serves you as well as it has helped my friends and me!

#
Credit goes to Syncex and all their contributers for the original Windows10Debloater script that this was built off of. 
-
Syncex's Github: https://github.com/Sycnex 

Syncex's Win10Debloater script: https://github.com/Sycnex/Windows10Debloater 
#  
Credit goes to Dan Pollock and all their contributers for the Hosts file
-
Dan Pollock's website: https://someonewhocares.org

Dan Pollock's Hosts file: https://someonewhocares.org/hosts/
#
Credit always goes to stackoverflow and everyone there <3
-
Stackoverflow's website: https://stackoverflow.com/
#
Credit also ofcourse goes towards github and everyone there <3
-
Github's website: https://github.com
#

| How to run the script |
-
Via Terminal
-
  
-  Open Terminal as Admin shortcut: (win key + x then hit a or click on it) 
-  Then type in "Set-ExecutionPolicy bypass" hit enter (no "") OR "Set-ExecutionPolicy RemoteSigned" hit enter (no "") 
-  Then use cd to where the file is located  (ez way =>) right click the file go to properties and copy the location then paste "cd [location]" (no "") 
-  Then type "w10&11deb.ps1" followed by enter to run it! (Tab to autocomplete)
  

Via Group Policy
-

-  Open Group Policy Editor
-  Navigate to: Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell
-  Set "Script Execution" to Enabled && "Execution Policy" to "Allow local scripts and remote signed scripts" OR "Allow all scripts"
-  Right click the file w10&11deb.ps1 and select "Run with Powershell" may need to select "Show more options" incase it's not there.

#
  May trigger Anti-Virus as "sus" due to system changes only triggers Bitdefender as far as I know & have seen. To run it open Bitdefender go to "protection" > "Advanced Threat Defense" > "Settings" > Uncheck "Advanced Threat Defense" and re-enable on script completion!
