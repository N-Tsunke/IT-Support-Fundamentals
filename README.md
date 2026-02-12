# Technical Support Fundamentals – Windows Troubleshooting Report

# Windows Troubleshooting Practical Task

This repository documents a step-by-step Windows troubleshooting exercise, including system checks, simulating an internet disconnection, and performing troubleshooting steps to restore connectivity.  

---

## PART 1: System Check

### 1. Check System Specifications

**Steps:**
1. Press `Windows + R`
2. Type `msinfo32` and press Enter.
3. Note the following information:  
   - OS Name  
   - Version  
   - System Manufacturer  
   - System Model  
   - Processor  
   - Installed RAM  
   - System Type  

**Screenshot:**  
![Open System Information](Open System Information.png)

---

### 2. Check Network Status

**Option A: Using Settings**
1. Go to `Start → Settings → Network & Internet`
2. Check network status (Connected / Not connected).  

**Screenshot:**  
![Network Status](Internet Disconnection Before.png)

**Option B: Using Command Prompt**
1. Press `Windows + R` → type `cmd` → press Enter  
2. Type `ipconfig` and press Enter  
3. Note the following information:  
   - IPv4 Address  
   - Subnet Mask  
   - Default Gateway  

**Screenshot:**  
![Command Prompt Network Info](Using Command Prompt.png)

---

## PART 2: Simulate a Basic Issue (Internet Disconnection)

**Steps to Simulate Internet Disconnection:**
- Turn off Wi-Fi manually **or**  
- Disable the network adapter:  
  1. Press `Windows + R` → type `ncpa.cpl` → press Enter  
  2. Right-click your Wi-Fi adapter → Click `Disable`  

**Screenshot:**  
![Internet Disconnected](Internet Disconnection Before.png)

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



