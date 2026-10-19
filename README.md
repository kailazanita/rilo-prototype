# RILO — Prototype Bank Sampah Terintegrasi

Prototype website front-end untuk demonstrasi konsep RILO. Dibuat dengan HTML, CSS, dan JavaScript murni; tidak memerlukan database, framework, atau proses build.

## Fitur demo
- Dashboard ringkasan poin, berat sampah, dan setoran
- Form input setoran sampah dengan estimasi poin
- Simulasi metode drop-off dan pickup
- Riwayat transaksi dan filter status
- Penukaran poin simulasi
- Ringkasan dampak dan material
- Konten edukasi, komunitas, dan profil
- Responsif untuk desktop dan mobile

## Menjalankan secara lokal
1. Ekstrak folder proyek.
2. Buka `index.html` di browser.

## Hosting gratis melalui GitHub Pages
1. Buat repository baru di GitHub, misalnya `rilo-prototype`.
2. Upload `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses publikasi selesai. URL website akan ditampilkan pada halaman Pages.

## Catatan penting
- Semua data transaksi berjalan di memori JavaScript dan tidak disimpan ke database atau server.
- Data yang dimasukkan bersifat sementara dan akan kembali ke data contoh saat halaman di-refresh.
- Poin per kilogram hanyalah angka simulasi untuk prototype. Ganti dengan ketentuan RILO yang sebenarnya sebelum digunakan untuk pilot.
- Peta, pembayaran, autentikasi, verifikasi berat, dan notifikasi belum terhubung ke layanan eksternal.
- Jangan masukkan data pribadi atau data sensitif ke prototype publik.
