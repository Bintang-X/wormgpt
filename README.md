<div align="center">

<img src="https://bintangapi.full.diskon.cloud/logo/wormgpt.jpg" alt="WormGPT by Bintang" width="100%"/>

# 🐛 WORMGPT BY BINTANG
### *AI Terminal Interface — Powered by BintangAPI*

[![Python](https://img.shields.io/badge/Python-3.8+-dc143c?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-8b0000?style=for-the-badge)](LICENSE)
[![BintangAPI](https://img.shields.io/badge/Powered_by-BintangAPI-ff1a1a?style=for-the-badge&logoColor=white)](https://bintangapi.full.diskon.cloud)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Android-b22222?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/Bintang-X/wormgpt)

> **Chat AI langsung dari terminal. No browser. No GUI. Pure terminal vibes.** 🔥

</div>

---

## ✨ Fitur

| Fitur | Keterangan |
|-------|-----------|
| 🤖 **AI Chat** | Chat dengan WormGPT powered by BintangAPI |
| 💬 **Multi Chat** | Kelola beberapa sesi chat sekaligus |
| 🔀 **Switch Chat** | Pindah antar chat dengan mudah |
| 🆕 **New Chat** | Buat chat baru kapan aja |
| 🔄 **Reset Session** | Reset semua chat dalam satu klik |
| ⚡ **Auto Retry** | Auto reconnect kalau koneksi putus (3x percobaan) |
| 🎨 **Red Terminal UI** | UI merah khas Bintang Tools yang goks |
| 💻 **Code Highlighting** | Code block langsung di-render rapi di terminal |
| ⌨️ **Typewriter Effect** | Response AI ditampilkan kayak diketik live |
| 📊 **Status Bar** | Info chat ID, jumlah pesan, status API realtime |

---

## ⚙️ Requirements

- Python **3.8+**
- Library `requests`
- Terminal yang support **ANSI color** (Linux, macOS, Termux)

---

## 🚀 Cara Install & Jalanin

**1. Clone repo**

```bash
git clone https://github.com/Bintang-X/wormgpt.git
cd wormgpt
```

**2. Install dependency**

```bash
pip install requests
```

**3. Jalanin!**

```bash
python wormgpt.py
```

---

## 📱 Termux (Android)

Bisa jalan di Termux tanpa root!

```bash
pkg update && pkg upgrade
pkg install python git
pip install requests
git clone https://github.com/Bintang-X/wormgpt.git
cd wormgpt
python wormgpt.py
```

---

## 🎮 Cara Pakai

Setelah dijalanin, lo masuk ke menu utama dengan opsi:

1. 💬 **Lanjut Chat** — lanjut sesi yang lagi aktif
2. 🆕 **New Chat** — buat sesi chat baru
3. 🔀 **Switch Chat** — pilih dari daftar chat yang ada
4. 📊 **Info Session** — lihat info session & semua chat
5. 🔄 **Reset Semua Chat** — hapus semua sesi
6. 🧹 **Clear Layar** — bersihkan terminal
7. 🚪 **Keluar**

**Command cepat saat chat:**

| Command | Fungsi |
|---------|--------|
| `menu` / `help` | Buka menu |
| `clear` | Bersihkan layar |
| `exit` / `quit` / `q` | Keluar |

---

## 🛠️ Konfigurasi

Ganti API endpoint di `wormgpt.py` kalau perlu:

```python
API_URL = "https://bintangapi.full.diskon.cloud/api/aichat/wormgpt/"
```

> API ini ditenagai **BintangAPI** — gratis, langsung bisa dipake.

---

## 📁 Struktur File

```
wormgpt/
├── wormgpt.py     # Single file, langsung jalan
└── README.md
```

---

<div align="center">

## 👤 Author

**Bintang** — [@Bintang-X](https://github.com/Bintang-X)

*Part of the [Bintang Tools](https://bintangtools.diskon.cloud) ecosystem*

*Made with ❤️ & 🔴 by Bintang*

</div>
