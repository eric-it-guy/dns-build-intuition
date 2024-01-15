<h1>DNS - Building Intuition</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Using the Active Directory we created in the previous lab, we connect/log into DC-1 and Client-1 with our domain admin and admin accounts. We then perform a local DNS cache exercise by pinging DC-1's mainframe, observe local DNS cache, & then flush the cache. Finally for our CNAME Record Exercise, we create a CNAME record that points to the host "search" to a familiar website, try to ping "search" from Client-1, and then nslookup "search and observe the results of the CNAME record. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>DNS</b>
- <b>IP Addressing</b> 

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
- <b>Windows Server</b> (2022)
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="DNS - Building Intuition"/>
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
