# Meilinguo Audio — situs GitHub Pages (siap upload)

Situs audio untuk produk **"HSK 1 dari Nol — 30 Hari, 300 Kata"**.
Isi: halaman utama + 30 halaman hari (10 kata/hari) + 300 MP3 Xiaoxiao (tiap kata dibaca 2x).

> ⚠️ Folder ini BELUM di-upload ke GitHub. Ikuti langkah di bawah — tidak perlu
> install apa-apa, cukup akun GitHub gratis.

## Cara upload (sekali saja, ~10 menit)

1. **Buat akun GitHub gratis** (kalau belum punya) di https://github.com/signup
   — cukup email + password, tidak perlu kartu kredit.
2. **Buat repo baru:** klik `+` (kanan atas) → **New repository**
   - Repository name: `meilinguo-audio` (persis seperti ini, huruf kecil, pakai strip)
   - Pilih **Public**
   - Klik **Create repository**. Jangan centang "Add a README" (folder ini sudah punya).
3. **Upload isi folder ini ke repo:**
   - Di halaman repo yang baru dibuat, klik **"uploading an existing file"**
   - Seret (drag) SEMUA isi folder `meilinguo-audio-site` ke halaman upload:
     `index.html`, `style.css`, `hari-01.html` … `hari-30.html`, dan folder `audio/`
     (300 MP3 di dalamnya). Semua harus di **root repo**, bukan di dalam subfolder.
   - Klik **Commit changes**.
4. **Nyalakan GitHub Pages:** di repo, klik **Settings** → (menu kiri) **Pages**
   - "Build and deployment" → Source: **Deploy from a branch**
   - Branch: **main**, folder: **/(root)** → **Save**.
   - Tunggu 1–2 menit. Situsmu aktif di `https://<USERNAME>.github.io/meilinguo-audio/`
     (`<USERNAME>` = username GitHub kamu).
5. **Cek:** buka `https://<USERNAME>.github.io/meilinguo-audio/hari-01.html`
   — harus muncul 10 kata Hari 1 dengan tombol play. Kalau ada kata yang tidak
   bersuara, cek file MP3-nya ada di folder `audio/` di repo.

## URL untuk QR & link di PDF

Ganti `<USERNAME>` dengan username GitHub kamu. Inilah URL yang dipakai di PDF:
QR-nya mengarah ke URL ini, dan di PDF juga ditulis sebagai **link yang bisa diklik**
(teks biru, bukan QR saja).

- Halaman utama: https://<USERNAME>.github.io/meilinguo-audio/
- Hari 01: https://<USERNAME>.github.io/meilinguo-audio/hari-01.html
- Hari 02: https://<USERNAME>.github.io/meilinguo-audio/hari-02.html
- Hari 03: https://<USERNAME>.github.io/meilinguo-audio/hari-03.html
- Hari 04: https://<USERNAME>.github.io/meilinguo-audio/hari-04.html
- Hari 05: https://<USERNAME>.github.io/meilinguo-audio/hari-05.html
- Hari 06: https://<USERNAME>.github.io/meilinguo-audio/hari-06.html
- Hari 07: https://<USERNAME>.github.io/meilinguo-audio/hari-07.html
- Hari 08: https://<USERNAME>.github.io/meilinguo-audio/hari-08.html
- Hari 09: https://<USERNAME>.github.io/meilinguo-audio/hari-09.html
- Hari 10: https://<USERNAME>.github.io/meilinguo-audio/hari-10.html
- Hari 11: https://<USERNAME>.github.io/meilinguo-audio/hari-11.html
- Hari 12: https://<USERNAME>.github.io/meilinguo-audio/hari-12.html
- Hari 13: https://<USERNAME>.github.io/meilinguo-audio/hari-13.html
- Hari 14: https://<USERNAME>.github.io/meilinguo-audio/hari-14.html
- Hari 15: https://<USERNAME>.github.io/meilinguo-audio/hari-15.html
- Hari 16: https://<USERNAME>.github.io/meilinguo-audio/hari-16.html
- Hari 17: https://<USERNAME>.github.io/meilinguo-audio/hari-17.html
- Hari 18: https://<USERNAME>.github.io/meilinguo-audio/hari-18.html
- Hari 19: https://<USERNAME>.github.io/meilinguo-audio/hari-19.html
- Hari 20: https://<USERNAME>.github.io/meilinguo-audio/hari-20.html
- Hari 21: https://<USERNAME>.github.io/meilinguo-audio/hari-21.html
- Hari 22: https://<USERNAME>.github.io/meilinguo-audio/hari-22.html
- Hari 23: https://<USERNAME>.github.io/meilinguo-audio/hari-23.html
- Hari 24: https://<USERNAME>.github.io/meilinguo-audio/hari-24.html
- Hari 25: https://<USERNAME>.github.io/meilinguo-audio/hari-25.html
- Hari 26: https://<USERNAME>.github.io/meilinguo-audio/hari-26.html
- Hari 27: https://<USERNAME>.github.io/meilinguo-audio/hari-27.html
- Hari 28: https://<USERNAME>.github.io/meilinguo-audio/hari-28.html
- Hari 29: https://<USERNAME>.github.io/meilinguo-audio/hari-29.html
- Hari 30: https://<USERNAME>.github.io/meilinguo-audio/hari-30.html

## Catatan

- Audio dialog (20 dialog) & mock test BELUM ada — halaman utama sudah menulis
  "Segera", dan halaman itu akan ditambahkan begitu audionya selesai dibuat.
- Kalau nanti ada kata yang diganti/di-rekam ulang, cukup upload ulang file MP3
  yang bersangkutan ke folder `audio/` di repo (nama file harus sama).
- Situs ini statis (HTML + MP3 saja), tidak ada server/database — jadi tidak ada
  biaya bulanan. GitHub Pages gratis untuk repo public.
