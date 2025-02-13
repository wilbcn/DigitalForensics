# 🔍 Recovering Deleted Files & Investigating Potential Threats

## 📖 Overview
This project demonstrates a **forensic investigation** into **deleted files** within a **Windows virtual machine (VM)**. The objective is to **recover files that were moved to the Recycle Bin**, analyze them for **potential threats**, and determine whether they indicate malicious intent.

We leverage **RBCmd.exe**, a **Windows forensic tool**, to extract and restore deleted files. Additionally, we use **metadata analysis, hashing, and threat intelligence tools** such as **ExifTool, CSVQuickViewer, and VirusTotal** to conduct a thorough investigation.

### **🔹 Real-World Scenario**
This is a **scenario-based project** where an insider attempts to **cover their tracks** by moving potentially malicious files into the **Recycle Bin**. However, they fail to empty it, allowing forensic recovery to take place.

💡 **This project was inspired by my learning in the** [**Blue Team Level 1**](https://www.securityblue.team/blue-team-level-1) **course, reinforcing key digital forensics concepts in a controlled environment.** By applying **real-world investigative techniques** within a secure VM, I am deepening my understanding of forensic methodologies while gaining **practical experience** with **industry-standard tools**.

You can find the setup of the secure VM in AWS here -> [EC2 VM](https://github.com/wilbcn/DigitalForensics/blob/main/AWS-SecureVM/README.md)

---

## 🔧 Tools & Acknowledgements
| **Tool**            | **Purpose** |
|---------------------|------------|
| [RBCmd.exe](https://github.com/EricZimmerman/RBCmd) | Recovering files from the Recycle Bin |
| [ExifTool](https://exiftool.org/) | Extracting metadata from files |
| [CSVQuickViewer](https://sourceforge.net/projects/csvquickviewer/) | Analyzing forensic CSV output |
| [VirusTotal](https://www.virustotal.com/gui/home/upload) | Checking files & hashes for malware |

---

## 🎯 Project Goals
- 🕵 **Create & simulate suspicious file activity** (malicious files moved to Recycle Bin).
- 🔍 **Identify and recover deleted files** using **RBCmd.exe**.
- 📝 **Analyze recovered files** with **ExifTool** and **CSVQuickViewer**.
- 🛡 **Verify file integrity & research threats** via **SHA-256 hashing & VirusTotal**.

---


---

### 📌 **Why This Project Matters**
This project simulates a **realistic forensic investigation**, demonstrating **hands-on analysis techniques** that are directly applicable in **blue team cybersecurity, digital forensics, and incident response** roles.

If you have any feedback or questions, feel free to connect! 🚀
