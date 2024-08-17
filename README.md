## Global RDP Attack Analysis with Microsoft Sentinel

## Project Overview
This project showcases the deployment of Microsoft Sentinel (Security Information and Event Management, SIEM) connected to a live virtual machine configured as a honeypot. The lab captures and analyzes real-time Remote Desktop Protocol (RDP) brute force attacks originating from various global locations.

A custom PowerShell script was developed to retrieve failed RDP logon attempts from the Windows Event Viewer. This script integrates with the ipgeolocation.io API to map the geographic locations of the attackers, allowing for a comprehensive visualization of global threat activity within Microsoft Sentinel.

<p align="center">
<img src="https://imgur.com/8DONyCB.jpeg" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

## Key Features
- Real-Time Attack Monitoring: Witness live RDP brute force attacks from global sources targeting a honeypot virtual machine.
- Geolocation Mapping: Custom PowerShell script pulls attacker IP addresses and maps their locations using the ipgeolocation.io API.
- Visual Data Representation: Attacks are visualized on a global map within Microsoft Sentinel, showcasing the distribution of threats over a 24-hour period.

## Technologies Used
- PowerShell: Scripted to extract and analyze failed RDP logon events from the Windows Event Viewer.
- ipgeolocation.io API: Integrated to retrieve geographic data for each attacking IP address, enriching the security analysis with global context.

## Visual Insights
- Incoming Attacks from Brazil
- Example of geolocated attack data showing concentrated RDP brute force attempts originating from Brazil.

<p align="center">
<img src="https://imgur.com/ntRTcDt.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<p align="center">
<img src="https://imgur.com/ECxzo3b.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

## Global Map of Attacks Within 24 Hours
- A comprehensive visualization of all detected RDP attacks within the past 24 hours, displayed on a Microsoft Sentinel map with custom log integration.

<p align="center">
<img src="https://imgur.com/z7hBHOh.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

## Project Impact
- This project highlights the importance of global threat visibility and the capability of Microsoft Sentinel to provide actionable insights into security incidents. By integrating geolocation data into SIEM, organizations can better understand the origin and scale of threats, ultimately improving their response strategies.
