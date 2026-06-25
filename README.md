# Vulnerability Scanner - Mini Project

## Project Overview

The Vulnerability Scanner is a Python-based security tool designed to identify common vulnerabilities in a network or web application environment. The tool scans target hosts for open ports, detects running services and software versions, identifies weak configurations, and generates a vulnerability assessment report.

This project helps in understanding the fundamentals of penetration testing and vulnerability assessment.

---

## Objectives

* Scan a target system for open ports.
* Detect active services and software versions.
* Identify weak or insecure services.
* Generate a simple vulnerability report.
* Gain practical knowledge of cybersecurity concepts.

---

## Features

* Open port scanning.
* Service and version detection.
* Detection of insecure services such as FTP and Telnet.
* Automatic report generation.
* Command-line interface for easy usage.

---

## Technologies Used

* **Programming Language:** Python 3
* **Libraries:**

  * socket
  * python-nmap
  * datetime

---

## Prerequisites

Before running the project, ensure that the following software is installed:

* Python 3.x
* Nmap

### Install Python Module

```bash
pip install python-nmap
```

---

## Installation

1. Clone or download the project files.

2. Install Nmap on your system.

3. Install the required Python library:

```bash
pip install python-nmap
```

---

## Project Structure

```text
VulnerabilityScanner/
│
├── vulnerability_scanner.py
├── vulnerability_report.txt
├── README.md
```

---

## Usage

Run the application using the following command:

```bash
python vulnerability_scanner.py
```

Enter the target IP address when prompted:

```text
Enter Target IP Address: 192.168.1.1
```

---

## Sample Output

```text
Scanning Target: 192.168.1.1

Host: 192.168.1.1
State: up

Port: 21 | Service: ftp | Version: vsFTPd
Warning: FTP service detected.

Port: 22 | Service: ssh | Version: OpenSSH

Port: 23 | Service: telnet | Version: BusyBox
Warning: Telnet detected.

Report generated successfully: vulnerability_report.txt
```

---

## Generated Report

The scanner automatically creates a report file named:

```text
vulnerability_report.txt
```

The report contains:

* Scan date and time
* Host information
* Open ports
* Detected services
* Vulnerability warnings

---

## Expected Outcome

After completing this project, users will:

* Understand network scanning techniques.
* Learn basic vulnerability assessment.
* Gain practical experience with penetration testing tools.
* Develop automated security reporting skills.

---

## Future Enhancements

* Add a graphical user interface (GUI).
* Integrate CVE vulnerability databases.
* Export reports to PDF format.
* Support multi-host scanning.
* Implement web vulnerability detection (SQL Injection, XSS, etc.).

---

## Disclaimer

This tool is intended for educational and authorized security testing purposes only. Users should scan only systems and networks for which they have explicit permission. Unauthorized scanning may violate organizational policies and legal regulations.

---

## Author

**Name:** ______________________

**Department:** B.Tech - Computer Science and Engineering

**Institution:** ______________________
