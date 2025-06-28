# 🛠️ PortScan - Simple Python Port Scanner

A fast and minimal command-line port scanner built in Python. Perfect for learning and scanning open ports like a pro. Works right from your terminal like a real tool!

---

## 🚀 Features

- 🔍 Scan any domain or IP
- 📊 Custom port range
- 🧠 Banner grabbing (when available)
- 💾 Save scan results to file
- ⚡ Fast, clean, and works like `httpx`

---

## ⚙️ Usage

```bash
portscan -t <target> -r <start-end> -o <output_file>
```

### 🧪 Example:

```bash
portscan -t scanme.nmap.org -r 1-100 -o result.txt
```

---

## 📦 Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd portscan
chmod +x portscan
sudo mv portscan /usr/local/bin/
```

✅ Now you can run it from anywhere:
```bash
portscan -t scanme.nmap.org -r 1-100 -o result.txt
```

---

## 📁 Output Sample

```
[+] Port 22 OPEN -> SSH-2.0-OpenSSH_6.6.1p1 Ubuntu-2ubuntu2.13
[+] Port 80 OPEN -> NO BANNER
✅ Scan complete!
```

---

## 🔧 Requirements

- Python 3.x
- No external libraries needed — 100% built-in modules

---

## 💡 Pro Tips

- Always run with permission (ethical use only)
- Works best on Linux/macOS (tested on Kali Linux)
- Customize for your own toolchain or add threading

---

## ✨ Author

Made with love by **Inder**  
[🔗 GitHub](https://github.com/inder33) | Feel free to star ⭐ and contribute

---
