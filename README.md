# Comparative Review of Penetration Testing Tools

![Cyber Security](https://img.shields.io/badge/Project-Cyber%20Security-red)
![University Project](https://img.shields.io/badge/Type-Final%20Year%20Project-blue)
![Tools](https://img.shields.io/badge/Tools-Nmap%20%7C%20Burp%20Suite%20%7C%20SQLmap%20%7C%20Metasploit-orange)

## Overview

This repository contains my final-year cybersecurity project, **Comparative Review of Penetration Testing Tools**.

The project evaluates four penetration-testing tools in a controlled virtual laboratory:

- **Nmap** — network discovery and reconnaissance
- **Burp Suite** — web application security testing
- **SQLmap** — SQL injection testing
- **Metasploit** — vulnerability exploitation

The tools were tested against **Metasploitable 2**, an intentionally vulnerable virtual machine, using an isolated VirtualBox environment.

## Project Aim

The project aimed to identify suitable criteria for evaluating penetration-testing tools, implement the selected tools within a controlled environment, conduct practical testing, and compare their capabilities and performance.

The comparison focused on:

- User Interface
- Reporting & Analysis
- Performance

## Repository Structure

```text
comparative-penetration-testing/
│
├── 01-project-overview/
│   └── README.md
│
├── 02-lab-environment/
│   └── README.md
│
├── 03-nmap/
│   └── README.md
│
├── 04-burp-suite/
│   └── README.md
│
├── 05-sqlmap/
│   └── README.md
│
├── 06-metasploit/
│   └── README.md
│
├── 07-comparison-results/
│   └── README.md
│
├── 08-project-management/
│   └── README.md
│
├── screenshots/
│   ├── lab-environment/
│   ├── nmap/
│   ├── burp-suite/
│   ├── sqlmap/
│   └── metasploit/
│
└── report/
    └── FYP-Final-Report.pdf
```

## Lab Environment

```text
                 Host Machine
                      |
                   VirtualBox
                      |
              Custom NAT Network
                 /           \
                /             \
        Kali Linux        Metasploitable 2
        Pen-testing         Vulnerable
           tools              target
```

### Hardware

| Component | Specification |
|---|---|
| CPU | AMD Ryzen 7 5800X |
| RAM | 32 GB |
| Storage | 500 GB SSD |
| Virtualisation | VirtualBox |

## Methodology

The practical implementation followed a controlled penetration-testing workflow:

```text
Lab Setup
   ↓
Reconnaissance
   ↓
Scanning & Enumeration
   ↓
Web Application Testing
   ↓
SQL Injection Testing
   ↓
Exploitation
   ↓
Comparison & Analysis
```

## Tools

| Tool | Primary Focus |
|---|---|
| Nmap | Network reconnaissance and vulnerability scanning |
| Burp Suite | Web application security testing |
| SQLmap | SQL injection and database enumeration |
| Metasploit | Exploitation and post-exploitation |

## Key Results

The project recorded the following resource measurements:

| Tool | RAM Usage | CPU Usage | Memory Usage |
|---|---:|---:|---:|
| Nmap | 41.94 MB | 4.0% | 0.6% |
| Burp Suite | 780 MB | 0.4% | 11% |
| SQLmap | 62.91 MB | 92.8% | 0.9% |
| Metasploit | 433 MB | 1.3% | 6.1% |

The project concluded that each tool has different strengths and that the most suitable tool depends on the penetration-testing scenario.

## Ethical Scope

All practical testing documented in this repository was conducted against the intentionally vulnerable **Metasploitable 2** virtual machine within the controlled laboratory environment.

The project report states that the virtual machines contained fake data and were used for security testing purposes.

## Documentation

The repository deliberately separates the project into smaller sections rather than reproducing the full academic report as one long README.

For the complete academic submission, see:

**[Final Year Project Report](./report/FYP-Final-Report.pdf)**

## Academic Project

**Degree:** BSc (Hons) Cyber Security & Digital Forensics  
**Project:** Comparative Review of Penetration Testing Tools  
**Supervisor:** Dr Hu Yuan  
**Date:** 14/04/2024
