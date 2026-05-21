<div align="center">

# ⚡ ASMODAX-OPS

### *Red Team • Blue Team • Digital Forensics*

[![STATUS](https://img.shields.io/badge/STATUS-ACTIVE-8A2BE2?style=flat-square&labelColor=0d1117)](https://github.com/ASMODAX-OPS)
[![Python](https://img.shields.io/badge/Python-3.9+-00d4ff?style=flat-square&labelColor=0d1117)](https://python.org)
[![Security](https://img.shields.io/badge/Focus-CyberSecurity-ff4444?style=flat-square&labelColor=0d1117)](https://github.com/ASMODAX-OPS)

</div>

---

<table align="center" style="border-collapse: collapse; width: 100%; max-width: 600px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; text-align: center; background: linear-gradient(135deg, rgba(138,43,226,0.06) 0%, rgba(0,212,255,0.06) 100%); border-radius: 10px; border: 1px solid #30363d;">
      <code style="color: #00d4ff; font-family: 'Fira Code', monospace; font-size: 13px; line-height: 1.8;">
❯ Alan Fonseca | ASMODAX-OPS<br/>
├─ Location: Bogotá, Colombia 🇨🇴<br/>
├─ Role: Cybersecurity Researcher & Tool Developer<br/>
├─ Focus: AD Exploitation • Threat Hunting • Memory Forensics<br/>
└─ Motto: "The quieter you become, the more you are able to hear" 🔍
      </code>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<table align="center" style="border-collapse: collapse; width: 100%; max-width: 700px; margin: 20px auto;">
  <tr>
    <td style="width: 50%; padding: 15px; background: rgba(0,212,255,0.03); border-left: 3px solid #00d4ff; border-top: 1px solid #30363d; border-bottom: 1px solid #30363d; border-right: 1px solid #30363d; border-radius: 6px 0 0 6px;">
      <strong style="color: #00d4ff;">💻 Languages</strong><br/><br/>
      <code>Python</code> • <code>Bash</code> • <code>PowerShell</code> • <code>Go</code>
    </td>
    <td style="width: 50%; padding: 15px; background: rgba(138,43,226,0.03); border-left: 3px solid #8A2BE2; border-top: 1px solid #30363d; border-bottom: 1px solid #30363d; border-right: 1px solid #30363d; border-radius: 0 6px 6px 0;">
      <strong style="color: #8A2BE2;">🛡️ Systems & Environment</strong><br/><br/>
      <code>Kali Linux</code> • <code>Windows Server</code> • <code>Docker</code> • <code>Obsidian</code>
    </td>
  </tr>
</table>

---

## 🔴 Offensive Security (Red Team)

<div style="background: rgba(255,68,68,0.03); border: 1px solid #30363d; border-left: 4px solid #ff4444; border-radius: 8px; padding: 20px; margin: 15px 0;">

### 🏢 Active Directory & Network
- **Enumeration:** Path finding y mapeo de relaciones con `BloodHound` y `SharpHound`.
- **Credential Attacks:** Ejecución de vectores `Kerberoasting`, `AS-REP Roasting` y Password Spraying.
- **Lateral Movement:** Técnicas de `Pass-the-Hash`, `Pass-the-Ticket` y abuso de privilegios en dominios.
- **Domain Dominance:** Generación de `Golden/Silver Tickets`, persistencia avanzada y ataques `DCSync`.

### 🚀 Exploitation & Infrastructure
- **Web App Pentesting:** Auditorías automatizadas y manuales basadas en el marco OWASP Top 10.
- **Pivoting Avanzado:** Evasión de segmentación de red utilizando `Ligolo-ng` (Layer 2) y túneles con `Chisel`.
- **C2 Frameworks:** Despliegue de infraestructura de comando y control orientada a pruebas de sigilo (`Sliver` / `Mythic`).

</div>

---

## 🔵 Defensive Security & DFIR (Blue Team)

<div style="background: rgba(0,212,255,0.03); border: 1px solid #30363d; border-left: 4px solid #00d4ff; border-radius: 8px; padding: 20px; margin: 15px 0;">

### 🔍 Digital Forensics & Incident Response
- **Memory Analysis:** Análisis profundo de volcados de memoria RAM utilizando `Volatility 3`.
- **Windows Artifacts:** Análisis forense del Registro de Windows, logs de eventos, `Prefetch`, `Shellbags` y `Jump Lists`.
- **Linux Forensics:** Análisis cronológico (`Timeline Analysis`), auditoría de archivos de autenticación y análisis del sistema de archivos.

### 🎯 Threat Detection & Monitoring
- **Rule Engineering:** Creación y despliegue de reglas `YARA` para detección de malware y reglas `Sigma` para SIEM.
- **SIEM Analytics:** Correlación de logs e investigación de alertas mediante queries complejas en `Splunk (SPL)` y `Elastic Stack (ELK)`.
- **Host Monitoring:** Configuración avanzada de auditoría del sistema con `Sysmon` y análisis del tráfico con `Wireshark`.

</div>

---

## 🚀 Featured Cyber Arsenal

<table style="width: 100%; border-collapse: collapse; background: linear-gradient(135deg, rgba(0,212,255,0.02) 0%, rgba(138,43,226,0.02) 100%); border: 1px solid #30363d; border-radius: 10px; padding: 25px; margin: 15px 0;">
  <tr>
    <td>
      <h3 style="color: #00d4ff; margin: 0 0 5px 0; font-family: 'Fira Code', monospace;">🐍 GHOSTHOUND SCOUT v2.1</h3>
      <p style="color: #8b949e; margin: 0 0 15px 0; font-size: 13px;">Automated Active Directory Reconnaissance & Information Gathering Toolkit</p>
      
      <div style="background: #0d1117; border: 1px solid #30363d; border-radius: 6px; padding: 15px; margin: 10px 0; font-family: 'Fira Code', monospace; font-size: 13px; color: #c9d1d9; line-height: 1.6;">
🔧 <span style="color: #8A2BE2;">Multi-threaded Scanning:</span> Módulos automatizados de descubrimiento de red externa e interna.<br/>
📊 <span style="color: #8A2BE2;">Data Correlation:</span> Parseo inteligente de respuestas en tiempo real mediante subprocesses nativos en Python.<br/>
🛡️ <span style="color: #8A2BE2;">Dependency Check:</span> Verificación robusta del entorno en Linux mediante validación directa en el PATH.<br/>
📦 <span style="color: #8A2BE2;">Clean Deliverables:</span> Exportación automática y estructurada de evidencias listas para reporte de auditoría.
      </div>
      
      <p style="color: #8A2BE2; font-family: 'Fira Code', monospace; font-size: 12px; margin: 15px 0 5px 0;">⚡ Status: [████████████░░░░░░░░] 60% Complete | Python Core Engine</p>
      <p style="margin: 15px 0 0 0;"><a href="https://github.com/ASMODAX-OPS/ghosthound-scout" style="color: #00d4ff; text-decoration: none; font-size: 13px; font-weight: bold;">[ View Repository → ]</a></p>
    </td>
  </tr>
</table>

---

## 📊 Operations & Roadmap

<div style="margin: 20px 0;">

⚡ **GHOSTHOUND SCOUT 2.1 — Tool Development**
<div style="background: #161b22; border: 1px solid #30363d; height: 12px; border-radius: 6px; margin: 8px 0; overflow: hidden;">
  <div style="background: #8A2BE2; height: 100%; width: 60%;"></div>
</div>
<span style="color: #8b949e; font-size: 12px;">Development Phase: **60% — Implementing Multi-threaded Parse Logic**</span>

<br/>

🧪 **HTB Pro Lab: Dante — Enterprise Network Penetration**
<div style="background: #161b22; border: 1px solid #30363d; height: 12px; border-radius: 6px; margin: 8px 0; overflow: hidden;">
  <div style="background: #00d4ff; height: 100%; width: 35%;"></div>
</div>
<span style="color: #8b949e; font-size: 12px;">Lab Progress: **35% — Network Pivoting & Domain Enumeration**</span>

<br/>

📚 **Advanced Memory Forensics — Volatility 3 Research**
<div style="background: #161b22; border: 1px solid #30363d; height: 12px; border-radius: 6px; margin: 8px 0; overflow: hidden;">
  <div style="background: #ff4444; height: 100%; width: 75%;"></div>
</div>
<span style="color: #8b949e; font-size: 12px;">Skill Track: **75% — Windows Kernel Artifacts & RAM Triage**</span>

</div>

---

## 🌐 Connect & Collaborate

<div align="center" style="margin: 25px 0;">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://linkedin.com/in/tu-perfil)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d1117)](https://discord.com/users/tu-id)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/ASMODAX-OPS)
[![HTB](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hack-the-box&logoColor=black&labelColor=0d1117)](https://hackthebox.eu/)
[![THM](https://img.shields.io/badge/TryHackMe-EF3B2D?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117)](https://tryhackme.com/)

</div>

---

<div style="background: rgba(255,68,68,0.02); border: 1px solid #30363d; border-radius: 8px; padding: 15px; margin: 20px 0; text-align: center; font-size: 12px; color: #8b949e; font-family: monospace;">

⚠️ **DISCLAIMER:** All information and tools hosted here are strictly intended for authorized security assessment, research, and educational purposes only. Unauthorized actions are strictly prohibited.

</div>
