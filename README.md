# Technical Support Fundamentals – Windows Troubleshooting Report

## Overview

This project demonstrates a Windows system check and troubleshooting process performed to identify and resolve an internet connectivity issue.

The objectives were to:

- Verify system specifications
- Identify network connectivity problems
- Check physical network adapter status
- Use Command Prompt troubleshooting tools
- Run the built-in Windows Network Troubleshooter

---

## 1. Open System Information

The first step was to verify the system specifications to confirm the operating system version and hardware details.

### Details Verified:

- Windows Version: Windows 10 Pro (64-bit)
- Processor: Intel Core i5
- Installed RAM: 8GB
- System Type: 64-bit Operating System

### Screenshot

![Open System Information]
(images/open-system-information.png)


*Figure 1: System Information window displaying operating system version, processor, RAM, and system type.*

---

## 2. Simulate a Basic Issue (Internet Disconnection)

To simulate a troubleshooting scenario, the internet connection was intentionally disconnected.

### Symptoms Observed:

- Unable to access websites
- Network icon showed "No Internet Access"
- Browser displayed connection error

### Screenshot

![Internet Disconnection Before]
(images/internet-disconnection-before.png)

*Figure 2: Network status showing “No Internet Access” before troubleshooting.*

---

## 3. Check Physical Adapter Status

The next step was to verify whether the network adapter was enabled and functioning correctly.

### Action Performed:

- Opened Network & Internet Settings
- Checked Ethernet/Wi-Fi adapter status
- Confirmed whether the adapter was enabled

This step ensures the issue is not caused by a disabled or disconnected network adapter.

### Screenshot

![Check Physical Adapter Status](
images/check-physical-adapter-status.png)

*Figure 3: Network adapter status showing whether the physical connection is enabled or disabled.*

---

## 4. Using Command Prompt

Command Prompt was opened as Administrator to perform advanced troubleshooting.

### Commands Used:

```bash
ipconfig /release
ipconfig /renew
ipconfig /flushdns

## Issue Resolution

After performing the troubleshooting steps:

- Internet connectivity was successfully restored  
- System was able to access websites  
- Network status returned to normal  

**Screenshot:**  
*(Insert screenshot here showing successful internet connection, e.g., browser loading a website or successful `ping google.com` results.)*

---

## Key Learning Outcomes

- Learned how to check system specifications  
- Verified network connectivity using command-line tools  
- Simulated a network issue  
- Applied troubleshooting steps to restore connectivity  

---

## Tools Used

- Command Prompt (ipconfig, ping, flushdns)  
- Windows Network Settings  
- GitHub (Documentation and reporting)
