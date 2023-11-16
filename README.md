<h1>[Home Lab] Deploying Wazuh SIEM and XDR </h1>



<h2>Description</h2>
This project consists of upcycling a useless old laptop and converting it into a headless SIEM to monitor my home network and endpoints
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 
- <b>Various tools</b>
- [Wazuh Open Source SIEM & XDR](https://wazuh.com/)
<h2>Environments Used </h2>

- <b>Xubuntu 22.04</b>

<h2>Program walk-through:</h2>

<p align="center">
For this project, I will be using an old retired Aspire laptop with an Intel Celeron, 4GB RAM, and 32GB of storage. The laptop had been wiped with a fresh Xubuntu 22.04 installation. It will be used as the headless SIEM server running Wazuh.  <br/>
I've set up SSH server on it along with basic packages, so let's SSH into it! <br/>
<img src="https://i.gyazo.com/1644a5a603408879e60369a70feedeba.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once we've connected to our laptop, we can now begin the installation of the Wazuh SIEM Server. I will be referring to the official quickstart documentation found here(https://documentation.wazuh.com/current/quickstart.html) <br/>
<img src="https://i.gyazo.com/0ec8ce4244073376be80490d8de14cbc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
