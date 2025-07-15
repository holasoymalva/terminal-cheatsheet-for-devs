# 🔐 SSH & SCP Essentials

Remote access and file transfers with SSH.

## 🔐 Connect to a Server

```bash
ssh user@host
```

## 📂 Transfer Files

```bash
scp localfile.txt user@host:/path/
scp -r folder/ user@host:/path/
```

## 🔑 SSH Keys

```bash
ssh-keygen -t rsa -b 4096
ssh-copy-id user@host
```