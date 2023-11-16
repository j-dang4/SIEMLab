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

<h2>Installation walk-through:</h2>

<p align="center">
For this project, I will be using an old retired Aspire laptop with an Intel Celeron, 4GB RAM, and 32GB of storage. The laptop had been wiped with a fresh Xubuntu 22.04 installation. It will be used as the headless SIEM server running Wazuh.  <br/>
I've set up SSH server on it along with basic packages, so let's SSH into it! <br/>
<img src="https://i.gyazo.com/1644a5a603408879e60369a70feedeba.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once we've connected to our laptop, we can now begin the installation of the Wazuh SIEM/XDR. I will be referring to the official quickstart documentation found here(https://documentation.wazuh.com/current/quickstart.html) <br/>
Using Curl to download and run the official install .sh script should get the Server, Indexer, and Dashboard central components up and running quickly.<br/>
More info regarding each component can be found here: (https://wazuh.com/install/)
<img src="https://i.gyazo.com/0b1081e43f03b3c326afdfe4853ac0eb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After a few minutes, Wazuh finishes installing and prompts us regarding how we can access our web dashboard. <br/>
<img src="https://i.gyazo.com/554edba3b63aded6ed0a6ebea2fd58ee.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Let's access our dashboard for the first time! Our host's (laptop) IP is 192.168.1.21 and we will be connecting via port 443 in the browser.   <br/>
<img src="https://i.gyazo.com/fa659a2808f89ab6c3fe0969ee20bcdf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wow this is a pretty neat SIEM for being open-source! Since this is only a lab and will remain in our private network, we will not be getting a domain name or configuring SSL.  <br/>
We can see that it has features such as Security Information Management, Auditing and Policy Monitoring, Threat Detection and Response,  Regulatory Compliance, and more!
<br />
 </p>
<br />
 <h2>Configuration Walk-through:</h2>

<br />
<p align:"center">Agents  <br/>
 Now what's the point of a SIEM without any agents to monitor? 
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
