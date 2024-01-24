<h1>Elastic SIEM HomeLab</h1>

 

<h2>Description</h2>
In this Home lab I successfully set up and configured a Elastic Stack SIEM. With demonstrated proficiency in deploying a Kali Linux VM, configuring Elastic Agents for log collection, and forwarding data to the SIEM for effective security event monitoring. Additionally, I gained hands-on experience in generating and analyzing security events using Nmap on Kali Linux. I also developed a custom dashboard in Elastic SIEM for visualizing security events, which shows data interpretation and pattern recognition. Furthermore, in this lab I successfully created and tested alert rules for detecting specific security events.
<br />

<h2>Environments and Applications Used </h2>

- <b>Kali Linux</b>
- <b>Elastic Cloud</b>
- <b>VirtualBox</b>

<h2>Program walk-through:</h2>

<p align="center">
Installation of Elastic Agent: <br/>
<img src="https://imgur.com/VBOWnOZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Elastic Agent Successfully Installed:  <br/>
<img src="https://imgur.com/3CYWi12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nmap scan of localhost to create some activity in Elastic: <br/>
<img src="https://imgur.com/88mbxN6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Details of log entry and also shows the prior nmap scan:  <br/>
<img src="https://imgur.com/fWPEMMq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Bar chart created within Elastic cloud showing data from host:  <br/>
<img src="https://imgur.com/2kxxwAR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
More Data Ingested to the cloud from new nmap scan:  <br/>
<img src="https://imgur.com/R8LRhOm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of Security Alert:  <br/>
<img src="https://imgur.com/B3UNaDq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Adding rules to alert:  <br/>
<img src="https://imgur.com/Ck36st8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Selecting where the alerts would go to:  <br/>
<img src="https://imgur.com/4KWrF31.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Bar chart showing all new data ingested from the host:  <br/>
<img src="https://imgur.com/liRkG3A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
