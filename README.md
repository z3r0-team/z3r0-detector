
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=00FF00&center=true&vCenter=true&width=435&lines=z3r0-detector+by+binyourbae" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Coded%20By-binyourbae-blue?style=flat-square&logo=github" />
  <img src="https://img.shields.io/badge/Team-%23CianjurHacktivist%20x%20z3r0--team!-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Language-Go-00ADD8?style=flat-square&logo=go" />
</p>

---

```
███████ ██████  ██████   ██████        ██████  ███████ ████████ ███████  ██████ ████████  ██████  ██████  
   ███       ██ ██   ██ ██  ████       ██   ██ ██         ██    ██      ██         ██    ██    ██ ██   ██ 
  ███    █████  ██████  ██ ██ ██ █████ ██   ██ █████      ██    █████   ██         ██    ██    ██ ██████  
 ███         ██ ██   ██ ████  ██       ██   ██ ██         ██    ██      ██         ██    ██    ██ ██   ██ 
███████ ██████  ██   ██  ██████        ██████  ███████    ██    ███████  ██████    ██     ██████  ██   ██                                                                                                         
```

### ⚡ z3r0-detector
`z3r0-detector` is a **massive multi-path detection tool** built in Go, optimized with **goroutines + automatic multi-core support**. Perfect for large-scale scanning using target lists, paths, and keyword matches.

---

### 🧪 File Structure

| File         | Description                                       |
|--------------|---------------------------------------------------|
| `paths.txt`  | List of endpoint paths to scan (`/admin`, `/login`, etc) |
| `detects.txt`| List of strings/keywords to search in responses   |
| `z3r0-detector`    | The main Go file containing all scanner logic     |

---

### 🚀 How to Run

```bash
./z3r0-detector
```

Follow the interactive prompt:
```
Enter number of threads:
Enter target list filename:
```

---

### 📁 Example File Content

**detects.txt**
```
Welcome
Login
Index of
```

**paths.txt**
```
/
admin
wp-login.php
```

**targets.txt**
```
site1.com
http://site2.org
https://site3.net
```

---

### 💀 Credits

> 🚩 Developed with ❤️ by `binyourbae` x `#CianjurHacktivist - z3r0-team!`

---

<p align="center"><i>Hack the signal, not the soul.</i></p>
