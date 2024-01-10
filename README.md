# PowershellDiskWipe
Easy disk format walkthrough using CLI
<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. To begin make sure you downloaded or copied the code in the repo, if downloaded look for .\Pwipe.ps1. if you copied the raw code save in a text file and name it .\Pwipe.ps1 and make sure to run your powershell from the location where you saved the file. for example below I saved it to my desktop which you can see the directory I am using powershell in is my desktop. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization. 5 passes is the Department of Defense minimum standard for those goverment employees out there.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows 11</b> (22H2) 
<h2>Program walk-through:</h2>

<p align="center">

  Begin by pushing the windows key, typing in powershell and click run as administrator to
Launch the utility: <br/>
<img src="https://i.imgur.com/AD3KRS9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Windows 11 users may be thrown a error that running scripts is disabled. If it happens to you below is the fix
<img src="https://i.imgur.com/ACqoaQL.png" height="80%" width="80%"/>
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
