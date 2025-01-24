Splunk SIEM LAB Project 

##Overview 
This repository contains the configurations for setting up and using SPLUNK SIEM for security monitoring. This lab involves ingesting logs, creating dashboards, simulating security events, and generating alerts. 

## Lab Objectives 
- Install Splunk on A virtual machine
- Installing data forwarder
- Configure data inputs
- Create dashboards and alerts for monitoring security events
- Simulate security incidents and analyze data in Splunk
- Investigate incidents using SPL queries 


## Steps 

1. ** Installing SPLUNK Version 9.4.0 on hyper-v**:

Description: In this step, I installed Splunk enterprise on a virtual machine and accessed the splunk web interface.

Key Actions: 
- Downloaded and installed splunk from [Splunk Downloads](https://www.splunk.com/en_us/download/splunk-enterprise/thank-you-enterprise.html)
- Installed Splunk using the default installation options
- Logged into Splunk Web at http://localhost:8000

2. **Installing Data forwarder**

Description: In this step, I installed the universal data forwarder 

Key Actions:
- Downloaded and installed data forwarder from from (https://www.splunk.com/en_us/download/universal-forwarder.html?locale=en_us)
- Configured server name and receiver port number, 9997
- Added splunk server as forwarder target on windows machine

3. Configuring data inputs

- Selected "Security, System, Application" to be monitored
- Set source type, host, and index


- 

