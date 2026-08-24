# 07 — Comparison & Results

## Evaluation Criteria

The project compared the four tools using:

1. User Interface
2. Reporting & Analysis
3. Performance

## User Interface

| Tool | Interface |
|---|---|
| Nmap | Command-line based |
| Burp Suite | Graphical and text-based |
| SQLmap | Command-line based |
| Metasploit | Primarily command-line in the tested version |

Burp Suite provided the most GUI-oriented workflow, while Nmap and SQLmap relied heavily on command-line operation.

## Reporting & Analysis

| Tool | Main Output |
|---|---|
| Nmap | Ports, services, OS information and potential vulnerabilities |
| Burp Suite | Web application requests, responses and vulnerabilities |
| SQLmap | SQL injection findings and extracted database information |
| Metasploit | Exploitation and post-exploitation results |

## Performance

The measurements recorded in the project were:

| Tool | RAM Usage | CPU Usage | Memory Usage |
|---|---:|---:|---:|
| Nmap | 41.94 MB | 4.0% | 0.6% |
| Burp Suite | 780 MB | 0.4% | 11% |
| SQLmap | 62.91 MB | 92.8% | 0.9% |
| Metasploit | 433 MB | 1.3% | 6.1% |

## Overall Conclusion

Each tool demonstrated a different strength.

- Nmap was suited to network and reconnaissance activities.
- Burp Suite was suited to web application testing.
- SQLmap was specialised for SQL injection testing.
- Metasploit was particularly useful for exploitation.

The project concluded that the most appropriate tool depends on the penetration-testing scenario rather than there being one universally best tool.
