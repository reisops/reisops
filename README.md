<p align="center">
  <img src="./assets/mario-sudo" width="350"/>
</p>

<h1 align="center">hey, I'm Luís 👋</h1>

<p align="center">
  Infrastructure & Cloud Engineering student — Linux, networking, and systems that break in interesting ways.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/luis-reis-ops">LinkedIn</a> •
  <a href="https://github.com/reisops">GitHub</a>
</p>

-----

## $ whoami

```bash
reisops
├── role:     Infrastructure & Cloud Engineering student
├── focus:    Linux · Networking · Cloud · Troubleshooting
├── labs:     AlmaLinux 9 on VirtualBox · Ubuntu Server multi-VM environments
├── certs:    RHCSA (in progress) · AWS Re/Start · Cisco CyberEdu 2026
└── mode:     break it → understand it → document it → don't break it the same way twice
```

-----

## 🏗️ Projects

<p align="center">
  <img src="https://raw.githubusercontent.com/reisops/reisops/main/assets/metalslug.gif" width="320"/>
</p>

### [enterprise-linux-lab](https://github.com/reisops/enterprise-linux-lab)

Multi-VM Ubuntu Server environment simulating production-like infrastructure from scratch.

|Service               |Role                          |
|----------------------|------------------------------|
|DNS (BIND9)           |Internal name resolution      |
|DHCP (isc-dhcp-server)|Dynamic IP assignment         |
|Samba                 |File sharing / Windows interop|
|Apache2 + WordPress   |Web hosting stack             |
|MariaDB               |Database backend              |
|Squid                 |Proxy server                  |
|iptables              |Firewall and packet filtering |

3 VMs, all interconnected, all configured manually. No shortcuts.

-----

### [linux-troubleshooting](https://github.com/reisops/linux-troubleshooting)

Documented real troubleshooting cases using a structured methodology:

```
OBSERVE → DIAGNOSE → FIX → DOCUMENT
```

Each case includes the exact command sequence used, reconstructed from shell history — not cleaned up after the fact.

Cases documented so far:

- `networking` — No internet: interface is up but default route is missing
- `ssh` — SSH alias not resolving: could not connect to VM from host
- `systemd` — Service fails to start: binary not found (status=203/EXEC)

-----

### [Supermarket Sales Database](https://github.com/reisops/db-sales)

Relational database system for retail operations — data modeling, SQL queries, and automated stock control via trigger. Deployed on the MariaDB instance running on `vm2web` from the enterprise-linux-lab infrastructure.

-----

## 🎓 Training Programs

- ☁️ **AWS Re/Start** (Escola da Nuvem) — Cloud foundations, IAM, compute, networking *(scholarship)*
- 🌐 **Cisco CyberEdu — Cyber Education Marathon 2026** — Networking + cybersecurity fundamentals *(scholarship)*
- 🐧 **Linux System Administration** (4Linux) — Working toward RHCSA

-----

## ⚡ On incidents

> Mario causes the incident. Luigi writes the postmortem.

<p align="center">
  <img src="https://raw.githubusercontent.com/reisops/reisops/main/assets/luigi.gif" width="130"/>
</p>
