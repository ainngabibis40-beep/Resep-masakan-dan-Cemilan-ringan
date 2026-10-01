# 🍳 ResepKreatif - Ide Masakan & Cemilan Praktis

Aplikasi web interaktif pencari ide masakan harian dan cemilan praktis dengan filter bahan kulkas, timer dapur bawaan, serta generator resep acak. Dibuat dengan **HTML5**, **Tailwind CSS**, dan **Vanilla JavaScript**.

---

## 🌟 Fitur Utama

- 🎲 **Generator Resep Acak ("Lagi Bingung Mau Masak Apa?")**: Menampilkan ide resep secara acak hanya dengan 1 klik.
- 🧊 **Filter Bahan Kulkas ("Punya Bahan Apa di Kulkas?")**: Pilih stok bahan yang tersedia di dapurmu, dan aplikasi akan menampilkan resep yang bisa langsung kamu masak.
- 🔍 **Pencarian & Kategori**: Cari berdasarkan nama makanan/bahan dan filter kategori (*Cemilan Manis, Cemilan Gurih, Masakan Praktis, Minuman Segar*).
- 💖 **Favorit / Bookmark**: Simpan resep favorit menggunakan `localStorage` agar tidak hilang saat browser ditutup.
- ⏱️ **Timer Dapur Interaktif**: Fitur stopwatch / timer bawaan lengkap dengan alarm suara (*Web Audio API*) saat timer selesai.
- 📋 **Modal Detail Resep**: Checklist bahan interaktif dan langkah-langkah memasak yang terstruktur.
- 🌙 **Dark Mode & Responsive**: Tampilan modern dengan Tailwind CSS, dukungan Dark Mode, dan nyaman diakses dari smartphone maupun PC.

---

## 📁 Struktur Repositori

```
resep-kreatif/
├── index.html       # Kode utama aplikasi web (HTML + CSS Tailwind + JS)
└── README.md        # Dokumentasi dan panduan proyek
```

---

## 🚀 Cara Menjalankan secara Lokal

1. Clone atau download repositori ini:
   ```bash
   git clone https://github.com/username/resep-kreatif.git
   ```
2. Buka folder proyek dan jalankan file `index.html` langsung di browser favoritmu (Google Chrome, Firefox, Edge, Safari).

---

## 🌐 Cara Deploy ke GitHub Pages

1. Buat repositori baru di GitHub dengan nama `resep-kreatif`.
2. Push file `index.html` dan `README.md` ke repositori tersebut:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - ResepKreatif"
   git branch -M main
   git remote add origin https://github.com/username/resep-kreatif.git
   git push -u origin main
   ```
3. Buka repositori di GitHub -> Klik tab **Settings**.
4. Pilih menu **Pages** di sidebar sebelah kiri.
5. Pada bagian **Build and deployment / Source**, pilih `Deploy from a branch`.
6. Pada bagian **Branch**, pilih `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
7. Tunggu 1-2 menit, lalu web kamu siap diakses melalui link:  
   `https://<username_github>.github.io/resep-kreatif/`

---

## 📄 Lisensi

Proyek ini bebas digunakan dan dimodifikasi di bawah lisensi [MIT License](LICENSE). Selamat memasak dan berkreasi! 🍳✨
