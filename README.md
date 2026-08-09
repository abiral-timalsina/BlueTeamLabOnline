# BTLO Challenges

Write-ups and solutions for challenges completed on [Blue Team Labs Online (BTLO)](https://blueteamlabs.online/), a platform for hands-on blue team / SOC analyst training.

Each challenge includes a detailed PDF report documenting the investigation process, tools used, and methodology followed to reach each answer — written to reflect how a SOC analyst would document findings in a real investigation.

## About

This repository is part of my ongoing blue team / SOC analyst portfolio, alongside my [Splunk SIEM home lab](https://github.com/abiral-timalsina/soc-splunk-lab) and [CyberDefenders write-ups](https://github.com/abiral-timalsina/CyberDefenders-lab-). I'm building this out while pursuing SOC Analyst / Junior Cybersecurity Analyst roles, with a focus on digital forensics, incident response, and log/SIEM analysis.

## Challenges Completed

| # | Challenge | Category | Difficulty | Report |
|---|-----------|----------|------------|--------|
| 1 | Meta | Digital Forensics | Easy | [PDF](./reports/Meta.pdf) |
| 2 | Bruteforce | Incident Response | Medium | [PDF](./reports/Bruteforce.pdf) |
| 3 | Secrets | Python / Crypto | Easy | [PDF](./reports/Secrets.pdf) |
| 4 | Phishing Analysis | Email Forensics | Easy | [PDF](./reports/Phishing_Analysis.pdf) |

*(This table will be updated as new challenges are completed.)*

## Skills Demonstrated

- **Digital Forensics** — EXIF metadata extraction and analysis, image OSINT / reverse image search
- **Incident Response** — Windows Security Event Log analysis (Event ID 4625), brute-force attack investigation, IP/geolocation attribution
- **Cryptography / Application Security** — JWT structure analysis, signature cracking (Hashcat mask attacks), manual token forgery (Base64 + HMAC-SHA256)
- **Email / Phishing Forensics** — Raw `.eml` header analysis, nested MIME structure parsing, reverse DNS lookups, URL and hosting service identification

## Tools Used

`exiftool` · `grep` / `awk` · `hashcat` · `openssl` · `7z` · WHOIS / DomainTools · URL2PNG · CyberChef

## Report Format

Each PDF report follows a consistent structure:
1. **Scenario** — the challenge prompt as given
2. **Methodology** — step-by-step investigation process and commands used
3. **Findings** — answers to each submission question with supporting evidence
4. **Lessons Learned** — key takeaways or techniques worth remembering

---

📫 Connect with me on [LinkedIn](https://linkedin.com/in/abiral-timalsina) | Check out my [CyberDefenders profile](https://cyberdefenders.org/p/abiraltimalsina8)
