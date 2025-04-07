# Boot2Root-CTF
Difficulty
This exercise range is aimed at users with a beginner or intermediate level of pen testing and offensive security skills. There are five independent target machines in the scenario, and each machine has two flags that need to be found to complete each challenge.

User
Identify and exploit a vulnerability or misconfiguration to gain user-level access to the target host. Once you gain this level of access, a users.txt file contains the required flag. This file is typically found in the user's home drive or desktop, but each task will tell you where to locate this file.

Root
Once you've gained initial access, you'll need to escalate your privileges to root or administrator level to fully compromise the host. Once you have this level of access, there'll be a root.txt file that contains the required flag. This will typially be found in the root user's home directory on Linux systems or the administrator's desktop for Windows systems, but make sure you check each task will tell you where to locate this file.

Scope
The following assets are deemed to be in scope for this assesment.

Target	IP address	Hostname	Difficulty
Foundation	10.10.20.10	foundation	Beginner
RunMeNot	10.10.20.20	runmenot	Beginner
SourceOfEvil	10.10.20.50	sourceofevil	Beginner
Jason	10.10.20.40	jason	Intermediate
Clocked	10.10.20.30	clocked	Intermediate
Kali
You've been provided RDP access to a Kali host within the same network range. Your Kali instance has outbound internet access on ports 80 and 443, allowing you to install any additional tools you may wish to use.

Social Engineering
No social engineering is required as part of this range environment.
