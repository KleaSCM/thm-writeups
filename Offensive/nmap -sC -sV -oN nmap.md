
- Ports: 22, 80
- Webpage hosted on port 80, default Apache
- Used Gobuster: found `/dev`, `/backup`

## 🌐 Web Recon
- `backup.zip` found with credentials
- Extracted creds: `user: password123`

## 🔑 Access
- SSH access granted
- Valid shell

## ⚙️ Privilege Escalation
- Ran `linpeas.sh`, found SUID binary
- Exploited to get root

## 🏁 Root Flag
