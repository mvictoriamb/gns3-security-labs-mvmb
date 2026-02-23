<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00D4AA&center=true&vCenter=true&width=435&lines=%F0%9F%91%8B+Hola!+Soy+Mar%C3%ADa+Victoria+Maldonado+Bao;🛡️+Ciberseguridad+%26+IA;🎻+Violinista+pianista+profesional;🌏+Triling%C3%BCe+ES%2FEN%2FCN;MSc+Cyber+Security+%26+AI+%40+Radboud" alt="typing svg" />
</div>

# 🛡️ **GNS3 Enterprise Security Labs**
**5 laboratorios completos** | **47 páginas técnicas** | **20+ ataques simulados**

[![Google Cybersecurity](https://img.shields.io/badge/Google-Cybersecurity-blue?style=for-the-badge&logo=google)](https://coursera.org)
[![2º Google Init.g()](https://img.shields.io/badge/2º%20Google%20Init.g()-gold?style=for-the-badge&logo=trophy)](https://google.com)
[![NVIDIA Recommended](https://img.shields.io/badge/NVIDIA-University%20Ambassador-teal?style=for-the-badge&logo=nvidia)](https://nvidia.com)

## 📋 **Contenido de los Labs**

| **Lab** | **Ataques Simulados** | **Defensas Implementadas** |
|---------|----------------------|---------------------------|
| **LAB 1** | SYN Flood, LAND, Smurf, ARP Spoofing | Wireshark `tcp.flags.syn==1 && !tcp.flags.ack` |
| **LAB 2** | Brute Force, Port-Knocking | Whitelist/Blacklist, **OpenVPN** |
| **LAB 2.3** | ARP Spoof, ICMP Injection, SYN Flood | **Snort IDS + pfSense NIDS** |
| **LAB 3** | Nmap Stealth Scans | **iptables rate limiting** |
| **LAB 4** | Client-Server TCP sin TLS | Scripts Python análisis |

## 🛠 **Stack Técnico**
```mermaid
graph TB
    A[GNS3 Emulation] --> B[Cisco Router + Kali VMs]
    B --> C[hping3 / Ettercap / arpspoof]
    B --> D[Snort IDS / pfSense NIDS]
    C --> E[iptables / OpenVPN]
    D --> F[Wireshark / Torch Analysis]
