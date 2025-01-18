# Forensic Analysis of Digital Evidence from Android Devices

This repository contains the dissertation project titled **"Forensic Analysis of Digital Evidence from Android Devices"**, submitted as part of the requirements for the Master of Science degree in Forensic Science at Gujarat University. The project explores tools, methodologies, and practical approaches for analyzing volatile and non-volatile memory of Android devices from a forensic perspective.

---

## 📌 Project Overview

### **Aim**
To contribute to the growing field of Android device forensics by providing a comprehensive analysis of memory acquisition tools and techniques. This study focuses on forensic investigation challenges related to volatile and non-volatile memory of Android devices.

### **Scope**
Given the increasing prevalence and misuse of Android devices due to their open-source nature, this project emphasizes the importance of reliable memory analysis for forensic investigators. The study is limited to identifying evidence of user activities on Android devices.

---

## 🛠️ Tools and Technologies

### **Non-Volatile Memory Tools**
- **EaseUS Mobisaver for Android**: Effective for recovering deleted or lost files.
- **FonePaw Android Data Recovery**: Detects and restores various file types.
- **MOBILedit Forensic**: Extracts comprehensive phone data, including encrypted information.
- **AFLogical (Linux-based)**: Facilitates logical acquisition of Android device data.

### **Volatile Memory Tool**
- **LiME (Linux Memory Extractor)**: Captures full volatile memory from Android devices with minimal interference, ensuring forensically sound results.

---

## 🚀 Methodology

1. **Preparation**: Configure Android devices in USB debugging mode.
2. **Tool Usage**:
   - For non-volatile memory: Tools like EaseUS, FonePaw, and MOBILedit were tested for retrieving user files, contacts, messages, and media.
   - For volatile memory: LiME was employed to capture and analyze RAM data.
3. **Analysis**:
   - Extracted data was analyzed for evidence such as communication logs, deleted messages, and encrypted files.
   - Results were compared across tools to determine efficiency and reliability.
4. **Challenges**: Issues such as tool compatibility, time-consuming processes, and incomplete extractions were documented.

---

## 📊 Results and Observations

- **Non-Volatile Memory**:
  - Recovered significant data, including contacts, call logs, SMS, media, and app backups.
  - MOBILedit emerged as the most comprehensive tool for non-volatile memory.
- **Volatile Memory**:
  - LiME proved effective for full memory acquisition with minimal system impact.
  - Successfully captured encryption keys, buffers, and temporary data critical for investigations.

---

## 📁 Repository Contents

- **Dissertation.pdf**: Complete dissertation detailing the methodology, tools, and findings.
- **Tools**: Scripts and setup guides for tools like LiME and AFLogical.
- **Results**: Sample outputs and recovered data.
- **README.md**: This project overview file.

---

## 🛡️ Disclaimer

This project was conducted in an academic setting and for ethical purposes. All tools and techniques described here should only be used with proper authorization and compliance with applicable laws.

---

## 🔗 References

- **EaseUS Mobisaver**: [https://www.easeus.com/android-data-recovery-software](https://www.easeus.com/android-data-recovery-software)
- **LiME**: [https://github.com/504ensicslabs/lime](https://github.com/504ensicslabs/lime)
- **AFLogical**: [https://santoku-linux.com](https://santoku-linux.com)

For any inquiries or collaboration opportunities, feel free to connect with me on [LinkedIn](https://linkedin.com/in/parth-lakhalani).
