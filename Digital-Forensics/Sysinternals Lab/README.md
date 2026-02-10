# Sysinternals Lab – CyberDefenders CTF

## Overview
This project documents my forensic analysis of a system compromise involving the **Rozena malware family**.  
The investigation focuses on identifying the **initial infection vector**, analyzing the **malicious process chain**, and documenting the attacker’s **persistence mechanisms** and **command-and-control (C2) infrastructure**.

---

## Challenge Info

- **Platform:** CyberDefenders  
- **Challenge:** Sysinternals  
- **Category:** Endpoint Forensics  
- **Difficulty:** Medium  
- **Case Title:** Sysinternals Endpoint Compromise  

---

## Tools Used

- **Autopsy**  
  Used for deep-dive file system analysis and metadata recovery.

- **VirusTotal**  
  Used to identify the malware family and analyze binary behavior.

- **Timeline Explorer**  
  Used to review and filter NTFS MFT (Master File Table) artifact timelines.

- **Arsenal Image Mounter**  
  Used to mount the forensic disk image for examination.

- **MFTECmd**  
  Used to parse and analyze NTFS Master File Table records.

---

## What This Project Contains

- **High-level Investigation Summary**  
  An overview of the attack stages and key findings (this README).

- **Forensic Report**  
  A structured incident response report detailing all findings.  
   `Report.pdf`

- **Technical Documentation**  
  A step-by-step investigation guide including methodology and screenshots.  
   `Documentation.pdf`

---

## Key Skills Practiced

- **Malware Analysis**  
  Identifying threats using SHA1 hashes and multi-engine detections.

- **Persistence Detection**  
  Locating malicious system services configured for automatic execution.

- **Process Tree Analysis**  
  Mapping parent–child relationships involving `cmd.exe` and dropped binaries.

- **Network Infrastructure Mapping**  
  Investigating `hosts` file modifications to uncover C2 domains and IP addresses.

---

## Detailed Analysis

Comprehensive documentation was prepared to describe the **full step-by-step investigation methodology**, including screenshots and forensic evidence:

- **Forensic Report:** `Report.pdf`  
- **Technical Documentation:** `Documentation.pdf`

---

## Author

**NIZAR ADERBAZ**  
Cybersecurity Student | DFIR & Malware Analysis

