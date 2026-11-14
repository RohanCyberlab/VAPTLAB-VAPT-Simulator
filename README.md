# VAPTLAB — Corporate Infrastructure VAPT Simulator

An intermediate-level, GitHub-ready portfolio project demonstrating a professional Vulnerability Assessment and Penetration Testing (VAPT) workflow.

## Important: simulation only

This is a **front-end educational simulator**. It does not:
- Connect to a company network or the internet to scan targets.
- Run Nmap, Wireshark, Kali Linux, Nessus, Burp Suite, or a real Linux shell.
- Authenticate to a real company or Cisco ASA firewall.
- Exploit vulnerabilities or collect real packets.

All assets, IP addresses, packet rows, scan output, and findings are fictional/pre-generated. Do not present the sample findings as a real security assessment.

## Features

- Security overview dashboard
- Fictional corporate asset inventory
- Reconnaissance workflow demonstration
- Sample vulnerability findings and risk ratings
- Cisco ASA 5505 read-only review checklist
- Simulated Linux terminal (`help`, `whoami`, `pwd`, `ls`, `ip addr`, `uname -a`, `nmap-demo`, `clear`)
- Nmap output simulator with documentation-only targets
- Wireshark-style sample packet viewer with protocol filter
- Downloadable Markdown VAPT report
- Downloadable CSV asset inventory
- Responsive layout

## Run locally

No installation or build step is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Navigate using the left sidebar.
4. Try the Linux terminal and tool simulators.
5. Download the sample report from **Reports**.

For a local web server, from this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub

1. Create a new public or private repository, for example `vaptlab-simulator`.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md`.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub Pages will provide a public website URL after deployment.

Do not upload company configuration files, internal IP lists, credentials, screenshots containing sensitive data, or customer information.

## Suggested project description

**VAPTLAB — Real-World VAPT Workflow Simulator**

A browser-based educational dashboard that demonstrates corporate asset inventory, reconnaissance workflow, vulnerability assessment, Cisco ASA security review, simulated Linux terminal, Nmap-style scan output, Wireshark-style packet inspection, and VAPT report generation using fictional data.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript

## Disclaimer

This project is a portfolio simulator, not a real penetration-testing tool. Any real-world security testing requires explicit written authorization, confirmed asset ownership/testing authority, an approved scope, rules of engagement, and agreed maintenance windows.
