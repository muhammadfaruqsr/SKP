# SKP Harian — paket PWA (mode mandiri)

Aplikasi tampil langsung dari hosting ini (bukan di dalam bingkai Apps Script), lalu mengambil data lewat
permintaan anonim ke URL web app Apps Script. Karena itu bisa dibuka dengan akun Google apa pun
(atau tanpa login) dan datanya tetap di Drive akun pemilik.

1. Buka `index.html`, cari `PASTE_URL_EXEC_DI_SINI` (hanya ada satu), ganti dengan URL web app Anda (berakhiran `/exec`).
2. Upload SEMUA file di folder ini ke repositori GitHub (Add file → Create new file untuk .webmanifest dan sw.js bila upload gagal).
3. Settings → Pages → Deploy from a branch → main / root.
4. Buka alamat GitHub Pages di Chrome HP → ⋮ → Instal aplikasi.

Syarat di Apps Script: deployment "Jalankan sebagai: Saya" dan "Yang memiliki akses: Siapa saja",
kode `Code.gs` terbaru (ada fungsi `doPost`), lalu Deploy → Versi baru.
