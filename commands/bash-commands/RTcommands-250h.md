# ✅ Linux Commands Checklist – Red Team Fundamentals (0–250h)

This checklist covers essential Linux commands you'll need to get comfortable with during the early stages of your cybersecurity/Red Team journey.

---

## 🔐 Permissions & Ownership

- [ ] `whoami` — Show current user
- [ ] `id` — Show user and group IDs
- [ ] `sudo -l` — Check sudo privileges for the current user
- [ ] `chmod` — Change file permissions (e.g. `chmod +x file.sh`)
- [ ] `chown` — Change file ownership (e.g. `chown user:group file`)

---

## 🛠️ Process & System Info

- [ ] `ps aux` — List running processes
- [ ] `netstat -tulnp` or `ss -tuln` — View open/listening ports
- [ ] `lsof -i` — Show which processes use network connections
- [ ] `uname -a` — Display kernel version and system architecture
- [ ] `hostname` / `hostname -I` — View system name and IP address

---

## 📁 File & User Enumeration

- [ ] `find / -perm -4000 2>/dev/null` — Find SUID binaries (privilege escalation)
- [ ] `cat /etc/passwd` — View user account info
- [ ] `ls -la /home` — Explore user directories
- [ ] `env` — Show environment variables
- [ ] `history` — View command history (may contain useful info)

---

## 📡 Networking & File Transfer

- [ ] `ping <host>` — Check connectivity
- [ ] `dig <domain>` — DNS lookup
- [ ] `nslookup <domain>` — DNS query tool
- [ ] `curl <url>` — Download file via HTTP
- [ ] `wget <url>` — Another method to download files
- [ ] `scp user@host:/path/file .` — Secure file copy from remote machine
- [ ] `nc -lvnp 4444` — Start a Netcat listener (for reverse shell)
- [ ] `nc <ip> <port>` — Connect to a remote service (bind shell)

---

## 🧪 Execution of Scripts & Binaries

- [ ] `chmod +x file` — Make script or binary executable
- [ ] `./file` — Run a local binary or script
- [ ] `bash script.sh` — Run shell script
- [ ] `python3 script.py` — Run Python script

---

## 🗂 Archive Management

- [ ] `tar -xvf file.tar` — Extract tar archive
- [ ] `unzip file.zip` — Extract zip file

---

## 💡 Optional (Bonus)

- [ ] `crontab -l` — List user’s cron jobs
- [ ] `cat /etc/shadow` — (Restricted) View hashed passwords if accessible
- [ ] `top` / `htop` — Monitor system usage in real-time

---

## 🧠 Notes

Feel free to add examples of when you used these commands during a lab, TryHackMe room, or project. Tracking real usage helps cement the learning.

---

## ⏱️ Last Updated: 18-04-2025

