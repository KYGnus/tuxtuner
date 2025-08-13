# 🐧 TuxTuner

**TuxTuner** is an **Enterprise Linux Optimization & Hardening Tool** designed to improve **performance**, **security**, and **stability** across desktop, server, and embedded Linux systems.  
It supports **distribution-specific tuning**, **enterprise kernel tweaks**, **service optimization**, and **security hardening** — all from a single script.

---

## ✨ Features

### 🔹 Performance Optimization
- Enterprise-grade **kernel parameter tuning** for networking, memory, and I/O.
- CPU isolation for high-performance workloads.
- Power management optimizations for desktops and laptops.
- SSD optimizations and filesystem tuning.

### 🔹 Security Hardening
- SSH configuration hardening.
- Kernel-level security parameters.
- Firewall configuration (UFW or firewalld).
- Automatic installation & configuration of **Fail2Ban**.
- File permission lockdown.

### 🔹 Service Optimization
- Enable essential enterprise services.
- Disable unnecessary background services.
- Optimize `systemd` slices for resource allocation.
- Journald log rotation & storage management.

### 🔹 Distribution-Specific Profiles
- Ubuntu Desktop Optimization
- Debian Desktop Optimization
- Fedora Desktop Optimization
- CentOS Desktop Optimization
- openSUSE Desktop Optimization

---

## 📦 Supported Environments

- **Desktop**:
  - Storage server mode
  - Media server mode
- **Server**:
  - Storage server mode
  - Media server mode
  - IDS/IPS security mode
- **Embedded devices**
- **Enterprise Kernel / Services / Security** profiles

---

## 🚀 Installation

```bash
git clone https://github.com/<yourusername>/TuxTuner.git
cd TuxTuner
chmod +x tuxxuner
````

---

## 🛠 Usage

Run with the desired options:

```bash
./TuxTuner --ubuntu-desktop --enterprise-security
./TuxTuner --server --storageserver --enterprise-kernel
```

### 📌 Options Overview

| Option                     | Description                         |
| -------------------------- | ----------------------------------- |
| `--desktop --storage`      | Optimize desktop as storage server  |
| `--desktop --mediaserver`  | Optimize desktop as media server    |
| `--server --storageserver` | Optimize server as storage server   |
| `--server --mediaserver`   | Optimize server as media server     |
| `--server --idsips`        | Optimize server for IDS/IPS role    |
| `--embedded`               | Optimize for embedded devices       |
| `--ubuntu-desktop`         | Ubuntu desktop optimizations        |
| `--debian-desktop`         | Debian desktop optimizations        |
| `--fedora-desktop`         | Fedora desktop optimizations        |
| `--centos-desktop`         | CentOS desktop optimizations        |
| `--opensuse-desktop`       | openSUSE desktop optimizations      |
| `--enterprise-kernel`      | Apply enterprise kernel tuning      |
| `--enterprise-services`    | Optimize enterprise services        |
| `--enterprise-security`    | Apply enterprise security hardening |
| `--help`                   | Show help message                   |

---

## ⚠️ Disclaimer

This tool makes **low-level system changes**.

* **Use at your own risk**.
* **Backup important data** before running.
* Recommended for **experienced administrators**.

---

## 📜 License

This project is licensed under the **GPL-3.0 License** — free to use, modify, and share.

---

## 👨‍💻 Author

**KYGnus**
🌐 Website: [kygnus.de](kygnus.de)

