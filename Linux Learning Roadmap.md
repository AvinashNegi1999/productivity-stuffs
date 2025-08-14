# 🐧 Linux Learning Roadmap (with Timeline)
![Time](https://img.shields.io/badge/Time-5–8%20hrs%2Fwk-blue)
![Level](https://img.shields.io/badge/Level-Beginner%E2%86%92Intermediate-brightgreen)
![Track](https://img.shields.io/badge/Focus-Hands%20on%20Projects-orange)

> 💡 Use a VM (VirtualBox/UTM) or WSL2 if you can’t dual-boot. Keep a notes repo and push weekly.

---

## 🗓️ Standard Timeline — 12 Weeks

### Week 1 — Setup & Orientation
- **Goals:** Install a distro, terminal basics, help/man pages.
- **Do:** Install [Ubuntu](https://ubuntu.com) or [Linux Mint](https://linuxmint.com); learn `pwd`, `ls`, `cd`, `man`.
- **Watch/Read:** [freeCodeCamp: Linux for Beginners](https://www.youtube.com/watch?v=sWbUDq4S6Y8)
- **Deliverable:** VM/WSL ready, a 1-page cheat sheet.

### Week 2 — Filesystem & Text Utilities
- **Goals:** Hierarchy (`/etc`, `/var`…), paths, wildcards, I/O redirection.
- **Do:** Practice `cat`, `less`, `head/tail`, `cp/mv/rm`, `find`, `grep`, pipes.
- **Course:** [Linux Command Line Bootcamp (Udemy)](https://www.udemy.com/course/the-linux-command-line-bootcamp/)
- **Deliverable:** A “dotfiles” folder with aliases/functions.

### Week 3 — Users, Groups & Permissions
- **Goals:** `chmod`, `chown`, umask, SUID/SGID, `sudo`.
- **Watch:** [Linux Permissions Tutorial](https://www.youtube.com/watch?v=ZtqBQ68cfJc)
- **Deliverable:** Script to set correct perms for a project directory.

### Week 4 — Package Management
- **Goals:** APT/DNF/YUM, repos, updates, services basics.
- **Watch:** [APT/YUM/DNF Overview](https://www.youtube.com/watch?v=V2t5cCHo1Z0)
- **Deliverable:** System updated, list of essential packages with notes.

### Weeks 5–6 — Bash Scripting & Automation
- **Goals:** Variables, conditionals, loops, functions, `cron`, `systemd` timers.
- **Learn:** [Bash Scripting – freeCodeCamp](https://www.youtube.com/watch?v=tK9Oc6AEnR4)
- **Deliverables (pick 2):**
  - Backup script (tar + date + rotate)
  - Log parser (`grep | awk | sed`) with report
  - Dotfile bootstrapper (`ln -s` / install script)

### Week 7 — Networking Basics
- **Goals:** IP/DNS/ports; tools: `ip`, `ss`, `netstat`, `dig`, `traceroute`, `curl`.
- **Watch:** [Linux Networking Commands](https://www.youtube.com/watch?v=VzwbGaxc7nk)
- **Deliverable:** Network diagnostics script that saves results to `/var/log`.

### Week 8 — Services & systemd
- **Goals:** `systemctl`, unit files, targets, logs with `journalctl`.
- **Do:** Create a simple `systemd` service for your script.
- **Deliverable:** Custom service runs at boot, has a log, and a restart policy.

### Week 9 — Processes, Logs & Storage
- **Goals:** `ps`, `top/htop`, `nice/renice`, `kill`; log rotation; disks with `lsblk`, `df`, `du`, mount/umount.
- **Watch:** “Linux Monitoring Basics” (any recent 30–60m tutorial)
- **Deliverable:** Monitoring script emailing/saving CPU/mem/disk alerts.

### Week 10 — Security Fundamentals
- **Goals:** Firewall, SSH hardening, basic audit, updates.
- **Do:** Set up `ufw`/`firewalld`, key-based SSH, disable root login.
- **Watch:** [Linux Security Basics](https://www.youtube.com/watch?v=Rsl8xJ_c3OY)
- **Deliverable:** Hardened VM checklist (repo markdown).

### Week 11 — Mini-Project (Pick One)
- **Options:**
  - **Web server:** Nginx + TLS + logrotate + `fail2ban`
  - **Dev workstation:** Shell, Git, Docker, language toolchains
  - **Home server:** Samba/NFS + backups + uptime monitor
- **Deliverable:** README with architecture, commands, and a makefile/script.

### Week 12 — Practice & Cert Readiness
- **Goals:** Review gaps; practice challenges.
- **Practice:** [OverTheWire Wargames](https://overthewire.org/wargames/)
- **Cert Path:** [LPI Linux Essentials / LPIC-1](https://www.lpi.org/our-certifications/linux-professional-institute-certifications-overview)
- **Deliverable:** Study notes + exam date target (optional).

---

## ⚡ Fast-Track — 4 Weeks (10–12 hrs/wk)

| Week | Focus | Outcome |
|---|---|---|
| 1 | Install, CLI, FS, perms | Cheat sheet + dotfiles repo |
| 2 | Packages, Bash scripting | 2 automation scripts + `cron` |
| 3 | Networking, systemd | Custom service + net-diag report |
| 4 | Security + Mini-project | Hardened VM + Nginx/Docke
