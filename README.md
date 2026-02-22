# 🏦 Dashboard AL — Finance Control System

Dashboard manajemen keuangan (Deposit & Withdraw) dengan login aman, statistik lengkap, dan export Excel.

## ✨ Fitur

- 🔐 **Login Aman** — Credentials terenkripsi dalam kode, tidak disimpan plain text
- 📊 **Overview Dashboard** — Statistik harian, mingguan, bulanan
- 💰 **Input Transaksi** — Deposit & Withdraw dengan tanggal dan username custom
- 📋 **History Lengkap** — Filter by tanggal, username, tipe transaksi
- 👥 **Data Per User** — Ringkasan per username
- 📥 **Export Excel** — Export history dan data user ke .xlsx
- 💾 **Data Persistent** — Data tersimpan di browser (localStorage), tidak hilang saat buka tab baru

## 🚀 Deploy ke GitHub Pages

1. Upload file `index.html` ke repository GitHub
2. Aktifkan GitHub Pages di Settings → Pages → Source: main branch
3. Akses via `https://username.github.io/nama-repo`

## 📁 File

- `index.html` — Aplikasi lengkap (single file, no dependencies except CDN)

## ⚠️ Catatan

- Data tersimpan di `localStorage` browser yang digunakan
- Jika pindah browser/device, data tidak ikut berpindah
- Untuk multi-device, gunakan backend database

---
*Dashboard AL v1.0 — Finance Control System*
