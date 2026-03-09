# 🚫 IPBlock

> PowerShell script to **download malware blocklists** and **block IPs via Windows Firewall** — Spamhaus DROP, Emerging Threats, Zeus/Feodo Trackers, Talos, FireHOL.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📥 **Blocklists** | Spamhaus DROP, Emerging Threats, Zeus, Feodo, CINS, Talos, FireHOL Level 3 |
| 🔥 **Firewall Rules** | Creates inbound/outbound block rules per IP/range |
| 📋 **Whitelist** | Configurable exceptions |
| 📝 **Logging** | Logs to `Documents\block_log.txt` |
| ⚙️ **DryRun** | Preview without applying |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |
| **Network** | Internet for blocklist downloads |

---

## 🚀 Usage

```powershell
# Apply block rules
.\IPBlock.ps1

# Preview only (no changes)
.\IPBlock.ps1 -DryRun
```

---

## 📁 Paths

| Path | Purpose |
|------|---------|
| `Documents\PeerBlockLists` | Downloaded blocklists |
| `Documents\block_log.txt` | Log file |

---

<p align="center">
  <sub>🛡️ Gorstak Security Tooling</sub>
</p>
