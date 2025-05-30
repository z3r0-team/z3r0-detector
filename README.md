
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=00FF00&center=true&vCenter=true&width=435&lines=z3r0-detector+by+binyourbae" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Coded%20By-binyourbae-blue?style=flat-square&logo=github" />
  <img src="https://img.shields.io/badge/Team-%23CianjurHacktivist-green?style=flat-square" />
</p>

---

```
███    ███  █████  ███████ ███████ ██████   ██████      
████  ████ ██   ██    ███    ███      ██ ██    ██     
██ ████ ██ ███████   ███     ███    █████  ██    ██     
██  ██  ██ ██   ██  ███     ███    ██     ██    ██     
██      ██ ██   ██ ███████ ███████  ██████   ██████     
```

### ⚡ z3r0-detector
`z3r0-detector` adalah **tool pendeteksi masif multi-path** berbasis Go, dengan concurrency tinggi menggunakan **goroutine + multi-core** otomatis. Cocok untuk scanning masal target dengan daftar path dan string keyword.

---

### 📦 Fitur Utama

✅ **Goroutine + GOMAXPROCS** → Full multicore  
✅ **Input custom thread + target list** via prompt  
✅ **Bypass SSL cert** otomatis  
✅ **Auto prepend HTTP/HTTPS** jika tidak ada protocol  
✅ **Timeout request: 7 detik**  
✅ **Output stylish:**

```
[FOUND]  site.com/path ~> "keyword" [1/10] + [3/20]
[ x ]    site.com/path ~> "keyword" [1/10] + [3/20]
```

✅ **Hasil disimpan otomatis ke:**
```
result/found-keyword.txt
```

✅ **Warna retro hacker:**
- `[ ]` → Cyan  
- `site.com` → Hijau (jika ditemukan)  
- `Not found` → Merah  
- `(1/10)` → Merah

---

### 🧪 Struktur File

| File         | Fungsi                                          |
|--------------|-------------------------------------------------|
| `paths.txt`  | Daftar path endpoint untuk dideteksi (`/admin`, `/wp-login.php`, dll) |
| `detects.txt`| Keyword / string yang akan dicari dalam response body |
| `main.go`    | File utama Go dengan semua logika scanning      |

---

### 🚀 Cara Jalankan

```bash
go run main.go
```

Ikuti instruksi input terminal:
```
Masukkan jumlah thread:
Masukkan nama file list target:
```

---

### 📁 Contoh Struktur File

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

### 💀 Credit

> 🚩 Coded with ❤️ by `binyourbae` x `#CianjurHacktivist`

---

<p align="center"><i>Hack the signal, not the soul.</i></p>
