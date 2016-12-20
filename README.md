# PoSh-R2
PowerShell - Rapid Response (PoSH-R2)... For the incident responder in you!
        
PoSH-R2 is a set of Windows Management Instrumentation interface (WMI) scripts that investigators and forensic analysts can use to retrieve information from a compromised (or potentially compromised) Windows system. The scripts use WMI to pull this information from the operating system. Therefore, this script will need to be executed with a user that has the necessary privileges.
<br>
<br>
In a single execution, PoSH-R2 will retrieve the following data from an individual machine or a group of systems:
<br>
<br>
&#160;&#160;&#160;&#160;- Autorun entries <br>
&#160;&#160;&#160;&#160;- Disk info <br>
&#160;&#160;&#160;&#160;- Environment variables <br>
&#160;&#160;&#160;&#160;- Event logs (50 lastest) <br>
&#160;&#160;&#160;&#160;- Installed Software <br>
&#160;&#160;&#160;&#160;- Logon sessions <br>
&#160;&#160;&#160;&#160;- List of drivers <br>
&#160;&#160;&#160;&#160;- List of mapped network drives <br>
&#160;&#160;&#160;&#160;- List of running processes <br>
&#160;&#160;&#160;&#160;- Logged in user <br>
&#160;&#160;&#160;&#160;- Local groups <br>
&#160;&#160;&#160;&#160;- Local user accounts <br>
&#160;&#160;&#160;&#160;- Network configuration <br>
&#160;&#160;&#160;&#160;- Network connections <br>
&#160;&#160;&#160;&#160;- Patches <br>
&#160;&#160;&#160;&#160;- Scheduled tasks with AT command <br>
&#160;&#160;&#160;&#160;- Shares <br>
&#160;&#160;&#160;&#160;- Services <br>
&#160;&#160;&#160;&#160;- System Information <br>


# Usage <br>
1. Call upon the script from the shell and follow the prompts. <br>
2. Data will be saved to a new directory called "PoSH_R2--Results" within the same directory from which thise script was executed from. <br>

# Screenshots <br>
<br>
Running the script <br>
![Alt text](https://github.com/WiredPulse/PoSh-R2/blob/master/screenshots/1-Script_Execution.png?raw=true "Optional Title")<br>
<br>
A listing of the results written to csv files
![Alt text](https://github.com/WiredPulse/PoSh-R2/blob/master/screenshots/2-Results.png?raw=true "Optional Title")<br>
<br>
Reading the data back into PowerShell using out-gridview
![Alt text](https://github.com/WiredPulse/PoSh-R2/blob/master/screenshots/3-Results2.png?raw=true "Optional Title")
