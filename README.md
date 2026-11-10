# Bookstore Pandji — GitHub Pages (HTML)

Project ini adalah versi frontend statis HTML, CSS, dan JavaScript dari project PHP.

## Cara upload ke GitHub Pages
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini (bukan folder ZIP-nya).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Buka alamat GitHub Pages yang diberikan.

## Catatan penting
GitHub Pages hanya menjalankan file statis. PHP dan MySQL tidak bisa dijalankan di GitHub Pages. Karena itu, login, daftar, keranjang, checkout, dan pesan pada paket ini adalah simulasi frontend yang memakai `localStorage` di browser yang sama. Data tidak tersimpan ke server dan tidak dibagikan antar-pengunjung. Untuk login, transaksi, dan pesan admin sungguhan, diperlukan backend/hosting PHP atau layanan backend terpisah.

Desain menggunakan stylesheet project asli `assets/css/style.css` dan aset gambar dari project sumber.
