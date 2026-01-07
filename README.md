## Linux Forensics and Memory Analysis Lab

### Overview
This repository documents a hands-on digital forensics laboratory focused on
Linux system forensic analysis and volatile memory investigation.

The activity was developed as part of the Digital Forensics and Cyber Threat
Intelligence microcredential (Week 4).

The original report was written in Portuguese, as the course was taught in Portuguese.
This repository aims to demonstrate practical DFIR skills, forensic methodology,
and technical reasoning in a controlled academic environment.

---

### Objectives
- Perform forensic analysis on Linux systems
- Analyze Linux file systems and storage artifacts
- Reconstruct the Linux boot process
- Identify installed software and services
- Detect suspicious persistence mechanisms
- Perform memory forensics using Volatility
- Extract processes, commands, and credentials from memory dumps

---

### Lab Environment
- Analysis Systems: Linux forensic images
- Memory Images: Volatile memory dumps (MemLabs 0)
- Analysis Tools:
  - Linux command-line utilities
  - Sleuth Kit
  - Volatility Framework
  - Strings
  - Hexadecimal analysis tools

All analysis was performed on forensic copies to preserve evidence integrity.

---

## Linux Forensic Analysis

### File System and Storage Artifacts
- Analyzed Linux file system structures
- Identified mounted partitions and storage devices
- Inspected directory hierarchies for anomalies
- Reviewed file timestamps for suspicious activity

---

### Boot Process Reconstruction
- Analyzed GRUB configuration files
- Reviewed kernel boot parameters
- Inspected systemd services and startup scripts
- Identified services configured to start automatically

This analysis allows reconstruction of system behavior from boot to runtime.

---

### Installed Software and Services
- Enumerated installed packages
- Identified active and inactive services
- Correlated installed software with system timelines
- Detected potentially unwanted or suspicious packages

---

## Memory Forensics (Volatility)

### Memory Image Profiling
- Identified the correct operating system profile
- Validated memory image integrity before analysis

---

### Process and Command Analysis
- Enumerated running and terminated processes
- Identified parent-child process relationships
- Recovered executed shell commands
- Identified interactive terminal sessions

---

### Advanced Memory Analysis
- Extracted environment variables
- Identified suspicious decoded strings
- Performed XOR decoding to reveal hidden data
- Recovered NTLM password hashes from memory

---

### Key Findings
- Linux boot configuration can reveal persistence mechanisms
- Installed services may indicate unauthorized modifications
- Memory analysis exposes runtime-only artifacts
- Credentials and commands can be recovered from volatile memory
- Combined disk and memory forensics provide full incident context

---

### Ethical and Legal Considerations
- All activities were conducted in a controlled academic environment
- No real systems, users, or personal data were involved
- Forensic best practices and ethical guidelines were respected
- The work was performed strictly for educational purposes

---

