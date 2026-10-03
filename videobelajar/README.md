# videobelajar

Website tugas MVP dengan 3 halaman responsif: Beranda, Login, Register.

## Cara menjalankan
Buka `dist/index.html` di browser, atau jalankan `python -m http.server 8000 --directory dist` lalu buka http://localhost:8000. Tidak membutuhkan instalasi paket.

## File
- dist/index.html: Beranda
- dist/login.html: Login
- dist/register.html: Register
- dist/style.css: styling dan media queries
- dist/app.js: filter kategori, dialog course, navigasi demo, validasi formulir dan tampilkan kata sandi
- dist/assets/: foto yang diekstrak dari referensi tugas yang diberikan

## Batasan demo
Login dan register hanya validasi input serta navigasi; tidak ada autentikasi, penyimpanan kata sandi, backend, pengiriman email, atau integrasi Google. Form newsletter menampilkan konfirmasi demo dan tidak menyimpan data. Tombol Google menjelaskan bahwa integrasi belum diaktifkan. Metadata dan harga course adalah contoh.
