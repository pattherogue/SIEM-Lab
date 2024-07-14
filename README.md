<h1>Analyzing Global RDP Attacks: Geolocation Insights with Microsoft Sentinel</h1>

<h2>Lab Overview</h2>
<b>In this lab, I demonstrate the Microsoft Sentinel (SIEM) setup connected to a live virtual machine configured as a honeypot. Witness real-time observations of RDP brute force attacks originating from various global locations. Explore how a custom PowerShell script retrieves and visualizes attackers' geolocation data on a Microsoft Sentinel Map.
</b>
<br />
<br />

<p align="center">
<img src="https://imgur.com/8DONyCB.jpeg" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Developed to extract and analyze RDP failed logon logs from the Windows Event Viewer.

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> Utilizes a third-party API for IP address geolocation. Integrated into the PowerShell script to fetch geographic data, enhancing analysis of global security threat distribution.

<h2>Incoming Attacks from Brazil: Custom Logs with Geolocation Data</h2>

<p align="center">
<img src="https://imgur.com/ntRTcDt.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<p align="center">
<img src="https://imgur.com/ECxzo3b.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>Global Map of Attacks Within 24 Hours: Custom Logs with Geolocation Data</h2>

<p align="center">
<img src="https://imgur.com/z7hBHOh.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
