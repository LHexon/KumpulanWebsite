# PlasticBank Indonesia — Repaired GitHub Pages

Versi ini sudah diperbaiki agar `index.html` tetap tampil meskipun folder assets tidak terbaca: CSS dan JavaScript utama sudah di-embed langsung ke `index.html`.

## Upload ke GitHub
1. Extract ZIP.
2. Upload **isi** folder ini ke ROOT repository GitHub, sehingga `index.html` berada langsung di root.
3. GitHub → Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, Folder: `/ (root)`.
6. Save dan tunggu beberapa menit.
7. Buka URL GitHub Pages: `https://USERNAME.github.io/NAMA-REPOSITORY/`.

**Catatan:** Jika kamu klik `index.html` di GitHub dan yang muncul kode HTML, itu normal. GitHub sedang menampilkan source code. Yang harus dibuka adalah URL GitHub Pages.

## Fitur
Splash screen, Home, Dashboard, chart, peta Indonesia, indeks risiko, direktori bank sampah, filter/search, laporan, riwayat lokal, leaderboard, profil, dan responsive mobile/desktop.

## Data/laporan
Ini adalah frontend demo. Riwayat laporan memakai `localStorage`, jadi belum menjadi database bersama. Untuk laporan live antar-user, tambahkan backend/database seperti Supabase/Firebase/server sendiri.
