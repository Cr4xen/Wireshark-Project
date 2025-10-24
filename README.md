# Wireshark Packet‑Analysis Lab

📄 **PDF Documentation:** [wireshark_project.pdf](./wireshark_project.pdf)

---

### Overview

Hands-on packet analysis project for my portfolio. Investigate PCAPs to detect ARP‑MITM, DNS/ICMP tunneling, Log4j exploitation, decrypt TLS (when keys are available), and extract cleartext credentials.

### Tools

Wireshark, tshark, tcpreplay, NetworkMiner, Zeek (Bro), Scapy

### Workflow

* **PCAP Intake:** Collect and curate captures from lab traffic and public sources.
* **Hunting & Detection:** Apply display filters and follow streams to identify ARP‑MITM, tunneling, and exploitation evidence.
* **TLS Handling:** Decrypt TLS sessions using provided/private keys or SSLKEYLOGFILE when available.
* **IOC Extraction:** Extract credentials, payloads, and exploit indicators for reporting.
* **Replay & Validation:** Use tcpreplay and Scapy to emulate and validate observed behaviors.

### Key Outcomes

* Identified ARP‑MITM attacks and confirmed traffic interception.
* Detected DNS/ICMP tunneling channels used for covert data exfiltration.
* Located Log4j exploitation attempts and isolated payload delivery flows.
* Decrypted TLS sessions where keys were available and extracted cleartext credentials.
* Practiced and documented effective Wireshark display filters and investigative steps.

### Conclusion

This lab demonstrates practical network-forensics skills: packet-level threat hunting, protocol analysis, TLS decryption techniques, and evidence extraction—suitable for inclusion in a professional portfolio or GitHub resume.

