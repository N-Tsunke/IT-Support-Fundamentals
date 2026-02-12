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

[Open System Information](<img width="1487" height="830" alt="Open System Information" src="https://github.com/user-attachments/assets/01dad27f-b2fd-436e-a33b-667228c68d72" />


*Figure 1: System Information window displaying operating system version, processor, RAM, and system type.*

---

## 2. Internet Disconnection Before

To simulate a troubleshooting scenario, the internet connection was intentionally disconnected.

### Symptoms Observed:

- Unable to access websites
- Network icon showed "No Internet Access"
- Browser displayed connection error

### Screenshot

[Internet Disconnection Before]<img width="1127" height="627" alt="Internet Disconnection Before" src="https://github.com/user-attachments/assets/d1f389a1-fb68-4fae-9c95-43353554d91b" />


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

![Check Physical Adapter Status](images/check-physical-adapter-status.png)

*Figure 3: Network adapter status showing whether the physical connection is enabled or disabled.*

---

## 4. Using Command Prompt

The Command Prompt was used to perform network troubleshooting commands to restore internet connectivity.

### Action Performed:

- Opened Command Prompt as Administrator
- Executed `ipconfig /release` to drop the current IP address
- Executed `ipconfig /renew` to request a new IP address from the router
- Executed `ipconfig /flushdns` to clear the DNS cache

These steps help resolve IP conflicts and DNS issues that can prevent internet access.

### Screenshot

![Using Command Prompt](images/using-command-prompt.png)

*Figure 4: Command Prompt displaying execution of ipconfig commands to troubleshoot network connectivity.*

---

## 5. Run Network Troubleshooter

After using Command Prompt tools, the built-in Windows Network Troubleshooter was executed.

### Action Performed:

- Opened Network & Internet Settings
- Selected "Network Troubleshooter"
- Allowed Windows to detect and fix network problems automatically

This tool diagnoses and resolves common network issues.

### Screenshot

![Run Network Troubleshooter](images/run-network-troubleshooter.png)

*Figure 5: Windows Network Troubleshooter detecting and resolving connectivity issues.*

---

## Conclusion

The internet connectivity issue was successfully diagnosed and resolved using a structured troubleshooting approach.

Steps followed:

1. Verified system specifications  
2. Confirmed internet disconnection  
3. Checked physical network adapter status  
4. Used Command Prompt networking tools  
5. Ran Windows Network Troubleshooter  

## Key Learning Outcomes

- Learned how to check system specifications  
- Verified network connectivity using command-line tools  
- Simulated a network issue  
- Applied troubleshooting steps to restore connectivity  

---

## Author

Nthabiseng Tsunke  
IT Support Learnership – CAPACITI  
Technical Support Fundamentals



