# Technical Support Fundamentals – Windows Troubleshooting Report

# Windows Troubleshooting Practical Task

This repository documents a step-by-step Windows troubleshooting exercise, including system checks, simulating an internet disconnection, and performing troubleshooting steps to restore connectivity.  

---

## PART 1: System Check

### 1. Check System Specifications

**Steps:**
1. Note the following information:  
   - OS Name  
   - Version  
   - System Manufacturer  
   - System Model  
   - Processor  
   - Installed RAM  
   - System Type  

**Screenshot:**  
[Open System Information]<img width="1487" height="830" alt="Open System Information" src="https://github.com/user-attachments/assets/33fce64f-7fbd-42ff-ad28-e124ab3d4650" />


---

### 2. Check Network Status

**Option A: Using Settings**
1. Check network status (Connected / Not connected).  

**Screenshot:**  
[Network Status]<img width="1434" height="779" alt="Network Status (Connected or Disconnected)" src="https://github.com/user-attachments/assets/1b437a67-1a09-4e29-be5a-ce921c47c7c0" />


**Option B: Using Command Prompt**  
1. Note the following information:  
   - IPv4 Address  
   - Subnet Mask  
   - Default Gateway  

**Screenshot:**
[Command Prompt Network Info](Using Command Prompt.png)

---

## PART 2: Simulate a Basic Issue (Internet Disconnection)

**Steps to Simulate Internet Disconnection:**
- Turn off Wi-Fi manually **or**  
- Disable the network adapter:  
  2. Right-click your Wi-Fi adapter → Click `Disable`  

**Screenshot:** 
[Internet Disconnected](<img width="1120" height="592" alt="Check Physical Adapter Status" src="https://github.com/user-attachments/assets/4ecff3f6-a96a-46bb-840d-fa6dbd1ef2c8" />

---

## PART 3: Troubleshooting Steps

### Step 1: Check Physical / Adapter Status
1. Ensure Wi-Fi is turned ON.  
2. Re-enable the network adapter: Right-click → Enable  

**Screenshot:**  
![Check Physical Adapter Status](Check Physical Adapter Status.png)

---

### Step 2: Run Network Troubleshooter
1. Go to `Settings → Network & Internet → Advanced Network Settings`  
2. Click `Network Troubleshooter` and follow prompts.  

**Screenshot:**  
![Network Troubleshooter Results](Using Command Prompt.png)


---

### Step 3: Use Command Prompt to Fix
1. Open Command Prompt as Administrator  
2. Run the following commands:


bash
ipconfig /release
ipconfig /renew
ipconfig /flushdns


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



