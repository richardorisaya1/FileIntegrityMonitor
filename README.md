# File Integrity Monitor

<h2>Description</h2>
This project demonstrates the process of how a File Integrity Monitor works. In this example, the program is configured to create a new baseline of file names and hashes that point to a specific folder if option A is selected. Whenever this program is run again with the user clicking option b, then it will alert them of all the files that have been deleted, modified, or added until a new baseline is created. 
<br />


<h2>Languages Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
<b>Creating a new baseline to collect the current hash information for the files (Option "a"):<br/> <br/>
<img src="https://imgur.com/ztFja2m.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
<b>The baseline with the current file names and hashes:<br/>  <br/>
<img src="https://imgur.com/IVfz941.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
<b>Choosing option to begin monitoring the files within the saved baseline (Option b)<br/>  <br/>
<img src="https://imgur.com/4P7uWo9.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
<b>Alert when deleting file "Deletion - Sentinel Forge Corp." <br/>  <br/>
<img src="https://imgur.com/g4CayHg.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
<b>Alert when modifying a file "Credentials - Sentinel Forge Corp." <br/>  <br/>
<img src="https://imgur.com/iYzgHft.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />
<b>Alert when adding a file "Test.txt" <br/>  <br/>
<img src="https://imgur.com/yIk4Pt9.png" height="80%" width="80%" alt="File Integrity Monitor"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
