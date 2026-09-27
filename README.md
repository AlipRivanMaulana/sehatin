# Sehatin — Interactive Health App Prototype

Prototype aplikasi kesehatan **Sehatin** dengan desain mobile dan fitur interaktif berbasis HTML/CSS/JavaScript.

## ✨ Fitur
- Splash screen
- Login validation
- Dashboard / Home
- Bottom navigation
- Health Check (BMI + health score demo)
- Pencarian dan filter dokter
- Detail dokter + pilihan jadwal
- Riwayat kesehatan
- Pengingat obat
- Tambah pengingat
- Profile & Settings
- Light/Dark mode
- Toast feedback

## 📁 Struktur
```text
Sehatin/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── design/
    │   └── design_tokens.json
    └── *.svg
```

## 🚀 Menjalankan secara lokal
Cara paling mudah: buka `index.html` di browser.

Untuk hasil yang lebih mirip deployment web, jalankan local server:
```bash
python -m http.server 8000
```
Lalu buka `http://localhost:8000`.

## 🌐 Deploy dengan GitHub Pages
1. Buat repository baru di GitHub, misalnya `Sehatin`.
2. Upload seluruh isi folder project ini.
3. Pastikan `index.html` berada di root repository.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`.
7. Simpan dan tunggu proses deployment.
8. GitHub akan memberikan URL Pages untuk prototype.

## 🎨 File desain
Folder `assets/` berisi screen SVG yang bisa diimpor ke Figma dan diedit sebagai vector.

> Catatan: project ini adalah prototype web interaktif, bukan APK native dan bukan file `.fig` native Figma.
