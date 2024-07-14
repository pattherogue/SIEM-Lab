<h1>Analyzing Global RDP Attacks: Geolocation Insights with Azure Sentinel</h1>

<h2>Description</h2>
<b>This repository contains a PowerShell script designed to parse Windows Event Log data and analyze failed RDP (Remote Desktop Protocol) attacks. It leverages a third-party API to gather geographic information about the attackers' locations.
</b>
<br />
<br />
<h2>Demo Overview</h2>
<b>In this demonstration, I showcase the setup of Azure Sentinel (SIEM) connected to a live virtual machine acting as a honeypot. Experience real-time observations of RDP brute force attacks originating from diverse global locations. Explore how a custom PowerShell script retrieves and visualizes attackers' geolocation data on an Azure Sentinel Map.
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

<h2>Attacks from Brazil coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://imgur.com/ntRTcDt.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<p align="center">
<img src="https://imgur.com/ECxzo3b.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

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