# Hi, I'm Trisha Doret

Aspiring Cybersecurity Analyst with a background in Criminal Justice and Digital Forensics. I specialize in **Incident Response**, threat hunting, and hands-on security practices. Passionate about protecting systems and investigating breaches.

## Tools & Skills
- Incident Response | Digital Forensics | Threat Hunting
- Wireshark, Splunk, Autopsy, Kali Linux, Security Onion
- Python, Bash

## Projects
- [Phishing Email Analysis](#)
- [SIEM Alert Triage](#)
- [Forensics Case Study](#)

## Certifications & Education
- Cybersecurity Certificate - Southern New Hampshire University
- B.S. in Criminal Justice, Minor in Digital Forensics

phishing-email-analysis/
│
├── README.md
├── screenshots/
│   ├── header-analysis.png
│   └── payload-analysis.png
├── email_headers.txt
└── analysis_report.pdf

# Phishing Email Analysis

## Objective
Analyze a suspicious email to identify phishing indicators, extract payloads, and recommend remediation steps.

## Tools Used
- Email Header Analyzer
- VirusTotal
- Wireshark (optional if analyzing attached files)

## Steps Taken
1. Collected email headers and body.
2. Analyzed headers for spoofing (e.g., return-path, SPF, DKIM).
3. Extracted and examined any URLs or attachments.
4. Checked link/IP reputation using VirusTotal.
5. Wrote a mini incident report.

## Screenshots
![Header Analysis](screenshots/header-analysis.png)
![Payload Analysis](screenshots/payload-analysis.png)

## Lessons Learned
- Importance of email header forensics
- Recognizing spoofed domains and suspicious URLs
