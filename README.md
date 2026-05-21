# 🔴🔵 ASMODAX-OPS
## Red Team • Blue Team • Digital Forensics • Security Development

<div align="center">

![STATUS](https://img.shields.io/badge/STATUS-ACTIVE-00d4ff?style=flat-square)
![Location](https://img.shields.io/badge/📍-Bogotá,_Colombia-9A4DFF?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.9+-3776ab?style=flat-square&logo=python&logoColor=white)
![Security](https://img.shields.io/badge/Focus-CyberSecurity-ff4444?style=flat-square)

</div>

---

## 👤 whoami

<table style="width:100%; border-collapse:collapse;">
  <tr>
    <td style="width:65%; padding:20px; background:#0d1117; border:1px solid #30363d; border-radius:10px;">
      <pre style="color:#00d4ff; font-family:JetBrains Mono,monospace; font-size:12px; margin:0; line-height:1.6;">
<span style="color:#8A2BE2;">❯</span> <span style="color:#58a6ff;">whoami</span>

<span style="color:#79c0ff;">Name</span>           <span style="color:#8B8B8B;">→</span> Alan Fonseca
<span style="color:#79c0ff;">Handle</span>         <span style="color:#8B8B8B;">→</span> ASMODAX-OPS
<span style="color:#79c0ff;">Location</span>       <span style="color:#8B8B8B;">→</span> Bogotá, Colombia 🇨🇴
<span style="color:#79c0ff;">Role</span>           <span style="color:#8B8B8B;">→</span> Cybersecurity Researcher
<span style="color:#79c0ff;">Specialization</span> <span style="color:#8B8B8B;">→</span> AppSec • Threat Hunting
<span style="color:#79c0ff;">Expertise</span>      <span style="color:#8B8B8B;">→</span> AD Exploitation • DFIR
<span style="color:#79c0ff;">Passion</span>        <span style="color:#8B8B8B;">→</span> "Know the enemy within" 🔍
      </pre>
    </td>
    <td style="width:35%; text-align:center; padding:20px;">
      <div style="background:#0d1117; border:1px solid #30363d; border-radius:10px; padding:15px;">
        <p style="color:#00d4ff; margin:0 0 10px 0; font-weight:bold;">⚡ ENGINEERING PROFILE</p>
        <p style="color:#c9d1d9; margin:5px 0; font-size:12px;">▸ Security Research</p>
        <p style="color:#c9d1d9; margin:5px 0; font-size:12px;">▸ Red/Blue Ops</p>
        <p style="color:#c9d1d9; margin:5px 0; font-size:12px;">▸ Forensic Analysis</p>
        <p style="color:#c9d1d9; margin:5px 0; font-size:12px;">▸ Tool Development</p>
      </div>
    </td>
  </tr>
</table>

---

## ⚙️ TECHNOLOGY ARSENAL

### 🐍 Scripting & Automation Languages
<div style="background:#0d1117; border-left:3px solid #00d4ff; padding:15px; border-radius:6px; margin:10px 0;">

| Lenguaje | Proficiencia | Aplicación |
|----------|-------------|-----------|
| **Python 3.x** | Experto | Herramientas de seg, automatización SIEM, análisis forense |
| **Bash/Zsh** | Avanzado | Scripts de recon, automatización Linux, tunelización |
| **PowerShell 7.x** | Avanzado | Explotación AD, escalada privs Windows, evasión AV |
| **Go** | Intermedio | Herramientas ligeras, C2 frameworks, tunneling |

</div>

### ⚔️ Operative Platforms & Environments
<div style="background:#0d1117; border-left:3px solid #9A4DFF; padding:15px; border-radius:6px; margin:10px 0;">

| Sistema | Versiones | Especialidad |
|---------|-----------|------------|
| **Kali Linux** | 2024.x | Penetration testing, red team ops |
| **Windows** | 10/11 Pro | Target analysis, EDR testing, AD environments |
| **Windows Server** | 2019/2022 | DC simulation, AD exploitation, hardening |
| **Linux (Ubuntu/Debian)** | LTS | Forensic analysis, SIEM deployment, hardening |
| **Docker/Containers** | Latest | Lab isolation, tool containerization |

</div>

### 🛠️ Forensics & Security Tools
<div style="background:#0d1117; border-left:3px solid #FFD700; padding:15px; border-radius:6px; margin:10px 0;">

**Análisis Forense:** `Volatility 3` • `Autopsy` • `FTK Imager` • `Registry Explorer` • `ShellBagsExplorer` • `ExifTool` • `The Sleuth Kit`

**Explotación Web:** `Burp Suite` • `ZAP` • `Postman` • `SQLmap` • `Commix` • `XSSstrike`

**Red Team:** `Metasploit` • `Burp Suite` • `BloodHound` • `Mimikatz` • `Rubeus` • `Nmap` • `Gobuster` • `WhatWeb`

**Análisis SIEM/Logs:** `Splunk` • `Elasticsearch` • `Kibana` • `Logstash` • `Sysmon` • `Auditbeat`

**Threat Intelligence:** `YARA` • `Sigma` • `MITRE ATT&CK Navigator` • `VirusTotal` • `AlienVault OTX`

**IDEs & Utilities:** `VSCode` • `Vim/Neovim` • `Git` • `Obsidian` • `Wireshark` • `tcpdump`

</div>

---

## 🔴 RED TEAM OPERATIONS

### 🏗️ Active Directory Exploitation

<div style="background:rgba(139,0,0,0.08); border:1px solid #8B0000; border-radius:8px; padding:15px; margin:10px 0;">

**Enumeration & Reconnaissance**
- Enumeración LDAP anónima y consultas directas
- `BloodHound` & `SharpHound` para mapeo de relaciones
- Powerview & net commands para enumeración de usuarios/grupos
- Domain trust mapping y forest enumeration

**Authentication Attacks**
- `Kerberoasting` - Extracción de hashes TGS de cuentas SPN
- `AS-REP Roasting` - Ataques a cuentas sin pre-autenticación
- Brute force Kerberos/LDAP con herramientas automatizadas
- Password spraying técnicas y tunelización de ataques

**Lateral Movement & Escalation**
- `Pass-the-Hash` (PTH) - Uso de hashes NTLM directamente
- `Pass-the-Ticket` (PTT) - Reutilización de tickets Kerberos
- `Over-Pass-The-Hash` - Generación de TGT desde NTLM hash
- `Golden Ticket` - Creación de tickets administrativos permanentes
- `Silver Ticket` - Falsificación de tickets de servicio específicos
- `DCSync` - Sincronización de credenciales desde DC con Mimikatz
- Constrained Delegation abuse y Unconstrained Delegation attacks
- Resource-Based Constrained Delegation (RBCD) exploitation

**Advanced Persistence**
- `AdminSDHolder` backdoors para acceso permanente
- ACL modification attacks para escalada posterior
- `ShadowCredentials` abuse (PKINIT exploitation)
- Alternativos de autenticación (msDS-KeyCredentialLink)
- Domain Controller persistence mecanismos

**Tools Ecosystem:** `Mimikatz` • `Rubeus` • `ADCSExploit` • `Certify` • `Kekeo` • `SharpHound`

</div>

### 💥 Web Application Exploitation

<div style="background:rgba(139,0,0,0.08); border:1px solid #8B0000; border-radius:8px; padding:15px; margin:10px 0;">

**Reconnaissance & Scanning**
- Burp Suite advanced scanning (active/passive/intruder)
- OWASP ZAP passive scanning y spidering
- Nmap NSE scripts para servicios web
- Gobuster/Dirsearch para brute force de directorios
- Nikto web server fingerprinting
- WhatWeb technology identification
- Subdomain enumeration (Sublist3r, Amass, Assetfinder)

**OWASP Top 10 Exploitation**
- SQL Injection (Union-based, Boolean blind, Time-based, Error-based)
- Cross-Site Scripting (Reflected, Stored, DOM-based, Blind XSS)
- Cross-Site Request Forgery (CSRF token bypass, SameSite evasion)
- Broken Authentication (Session fixation, JWT weaknesses, bypass)
- Broken Access Control (Privilege escalation, BOLA/IDOR)
- XML External Entity (XXE) injection y XXE blind exploitation
- Broken Object Level Authorization (BOLA) via ID manipulation
- Server-Side Request Forgery (SSRF) y SSRF via redirection
- Security Misconfiguration (Default credentials, exposed configs)
- Serialization vulnerabilities (Gadget chains, code execution)

**API Security Testing**
- RESTful API enumeration y fuzzing
- GraphQL introspection attacks y query exploitation
- JWT token analysis, signature bypass, algorithm confusion
- OAuth/OIDC flow exploitation
- API rate limiting bypass techniques
- API authentication bypass (header injection, parameter pollution)

**Advanced Exploitation**
- Payload development personalizado en Python/Go
- Shell staging y encoding techniques
- WAF evasion (IDS/IPS bypass)
- Polyglot file generation para bypasses

**Tools Ecosystem:** `Burp Suite Professional` • `OWASP ZAP` • `SQLmap` • `Commix` • `XSSstrike` • `Insomni` • `Postman`

</div>

### 🕳️ Post-Exploitation & Persistence

<div style="background:rgba(139,0,0,0.08); border:1px solid #8B0000; border-radius:8px; padding:15px; margin:10px 0;">

**Linux Privilege Escalation**
- SUID/GUID binary exploitation (find / -perm -4000 2>/dev/null)
- Kernel exploit chains (Linux Exploit Suggester automation)
- Weak sudo permissions exploitation (NOPASSWD entries)
- LD_PRELOAD privilege escalation via library injection
- Cron job manipulation y wildcard exploitation
- Shared library hijacking (DLL/SO injection)
- Docker/Container escape techniques (CVE-based)
- Capability abuse (CAP_NET_ADMIN, CAP_SYS_ADMIN)

**Windows Privilege Escalation**
- Windows Exploit Suggester automated scanning
- SeImpersonate & SeAssignPrimaryToken (token impersonation)
- Print Spooler vulnerability exploitation (CVE-2021-1675/CVE-2021-34481)
- Weak service permissions y service binary hijacking
- Registry write permissions exploitation
- RunAs credential recovery y Runas token abuse
- Scheduled task abuse y ALPC exploitation
- Token impersonation con Incognito y Custom Tools

**Persistence Mechanisms**
- Reverse shell stabilization techniques
- Backdoor user creation (createuser, net user)
- SSH key injection en authorized_keys
- Cron job backdoors y atcron.c exploitation
- Systemd service persistence
- Windows service installation y modification
- Registry Run keys (HKLM\Software\Microsoft\Windows\CurrentVersion\Run)
- Scheduled task persistence con payloads ocultos
- WMI Event subscription backdoors
- Browser extension persistence y startup folder abuse

**Anti-Forensics & Evasion**
- Log deletion y manipulation (Clear-EventLog, historian.exe)
- Temporal file cleanup y artifact removal
- Memory artifact removal y clearance
- Event log disabling techniques
- Syslog tampering (auditd.conf modification)
- Swap memory considerations
- Bash history evasion (export HISTFILE=/dev/null)

**Tools Ecosystem:** `Meterpreter` • `Empire` • `Powersploit` • `Linux Exploit Suggester` • `Pspy` • `lolbas`

</div>

### 🔄 Pivoting, Tunneling & Command & Control

<div style="background:rgba(139,0,0,0.08); border:1px solid #8B0000; border-radius:8px; padding:15px; margin:10px 0;">

**Network Pivoting & Tunneling**
- `Ligolo-ng` TUN-based network pivoting (full network access)
- `Chisel` HTTP/SOCKS5 tunneling cross-platform
- `Socat` socket relay y port forwarding
- SSH port forwarding (Dynamic -D, Local -L, Remote -R)
- VPN establishment (OpenVPN, WireGuard, tailscale)
- Multi-stage pivoting chains via proxychains
- ICMP tunneling (icmptunnel, PTunnel)
- DNS tunneling (iodine, dnscat2)

**Modern C2 Frameworks**
- **Sliver** - Go-based beacon alternative
  - Modular architecture con plug-in system
  - HTTPS, DNS, HTTP over WireGuard beaconing
  - Code armoring y obfuscación automática
  - Multi-platform support (Windows, Linux, macOS)
  - Session persistence y recovery mechanisms
  
- **Mythic** - Web-based collaborative C2
  - Multi-agent support con diferentes operadores
  - Payload customization en tiempo real
  - Real-time collaboration dashboard
  - Webhook integration para automatización
  - MITRE ATT&CK mapping integrado
  
- **Havoc** - Advanced command & control
  - Listener management y agent customization
  - Encrypted communication channels
  - Team collaboration features
  - Post-exploitation module ecosystem

**Evasion & Defense Bypass**
- EDR/AV evasion techniques (memory patching, DLL unhooking)
- AMSI bypass methods (PowerShell, .NET reflection)
- Reflective DLL injection y direct syscalls
- Process hollowing y process spoofing
- Code cave exploitation para inyección
- Sleep obfuscation (beaconing timing randomization)
- Traffic obfuscation (HTTPS, DNS, steganography)
- Beacon jitter configuration y sleep masking

**Payload Development**
- Custom shellcode generation (ASM, x86/x64)
- Beacon/stager development personalizado
- Living Off The Land (LOLBins) exploitation
- DLL side-loading y COM hijacking
- Staged vs stageless payload tradeoffs

**Tools Ecosystem:** `Cobalt Strike` • `Sliver` • `Mythic` • `Havoc` • `Ligolo-ng` • `Chisel` • `PEzor` • `Donut`

</div>

---

## 🔵 BLUE TEAM OPERATIONS

### 🔍 Digital Forensics & DFIR

<div style="background:rgba(0,100,200,0.08); border:1px solid #0064C8; border-radius:8px; padding:15px; margin:10px 0;">

**Memory Analysis (RAM Forensics)**
- **Volatility 3 Framework Expertise**
  - Memory image acquisition (Win/Linux/macOS)
  - Process listing y hidden process detection
  - Loaded DLL/module analysis
  - Network connection enumeration (established, listening)
  - Kernel object inspection
  - Rootkit detection y malware signatures
  - Malware artifact extraction (strings, config, IOCs)
  
- **Memory-Based Indicators**
  - Injected code detection (VirtualProtect, CreateRemoteThread)
  - Process hollowing evidence identification
  - API hook detection (SSDT hooks, inline hooks)
  - Suspicious memory regions (RWX pages)
  - Shellcode identification y analysis

**Windows Artifacts Analysis**
- **Registry Forensics**
  - User Hive (NTUSER.DAT) - Recent files, MRU, typed paths
  - System Hive - Network config, device info, installed software
  - SAM Hive - User passwords (NTLM hashes)
  - Security Hive - Audit events, password policy
  - Software Hive - Installation history, run keys
  - USB device history (USBSTOR, DeviceClasses)
  - Recent file access y last write times

- **Prefetch Analysis** (PECmd, ShellBagsExplorer)
  - Program execution timeline
  - Execution count y last execution timestamp
  - File access patterns during execution
  - Evidence of previously executed programs

- **Event Log Forensics**
  - Security Log (Event ID analysis - login/logout 4624/4625)
  - System Log (Driver/service events)
  - Application Log (software-specific events)
  - PowerShell Operational Log (4103-4106 detailed execution)
  - Windows Defender Operational Log (malware detections)
  - Task Scheduler Log (scheduled task execution)

- **Additional Windows Artifacts**
  - Shellbags - User folder interaction history
  - Jump Lists - Recently used files/programs
  - Link Files (.LNK) - Shortcuts with metadata
  - Recycle Bin ($I files) - Deleted file metadata
  - Thumbnail Cache - Visual evidence of accessed files
  - MFT (Master File Table) timeline

**Linux/macOS Forensics**
- **Log File Analysis**
  - `/var/log/auth.log` - User authentication events
  - `/var/log/syslog` - System-wide events
  - `/var/log/audit/audit.log` - auditd detailed records
  - Application-specific logs (/var/log/apache2, nginx, etc.)
  
- **Artifact Recovery**
  - Bash history (.bash_history) - Command execution timeline
  - Shell command reconstruction
  - SSH key detection y analysis
  - Cron job enumeration (scheduling, persistence)
  - Service startup analysis (/etc/init.d, systemd)
  - File access times (atime, mtime, ctime) analysis

- **Filesystem Analysis**
  - inode timeline generation
  - Deleted file recovery (carving)
  - File slack space inspection
  - Extended attributes examination

**Timeline Analysis & Correlation**
- Temporal evidence correlation
- Event sequencing y chain building
- Date discrepancy analysis (timestamp anomalies)
- Suspicious timing pattern detection
- Root cause analysis (RCA) through timeline

**Tools Ecosystem:** `Volatility 3` • `Autopsy` • `FTK Imager` • `Registry Explorer` • `ShellBagsExplorer` • `Plaso` • `Sleuthkit` • `Caine OS`

</div>

### 🛡️ Threat Detection & Intelligence

<div style="background:rgba(0,100,200,0.08); border:1px solid #0064C8; border-radius:8px; padding:15px; margin:10px 0;">

**YARA Rule Development**
```yara
rule Malware_Detection_Example {
    meta:
        description = "Detects malware indicators"
        author = "ASMODAX-OPS"
        severity = "high"
    strings:
        $mz = { 4D 5A }
        $api = "CreateRemoteThread"
        $mutex = "Global\\Mutex"
    condition:
        $mz at 0 and ($api or $mutex)
}
```
- Hash-based detection (MD5, SHA1, SHA256)
- Behavioral signature development
- Yara-rules repository integration

**Sigma Rule Development**
```yaml
title: Suspicious PowerShell Execution
logsource:
  product: windows
  service: security
detection:
  selection:
    EventID: 4688
    Image|endswith: 'powershell.exe'
    CommandLine|contains:
      - 'bypass'
      - 'DownloadFile'
  condition: selection
```
- SIEM-agnostic detection logic
- Log source abstraction
- Multiple SIEM backend support

**Threat Intelligence**
- MITRE ATT&CK framework mapping
- TTP (Tactic, Technique, Procedure) classification
- IOC (Indicators of Compromise) collection y management
  - File hashes (MD5, SHA1, SHA256, SSDEEP)
  - IP addresses y CIDR ranges
  - Domain names y URLs
  - Email indicators y header analysis
  
- Threat feed integration
  - AlienVault OTX automation
  - Shodan API integration
  - VirusTotal API queries
  - Custom threat feeds
  
- Threat actor profiling
  - Infrastructure analysis
  - Malware variant tracking
  - Operational security assessment
  - Attribution techniques

**Advanced Threat Hunting**
- Hypothesis-driven hunting methodology
- Anomaly detection query development
- Lateral movement detection
- Data exfiltration pattern analysis
- Persistence mechanism identification
- Privilege escalation chain detection

**Tools Ecosystem:** `YARA` • `Sigma` • `CyberChef` • `Shodan` • `VirusTotal API` • `MITRE ATT&CK Navigator` • `Maltego`

</div>

### 📊 SIEM, Logs & Analytics

<div style="background:rgba(0,100,200,0.08); border:1px solid #0064C8; border-radius:8px; padding:15px; margin:10px 0;">

**Splunk (SPL) Expertise**
```spl
index=main sourcetype=WinEventLog:Security EventCode=4688
| stats count by ComputerName, User
| where count > 100
| table _time, ComputerName, User, ParentImage, Image
```
- Query language mastery
- Sourcetype configuration y tuning
- Field extraction (Regex, delimiters, props.conf)
- Lookup tables y data enrichment
- Data model acceleration
- Alert configuration y threshold tuning
- Dashboard creation y visualization
- Scheduled search automation

**Elastic Stack (ELK) Expertise**
```json
GET /logs-*/_search
{
  "query": {
    "bool": {
      "must": [
        {"match": {"event.code": 4688}},
        {"range": {"@timestamp": {"gte": "now-1h"}}}
      ]
    }
  }
}
```
- Elasticsearch Query DSL mastery
- Logstash pipeline configuration
- Kibana visualization y dashboarding
- Index pattern management
- Ingest pipeline development
- Machine learning job configuration
- Anomaly detection setup

**Sysmon Advanced Configuration**
- Event filtering y intelligent whitelisting
- Image Load Monitoring (Event 7)
- CreateRemoteThread Detection (Event 8)
- Process Creation Logging (Event 1)
- Network Connection Tracking (Event 3)
- File Creation Monitoring (Event 11)
- Registry Operations (Events 12-14)
- WMI Activity (Events 19-21)
- Clipboard Capture (Event 24)
- Custom configurations por entorno

**Windows Event Log Mastery**
- Security Log auditing (Event ID analysis)
- System Log monitoring
- Application Log investigation
- PowerShell Operational Log (4103, 4104)
- Windows Defender Operational Log
- Task Scheduler Event Log
- DNS Query Logging (Event 22)
- File Share Access Logging (Event 5145)

**Log Normalization & Parsing**
- CEF (Common Event Format) parsing
- Syslog standard parsing
- Custom log format handling
- Field mapping y normalization
- Timestamp normalization (timezone awareness)
- Data type conversion y validation

**Tools Ecosystem:** `Splunk` • `Elastic Stack (ELK)` • `Sysmon` • `Winlogbeat` • `Filebeat` • `Metricbeat` • `Auditbeat` • `Fluentd`

</div>

### 🔒 Security Hardening & Compliance

<div style="background:rgba(0,100,200,0.08); border:1px solid #0064C8; border-radius:8px; padding:15px; margin:10px 0;">

**CIS Benchmarks Implementation**
- CIS Controls v8 framework adherence
- CIS Benchmarks hardening
  - Windows 10/11 hardening
  - Windows Server 2019/2022
  - Linux (Ubuntu, CentOS, RHEL)
  - Docker container security
  - Kubernetes cluster hardening
  
- Automated compliance scanning
- Remediation script development
- Configuration drift detection

**STIG Implementation**
- DoD STIG compliance
- OS hardening (Windows/Linux)
- Application STIGs
- Web server hardening (Apache, Nginx)
- Database STIGs
- Compliance verification (STIG Viewer)

**Active Directory Hardening**
- AD Tiering Model (Tier 0/1/2)
- Privileged Account Management (PAM)
- Just-In-Time (JIT) access
- Just-Enough-Administration (JEA)
- Credential Guard implementation
- Attack Surface Reduction (ASR) rules

**Group Policy & Endpoint Security**
- LGPO tool configuration
- Security policy implementation
- AppLocker configuration
- Device Guard/Code Integrity
- Windows Defender configurations

**Network Segmentation**
- Zero-Trust architecture
- Microsegmentation strategies
- Network access control (NAC)

**Tools:** `CIS-CAT` • `OVAL Compliance` • `Nessus` • `OpenVAS` • `Nuclei` • `Tenable`

</div>

---

## 🚀 CYBER ARSENAL

### 🐍 GHOSTHOUND SCOUT v2.1

<div style="background:linear-gradient(135deg, rgba(138,43,226,0.1), rgba(0,212,255,0.1)); border:2px solid #8A2BE2; border-radius:10px; padding:20px; margin:15px 0;">

**Advanced Active Directory Reconnaissance Toolkit**

**Descripción Técnica**
Herramienta de reconocimiento de Active Directory desarrollada en Python 3.x, diseñada para automatizar la enumeración completa de dominios, identificación de rutas de ataque y documentación de cadenas de explotación. Integra múltiples motores de escaneo con ejecución controlada y análisis integrado.

**Arquitectura Modular**
```
ghosthound_scout/
├── core/
│   ├── engine.py              # Motor principal
│   ├── config.py              # Configuración global
│   └── logger.py              # Logging estructurado
├── modules/
│   ├── nmap_enum.py           # Escaneo de puertos Nmap
│   ├── ad_recon.py            # Enumeración LDAP/AD
│   ├── web_scanner.py         # Gobuster + WhatWeb
│   ├── bloodhound_gen.py      # Generación datos BH
│   └── report_engine.py       # Reportes HTML
├── payloads/
│   ├── shells/                # Plantillas de reverse shells
│   ├── encoders/              # Ofuscación y encoding
│   └── stagers/               # Staged payload loaders
└── ghosthound.py              # Punto de entrada
```

**Módulos Principales**
- **Nmap Integration** - Scripts NSE, detección de servicios, evasión IDS
- **AD Reconnaissance** - Enumeración LDAP, detección Kerberoastable, delegation abuse
- **Web Scanner** - Subdomain enumeration, directory brute-force, tech identification
- **BloodHound Engine** - Recolección datos, visualización rutas ataque
- **Report Engine** - Reportes HTML profesionales con gráficos

**Características Premium**
- ✅ Multi-threading configurable (10-50 threads)
- ✅ Database caching (SQLite) para re-runs rápidos
- ✅ CLI real-time con Rich library
- ✅ Webhook notifications (Slack/Discord)
- ✅ REST API endpoints
- ✅ Plugin architecture extensible
- ✅ Stealth mode con timing randomization

**Stack Técnico**
`Python 3.9+` • `Nmap` • `LDAP` • `Requests` • `BeautifulSoup` • `SQLite` • `Rich CLI`

**Status:** v2.1.0 | 60% Development | 4200+ LOC | 82% Test Coverage

**Enlaces:** [Repository](https://github.com/ASMODAX-OPS/ghosthound-scout) | [Documentation](https://github.com/ASMODAX-OPS/ghosthound-scout/wiki)

</div>

---

## 📈 MÉTRICAS & ESTADÍSTICAS

<div style="background:#0d1117; border:1px solid #30363d; border-radius:8px; padding:15px; margin:15px 0;">

| Métrica | Estado | Detalle |
|---------|--------|---------|
| **GitHub Profile** | Activo | Red Team + Blue Team Content |
| **Languages** | Python, Bash, PowerShell, Go | Primary security tools |
| **Focus Areas** | Red/Blue Ops | AD Exploitation, DFIR, AppSec |
| **Last Activity** | Ongoing | Active research & development |

**Visita:** [github.com/ASMODAX-OPS](https://github.com/ASMODAX-OPS) para estadísticas en vivo

</div>

---

## 🎯 LEARNING ROADMAP & OBJETIVOS

<div style="background:#0d1117; border:1px solid #30363d; border-radius:8px; padding:15px; margin:15px 0;">

### 🐍 GHOSTHOUND SCOUT 2.1 Development
**Status:** Beta Testing Phase

```
[██████████░░░░░░░░] 60% - Core enumeration modules complete
├─ ✅ Nmap integration & parsing
├─ ✅ LDAP reconnaissance engine
├─ ✅ BloodHound data generation
├─ ⏳ REST API endpoints
└─ ⏳ Advanced reporting dashboard
```

### 🧪 HTB Pro Lab: Dante - Enterprise Infrastructure
**Status:** In Progress

```
[███░░░░░░░░░░░░░░░] 35% - Initial access chains mastered
├─ ✅ Reconnaissance techniques
├─ ✅ Scanning & enumeration
├─ ⏳ Lateral movement chains
├─ ⏳ Privilege escalation
└─ ⏳ Persistence mechanisms
```

### 📚 Volatility 3 & Memory Forensics Mastery
**Status:** Advanced Level

```
[████████░░░░░░░░░░] 75% - RAM analysis expertise
├─ ✅ Memory image acquisition
├─ ✅ Process analysis & rootkit detection
├─ ✅ DLL/module enumeration
├─ ✅ Network connection analysis
├─ ⏳ Custom plugin development
└─ ⏳ Real-time memory forensics
```

</div>

---

## 🌐 CONEXIONES & REDES PROFESIONALES

<div align="center" style="margin:25px 0;">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tu-perfil)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/tu-id)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ASMODAX-OPS)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hack-the-box&logoColor=black)](https://hackthebox.eu/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-EF3B2D?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/)

</div>

---

## 📡 Open to Collaboration & Partnerships

<div style="background:#0d1117; border:2px solid #00d4ff; border-radius:10px; padding:20px; margin:15px 0;">

**🤝 Opportunities**
- 🔴 Red Team Operations - Penetration testing, threat emulation
- 🔵 Blue Team Projects - DFIR, threat hunting, detection engineering
- 🎯 Security Tool Development - Python libraries, Go utilities
- 📚 Research & Content - Technical writeups, threat analysis
- 🏆 CTF Competitions - HackTheBox, TryHackMe, OSINT

**📧 Contact Channels**
- GitHub: Issue-based inquiries
- LinkedIn: Direct message
- Discord: ASMODAX-OPS#xxxx
- Email: [your-email@domain.com]

</div>

---

## 📚 Certifications & Education

<div style="background:#0d1117; border:1px solid #30363d; border-radius:8px; padding:15px; margin:15px 0;">

| Status | Certificación | Organización | Año |
|--------|---------------|--------------|-----|
| ✅ | CompTIA Security+ | CompTIA | 2023 |
| ✅ | Google Cybersecurity Professional | Google | 2023 |
| ✅ | Practical Network Penetration Tester (PNPT) | TCM Security | 2024 |
| 🔄 | Offensive Security Certified Professional (OSCP) | Offensive Security | 2024-2025 |
| 🔄 | Certified Ethical Hacker (CEH) | EC-Council | 2024-2025 |

</div>

---

## ⚖️ Legal Disclaimer

<div style="background:rgba(255,0,0,0.05); border:2px solid #ff0000; border-radius:8px; padding:15px; margin:15px 0;">

```
⚠️  AVISO LEGAL

Todas las herramientas, técnicas y metodologías compartidas en este repositorio
están destinadas EXCLUSIVAMENTE para pruebas de seguridad AUTORIZADAS, fines
educativos e investigación defensiva.

❌ USOS PROHIBIDOS:
   • Acceso no autorizado a sistemas informáticos
   • Hacking malicioso o ciberataques
   • Violación de Computer Fraud and Abuse Act (CFAA)
   • Cualquier actividad ilegal bajo ley nacional/internacional

✅ USOS AUTORIZADOS:
   • Pruebas de penetración autorizadas (con permiso escrito)
   • Investigación de seguridad en entornos controlados
   • Competiciones educativas (CTF, HackTheBox, THM)
   • Trabajo profesional en ciberseguridad

🔐 RESPONSABILIDAD
   El autor NO asume responsabilidad por mal uso, acceso no autorizado,
   o daños derivados del uso inadecuado de herramientas/técnicas.
   
   Usuarios son responsables de cumplir todas las leyes aplicables
   en su jurisdicción.
```

</div>

---

<div align="center" style="margin:30px 0; padding:20px; background:#0d1117; border-radius:8px;">

### 🔐 Security First • Ethics Always

**"In the shadows of the network, knowledge becomes power."**

---

**Last Updated:** 2024 | **Status:** Active Development | **Maintainer:** ASMODAX-OPS

[📤 Back to Top](#-asmodax-ops)

</div>
