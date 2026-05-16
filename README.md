
```markdown
# 🐛 WormGPT — AI Terminal Interface
> **Next-Gen Cyberpunk CLI Interface Powered by BintangAPI**

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![API](https://img.shields.io/badge/BintangAPI-v4-E11D48?style=for-the-badge&logo=google-cloud&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-059669?style=for-the-badge)

<p align="center">
  <a href="#-fitur-utama">Fitur Utama</a> •
  <a href="#-instalasi">Instalasi</a> •
  <a href="#-cara-penggunaan">Cara Pakai</a> •
  <a href="#-arsitektur-sesi">Sistem Sesi</a>
</p>

---

</div>

## 🌌 Tentang Project

**WormGPT AI Terminal Interface** adalah aplikasi berbasis CLI (Command Line Interface) yang dirancang untuk memberikan pengalaman berinteraksi dengan AI secara radikal. Mengusung estetika *dark-mode terminal*, program ini tidak hanya fungsional tetapi juga memanjakan mata dengan layout box-drawing yang presisi dan animasi fluid.

---

## ✨ Fitur Utama

| Fitur | Deskripsi | Estetika |
| :--- | :--- | :--- |
| **🖥️ Premium UI** | Render otomatis menggunakan *ANSI Colors* tingkat tinggi dan structural *box-drawing*. | `Cyberpunk Red` |
| **💬 Session Manager** | Mendukung multi-chat dinamis. Pindah sesi, hapus riwayat, atau lacak ID secara *real-time*. | `Smart Cache` |
| **⏳ Fluid Animation** | Efek *typewriting* responsif dan *animated custom spinner* saat AI sedang berpikir. | `Smooth 0.08s` |
| **🟢 Raw Code Block** | Output kode dipisahkan dengan separator khusus tanpa memotong indentasi asli (mudah di-copy). | `Syntax Ready` |

---

## 🛠️ Instalasi

Cukup jalankan beberapa baris perintah ini di terminalmu:

```bash
# 1. Clone repositori ke lokal
git clone [https://github.com/USERNAME_GITHUB_KAMU/wormgpt-cli.git](https://github.com/USERNAME_GITHUB_KAMU/wormgpt-cli.git)

# 2. Masuk ke direktori project
cd wormgpt-cli

# 3. Install dependency utama
pip install requests

```
## 🎮 Cara Penggunaan
Jalankan script utama dengan perintah berikut:
```bash
python3 main.py

```
### ⌨️ Navigasi Perintah Internal
Saat berada di dalam chat, kamu bisa mengetikkan perintah khusus ini di prompt:
 * menu atau help — Membuka **Panel Kendali Utama** (Ubah sesi, cek memori, reset).
 * clear — Membersihkan layar terminal dan merender ulang logo utama.
 * exit atau quit — Menutup sesi terminal secara aman.
## 📊 Panel Arsitektur Sesi
Aplikasi ini dilengkapi dengan penjejak otomatis yang terhubung ke server pusat:
```
 ╔════ [ PANEL INFORMASI ] ════════════════════════════════════════╗
 ║  Chat ID    : chat_xxxxxx (Dinamis)                             ║
 ║  Memory ID  : Terenkripsi via BintangAPI                        ║
 ║  Interface  : Python Terminal Interactive Engine                ║
 ╚═════════════════════════════════════════════════════════════════╝

```
## 👨‍💻 Developer & Framework
Project ini dikembangkan sepenuhnya oleh **Bintang** dan berjalan di bawah payung **BintangGPT Development Framework**.
<div align="center">
**[ BINTANGTOOLS ECOSYSTEM © 2026 ]**
</div>
