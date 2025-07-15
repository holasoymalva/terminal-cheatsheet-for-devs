# 🌐 Networking CLI Commands

Useful tools for networking diagnostics and exploration.

## 📡 Connectivity

```bash
ping -c 4 google.com
traceroute google.com
```

## 🔍 DNS & Lookup

```bash
nslookup github.com
dig github.com
```

## 🌐 HTTP Requests

```bash
curl -I https://example.com
curl -X POST -d "key=value" https://example.com
```

## 🔗 Ports & Listening

```bash
netstat -tulnp
lsof -i :3000
```