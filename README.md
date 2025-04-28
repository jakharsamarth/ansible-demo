# 📦 Ansible + Docker Automation Demo

> **Goal**: Build Docker containers as servers and automate their setup using Ansible playbooks.

---

## 🛠️ Overview

This project shows:
- Building a custom **Ubuntu Docker image** with **OpenSSH Server** installed.
- Setting up **SSH key-based authentication**.
- Running **multiple servers** (`server1`, `server2`, etc.) inside Docker.
- Automating configuration with **Ansible**.
- Verifying server configuration using **Ansible modules** and manual tests.

---

## ⚙️ Full Setup Instructions (with Commands)

### 1. Generate SSH Key Pair
```bash
# Create a new SSH key pair (RSA 4096 bits)
ssh-keygen -t rsa -b 4096

# Copy keys to current directory for Docker build
cp ~/.ssh/id_rsa .
cp ~/.ssh/id_rsa.pub .


![Ansible Demo Screenshot] (ansible-demo/Screenshot from 2025-04-28 20-09-00.png)
