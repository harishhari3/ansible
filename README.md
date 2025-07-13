# Ansible Apache2 Installer

This project uses **Ansible** to install the Apache2 web server on a target system (either localhost or remote).

---

## 📦 Features

- Updates APT package cache
- Installs Apache2
- Works on Ubuntu-based systems
- Supports localhost or remote via SSH

---

## 🛠️ Files Included

| File                | Description                                |
|---------------------|--------------------------------------------|
| `sh.yml`            | Ansible playbook to install Apache2        |
| `localhost_apache.yml` | Playbook to run locally without SSH     |
| `hosts.ini`         | Inventory file for remote servers (if used) |

---

## 🚀 How to Use

### ▶️ For Localhost (No SSH)

```bash
sudo ansible-playbook localhost_apache.yml

