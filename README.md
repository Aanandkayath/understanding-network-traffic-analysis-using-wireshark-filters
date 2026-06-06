# Understanding Network Traffic Analysis Using Wireshark Filters

> Practical network packet analysis using 20+ Wireshark display filters covering TCP, UDP, ICMP, HTTP, DNS and TLS protocols with real captured traffic.

---

## About

This project demonstrates hands-on network traffic analysis using Wireshark. It covers packet inspection, protocol behavior, and filtering techniques used in real-world cybersecurity and SOC (Security Operations Center) environments.

---

## What's Inside

| File | Description |
|------|-------------|
| `Wireshark_Project_Report.pdf` | Full project report with all filters and analysis |
| `Wireshark_Cheatsheet_hackproofaanand.pdf` | Custom Wireshark filter cheat sheet |
| `capture.pcap` | Real packet capture file used in this project |
| `/screenshots/` | Screenshots of each filter applied in Wireshark |

---

## Filters Covered

**IP Filters**
- `ip.addr` `ip.src` `ip.dst`

**TCP Filters**
- `tcp.port` `tcp.srcport` `tcp.dstport`
- `tcp.flags.syn` `tcp.flags.ack` `tcp.flags.fin`
- `tcp.analysis.retransmission` `tcp.analysis.duplicate_ack`
- `tcp.stream eq 0`

**UDP Filters**
- `udp.port == 53` `udp.port == 67/68` `udp.port == 123`
- `udp.srcport` `udp.dstport`

**ICMP Filters**
- `icmp.type == 8` `icmp.type == 0`

**HTTP Filters**
- `http.request` `http.response` `http.request.method == "GET"`

---

## Tools Used

- Wireshark
- TCP/IP Protocol Suite
- Protocols: TCP, UDP, ICMP, HTTP, DNS, TLS

---

## Real-World Relevance

These filters are used daily by SOC analysts to:
- Monitor network traffic
- Detect suspicious activity
- Investigate security incidents
- Troubleshoot network issues

---

## Author

**Anand Kayath** — Cybersecurity Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-Aanandkayath-1D9E75?style=flat&logo=github)](https://github.com/Aanandkayath)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anand--kayath-1D9E75?style=flat&logo=linkedin)](https://www.linkedin.com/in/anand-kayath-2875b8291/)
[![Instagram](https://img.shields.io/badge/Instagram-hackproofaanand-1D9E75?style=flat&logo=instagram)](https://instagram.com/hackproofaanand)
[![X](https://img.shields.io/badge/X-hackproofaanand-1D9E75?style=flat&logo=x)](https://x.com/hackproofaanand)

---

*June 2026*
