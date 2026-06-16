## Hi, I'm Deval

I build security tools and break web apps. Each repo here is a concept I wanted to understand by building it instead of just reading about it: firewalls, scanners, malware analysis, crypto. Currently at JioStar.

### Tools

| Tool | What it does |
|---|---|
| [dpi-firewall](https://github.com/devalkotak/dpi-firewall) | Layer-7 userspace firewall via the Linux netfilter queue. Blocks by IP, port, and payload signature |
| [static-malware-analyzer](https://github.com/devalkotak/static-malware-analyzer) | Static binary analysis: hashes, entropy, IOC extraction, PE parsing, YARA matching |
| [web-recon-scanner](https://github.com/devalkotak/web-recon-scanner) | Checks for missing security headers and exposed sensitive files |
| [packet-sniffer](https://github.com/devalkotak/packet-sniffer) | Real-time TCP/UDP/ICMP traffic analyzer built with Scapy |
| [fortress-cipher](https://github.com/devalkotak/fortress-cipher) | AES-256-GCM encryption with PBKDF2 key derivation |
| [log-analyzer](https://github.com/devalkotak/log-analyzer) | Pulls suspicious entries out of Linux and Windows system logs |
| [file-integrity-monitor](https://github.com/devalkotak/file-integrity-monitor) | Baseline file hashing with change detection |
| [port-scanner](https://github.com/devalkotak/port-scanner) | Threaded TCP scanner with banner grabbing, plus a dependency-free Bash version |

### Currently building

A DAST engine: recursive JS-rendering crawler with active SQLi/XSS/SSRF/IDOR testing and CVSS-scored reports. It replaces the simple web scanner above.

### Find me

- LinkedIn: [devalkotak](https://www.linkedin.com/in/devalkotak/)
