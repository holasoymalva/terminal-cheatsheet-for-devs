# 🖥️ Terminal Cheatsheet for Developers

> ✨ A curated guide to essential terminal commands every developer should master.  
> Created by [@holasoymalva](https://github.com/holasoymalva) 🐚

---

## 🧠 Why this exists

As developers, we often copy/paste terminal commands without truly understanding them. This repo is meant to be your go-to reference for **clear**, **actionable**, and **explained** terminal commands — from Git to Docker to SSH to npm to process monitoring and beyond.

Whether you’re a beginner or seasoned dev, this will help you save time and feel more confident in the command line.

---

## 📦 Sections

- [🔧 Git Essentials](#-git-essentials)
- [🌐 Networking (cURL, Ping, Netstat)](#-networking)
- [🐧 Linux Basics](#-linux-basics)
- [📁 File & Folder Management](#-file--folder-management)
- [📦 Package Managers (npm, apt, brew)](#-package-managers)
- [🐳 Docker CLI](#-docker-cli)
- [⚡ Process Management](#-process-management)
- [🔒 SSH + SCP](#-ssh--scp)
- [🧪 Dev Utilities (npx, grep, sed, jq)](#-dev-utilities)
- [📜 Bonus: Useful dotfiles & aliases](#-bonus-useful-dotfiles--aliases)

---

## 🔧 Git Essentials

```bash
git log --oneline --graph --decorate
````

> Visualize your git history like a pro (branches, tags, commits).

```bash
git stash -u
```

> Temporarily save untracked changes too.

```bash
git reset --soft HEAD~1
```

> Undo last commit but keep the changes staged.

📚 [More Git Commands →](docs/git.md)

---

## 🐳 Docker CLI

```bash
docker ps -a
```

> List all containers, running or not.

```bash
docker images
```

> See all downloaded images.

```bash
docker exec -it <container_id> bash
```

> Access a running container interactively.

📚 [More Docker Commands →](docs/docker.md)

---

## 🌐 Networking

```bash
curl -I https://example.com
```

> Fetch only headers from a request.

```bash
ping -c 4 google.com
```

> Check connectivity to a host (limit to 4 pings).

📚 [More Networking Commands →](docs/networking.md)

---

## 📁 File & Folder Management

```bash
ls -lah
```

> List files with human-readable sizes and hidden files.

```bash
rm -rf node_modules/
```

> Remove folder recursively and forcefully. ⚠️ Caution!

📚 [More File Commands →](docs/files.md)

---

## 🧪 Dev Utilities

```bash
npx create-react-app my-app
```

> Create a new React app without installing globally.

```bash
grep -r "myKeyword" .
```

> Search recursively for a keyword in files.

```bash
jq '.data[] | .name' data.json
```

> Parse and filter JSON from the CLI.

---

## 🎁 Bonus: .bashrc / .zshrc Aliases

```bash
alias gs="git status"
alias gp="git push"
alias gc="git commit -m"
alias serve="python3 -m http.server"
```

---

## 💬 Contribute

Pull Requests welcome! Feel free to suggest more commands, corrections, or cool tricks.

---

## 🌍 Language Support

🌐 Spanish version coming soon → `terminal-cheatsheet-es.md`

---

## ⭐ Support the project

If this helped you, give it a ⭐, share it with your dev friends, or tweet it tagging [@holasoymalva](https://twitter.com/holasoymalva)!

---

## 📜 License

MIT — Created with 💻 by [@holasoymalva](https://github.com/holasoymalva)
