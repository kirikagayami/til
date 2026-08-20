# Configuring Passwordless SSH Authentication with ED25519

Quick summary of replacing HTTPS/PAT authentication on Kali Linux with an ED25519 SSH key pair.

## 1. Generate the SSH Key Pair
```bash
ssh-keygen -t ed25519 -C "kirikagayami"
