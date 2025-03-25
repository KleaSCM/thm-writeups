# <Room Name> 💻

**Platform**: [TryHackMe](https://tryhackme.com)  
**Room Link**: https://tryhackme.com/room/<room-name>  
**Difficulty**: <Easy / Medium / Hard>  
**Tags**: `#enum`, `#web`, `#ssh`, `#priv-esc`, etc.  
**Date Completed**: <Month Year>  
**Author**: [CyDieLia](https://github.com/CediLia)

---

## 📌 Room Overview

- **Goal**: <What does this room teach?>
- **Skills Practiced**: <Web exploitation, Linux enumeration, privilege escalation, etc.>
- **Tools Used**: `nmap`, `gobuster`, `hydra`, `linpeas`, `john`, `burpsuite`

---

## 🧭 Target Info

| Field       | Value               |
|-------------|---------------------|
| Target IP   | `10.10.10.10`        |
| OS          | Linux/Windows       |
| Services    | 22 (SSH), 80 (HTTP) |
| Notes       | <Any important notes about the setup or behavior>

---

## 🧠 Lessons Learned

| 💭 Concept                     | 💡 What I Took Away                                                                 |
|-------------------------------|--------------------------------------------------------------------------------------|
| File Looting 🗂️               | Don’t ignore backup files like `.zip`, `.tar`, or hidden dirs — gold mines for creds |
| SUID Exploitation ⚙️          | Custom or uncommon SUID binaries are serious privilege escalation candidates         |
| Local Enumeration 🛰️          | Tools like `linpeas` and manual checks (`sudo -l`, cron, PATH) are always step one   |
| Chain of Access 🔑 ➜ 🛡️       | Success = enumerate ➜ exploit ➜ escalate ➜ document                                 |
| Workflow Discipline 📋        | Writing while hacking reinforces memory and builds better habits                     |

> 📓 _“If it looks boring, it’s probably hiding root.”_ — ancient goblin proverb

---

## 📸 Screenshots

All screenshots related to this room are stored in the `images/` folder.  
Make sure to name them consistently like `<room-name>-<context>.png` for easy reference.

| 📷 Context           | Preview                                                                 |
|----------------------|-------------------------------------------------------------------------|
| Nmap Scan            | ![Nmap Scan](../images/<room-name>-nmap.png)                            |
| LinPEAS Output       | ![LinPEAS](../images/<room-name>-linpeas.png)                           |
| Root Shell Access    | ![Root Shell](../images/<room-name>-root-shell.png)                     |
| Web Recon            | ![Web Recon](../images/<room-name>-gobuster.png)                        |

> 📝 _Not all rooms will need screenshots — but if you got the shell, flex the shell._


---

## 📎 References

Below are useful resources consulted during this room or recommended for deeper learning:

- [TryHackMe Room – `<Room Name>`](https://tryhackme.com/room/<room-slug>)  
- [GTFOBins – SUID Binaries](https://gtfobins.github.io/)
- [HackTricks – Privilege Escalation](https://book.hacktricks.xyz/)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [Linux Privilege Escalation Checklist](https://github.com/sleventyeleven/linuxprivchecker)
- [HackTheBox Academy (Free Tier)](https://academy.hackthebox.com/)
- [Red Team Tools List (SecTools)](https://sectools.org/)

> 🧠 _You don't need to remember everything — just where to find it when you need it._



## 📚 Summary 


| 🧩 Phase           | 💡 Technique Used                                                   |
|--------------------|---------------------------------------------------------------------|
| 🔍 Enumeration     | `nmap`, `gobuster`, `whatweb`                                       |
| 🔑 Initial Access  | SSH login via credentials recovered from `backup.zip`               |
| ⚙️ Privilege Esc.  | Abused custom SUID binary: `/usr/bin/secret`                        |
| 🛠️ Tools Used      | `linpeas`, `john`, `ssh`, `scp`                                     |

> 🧠 **Key Takeaway**: Always inspect loose files like `.zip` archives — they may hold the keys to the kingdom.
