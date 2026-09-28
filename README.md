# AI-Powered Talent Intelligence & Signal Sourcing Framework
> **Target Role:** Technical Support Engineer (Application Security) — Cloudflare APAC (Singapore)  
> **Author:** Faiza Ummul Hussaini  
> **Methodology:** Signal-Based Sourcing, LLM Market Mapping, Complex X-Ray Boolean Logic & GitHub API Mining  

---

## 📌 Executive Brief & Problem Statement
Sourcing high-caliber **Application Security Support Engineers** in APAC requires moving beyond traditional ATS keyword searches. Top talent proficient in Layer 3/4/7 network protocols, Web Application Firewalls (WAF), BGP routing, and packet diagnostics rarely list generic support titles on public profiles.

To overcome top-of-funnel talent friction, this project demonstrates an **AI-native, signal-based sourcing workflow** engineered to:
- Map regional target companies, non-traditional titles, and CLI protocol signals across Singapore/APAC using structured LLM prompts.
- Construct and execute complex Google X-Ray strings to isolate passive security talent.
- Mine developer-native platforms (GitHub) via API search qualifiers to identify engineers actively building networking and edge proxy tools.

---

## 🧠 LLM Market Intelligence & Ecosystem Mapping

### Prompt Architecture
To map the regional technical ecosystem, the following structured prompt was executed:

```text
Act as an executive technical sourcer for Cloudflare in APAC. 
I am sourcing for a Technical Support Engineer (Application Security) in Singapore. Candidates need strong fundamentals in OSI Layer 3/4/7, DNS resolution, HTTP/HTTPS traffic, WAF rules, and CLI troubleshooting (curl, dig, traceroute, Wireshark). 

Output:
1. Top 10 target tech/SaaS companies in Singapore and APAC with overlapping network/security operations.
2. 5 non-traditional job titles that hold these technical skills.
3. Key technical indicators/signals beyond standard titles.
