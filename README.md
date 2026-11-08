# 📚 Toko Buku Ceria (Ruang Baca)

Platform web interaktif untuk pengelolaan katalog buku ajar, pemesanan, dan pelacakan pengiriman paket secara terpusat[cite: 1, 3, 4, 5].

---

## 🚀 Fitur Utama
- **Autentikasi & Dashboard**: Sistem login (*User/Admin*) dan dashboard interaktif yang menampilkan ringkasan data statistik sistem[cite: 1, 2, 6, 9].
- **Katalog & Stok Buku**: Menampilkan daftar lengkap buku ajar, fitur pencarian instan (*live search*), serta penambahan data buku baru secara dinamis menggunakan JavaScript DOM[cite: 3, 7].
- **Pemesanan (Checkout)**: Formulir pemesanan buku dengan pilihan kuantitas dan metode pembayaran fleksibel (*Transfer Bank*, *Virtual Account*, *COD*)[cite: 5].
- **Lacak Pengiriman**: Fitur pelacakan status pesanan berdasarkan nomor *Delivery Order* (DO) lengkap dengan *timeline* perjalanan paket[cite: 4].

---

## 🛠️ Teknologi
* **HTML5** & **CSS3** (Desain responsif & kustom properti)
* **JavaScript (Vanilla JS)** (Manipulasi DOM, pencarian, & manajemen data sesi)

---

## 📂 Struktur Folder
```text
📦 toko-buku-ceria
 ┣ 📂 assets/        # Aset gambar & logo
 ┣ 📂 css/           # Lembar gaya (style.css)
 ┣ 📂 js/            # Berkas logika & data (script.js, data.js)
 ┣ 📜 index.html     # Halaman Login
 ┣ 📜 dashboard.html # Halaman Dashboard
 ┣ 📜 stok.html      # Halaman Katalog & Stok
 ┣ 📜 checkout.html  # Halaman Pemesanan
 ┗ 📜 tracking.html  # Halaman Lacak Pengiriman
