## Hi there 👋

<!--
**ekeleu/ekeleu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
Core Methodologies:

    Infrastructure as Code (IaC)

    Trunk-Based Development (Solo) & GitFlow (Team)

    CI/CD Security Auditing

## 🛡️ Security Hardening (SSH & OS)
To protect the node's private keys and channel liquidity, the following security layers are implemented:

- **Key-Based Authentication:** Password authentication is disabled (`PasswordAuthentication no`).
- **Custom SSH Port:** Obfuscation implemented to reduce automated brute-force "noise" logs.
- **Fail2Ban Integration:** Automated IP-jail for repeated failed handshake attempts.
- **SSH Auditing:** Periodic review of `/var/log/auth.log` for anomalous connection patterns.
- **UFW Firewall:** Strict "Deny by Default" policy; only P2P (BTC/ADA/ALGO) and LND gossip ports are exposed.
