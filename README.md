# tugas-uts-web1
# 📚 Toko Buku Ceria (Ruang Baca)

> Platform web interaktif untuk pengelolaan katalog buku ajar, pemesanan, pengecekan stok, serta pelacakan pengiriman paket secara terpusat dan efisien[cite: 1, 3, 4, 5].

---

## 🌟 Fitur Utama

1. **Sistem Autentikasi (Login & Dashboard)**[cite: 1, 2]
   - Halaman login yang intuitif dengan pilihan peran pengguna (*User* / *Admin*)[cite: 1, 6].
   - Dashboard personal yang menyambut pengguna dan menampilkan ringkasan data statistik sistem (seperti jumlah judul buku, total stok, dan pesanan aktif)[cite: 2, 9].
2. **Katalog & Informasi Stok Buku Ajar**[cite: 3]
   - Menampilkan daftar lengkap buku lengkap dengan informasi sampul, kode barang, nama, deskripsi, jenis, edisi, stok, dan harga[cite: 3, 7].
   - Fitur pencarian instan (*live search*) berdasarkan judul atau kode buku[cite: 3].
   - Fitur interaktif **Tambah Buku Baru** menggunakan DOM JavaScript (`prompt`) untuk memasukkan data stok baru secara dinamis[cite: 3, 7].
3. **Formulir Pemesanan & Pembayaran (Checkout)**[cite: 5]
   - Memungkinkan pengguna untuk memesan buku ajar dengan memilih kuantitas serta metode pembayaran yang fleksibel (*Transfer Bank*, *Virtual Account*, atau *Bayar di Tempat/COD*)[cite: 5].
4. **Lacakan Pengiriman Paket**[cite: 4]
   - Fitur pengecekan status pesanan/Delivery Order (DO) berdasarkan nomor ID pemesanan, lengkap dengan riwayat perjalanan paket (*tracking timeline*)[cite: 4].

---

## 🛠️ Teknologi yang Digunakan

* **HTML5** – Struktur halaman web dan formulir interaktif[cite: 1, 2, 3, 4, 5].
* **CSS3** – Desain antarmuka modern, kustom properti (`--primary`), serta *layout* responsif (`style.css`)[cite: 1, 2, 3, 4, 5].
* **JavaScript (Vanilla JS)** – Logika aplikasi, manipulasi DOM, manajemen data lokal/sesi (`localStorage`), dan fungsi dinamis seperti pencarian serta penambahan data katalog[cite: 3, 6, 7].

---

## 📂 Struktur Proyek

```text
📦 toko-buku-ceria
 ┣ 📂 assets/          # Aset gambar, logo, dan sampul buku
 ┣ 📂 css/             # Lembar gaya (style.css)
 ┣ 📂 js/              # Berkas logika JavaScript (script.js, data.js)
 ┣ 📜 index.html       # Halaman Utama / Login
 ┣ 📜 dashboard.html   # Halaman Dashboard Pengguna
 ┣ 📜 stok.html        # Halaman Katalog & Stok Buku
 ┣ 📜 checkout.html    # Halaman Formulir Pemesanan
 ┗ 📜 tracking.html    # Halaman Lacak Pengiriman Paket






<img width="1583" height="771" alt="hasil 2" src="https://github.com/user-attachments/assets/30308385-332e-412c-b08e-6a60412fcace" />
<img width="1600" height="775" alt="hasil 1" src="https://github.com/user-attachments/assets/84276a63-c55d-4cdd-8aab-153038aa8cf9" />
<img width="1088" height="761" alt="codingan 7" src="https://github.com/user-attachments/assets/543c59b3-92c7-4fab-9771-9b75ff72df2e" />
<img width="1070" height="761" alt="codingan 6" src="https://github.com/user-attachments/assets/d23acb34-aa16-4382-a5e2-7fadc84411ed" />
<img width="1088" height="772" alt="codingan 5" src="https://github.com/user-attachments/assets/ebc24e07-dfee-4c2e-a1e5-67e0b410dcc7" />
<img width="1083" height="767" alt="codingan 4" src="https://github.com/user-attachments/assets/02803d69-4af5-4126-9017-77b72b75138a" />
<img width="1089" height="771" alt="codingan 3" src="https://github.com/user-attachments/assets/60fcacd5-8b3e-4427-98c0-5b8912455582" />
<img width="1092" height="468" alt="codingan 2" src="https://github.com/user-attachments/assets/5b8c94bb-4570-4212-ac69-784f3de8c25c" />
<img width="1091" height="774" alt="codingan 1" src="https://github.com/user-attachments/assets/6e7d7b83-23f1-4b8a-afd8-5ce582106430" />
<img width="1600" height="775" alt="hasil 5" src="https://github.com/user-attachments/assets/ca0a9c9f-47fe-46d5-b796-82a800ed4779" />
<img width="1600" height="773" alt="hasil 4" src="https://github.com/user-attachments/assets/6e8c4985-224e-493a-8b30-be9c3f1ab716" />
<img width="1591" height="777" alt="hasil 3" src="https://github.com/user-attachments/assets/1df3a0d3-ab01-4d0f-83b8-f493deeb63ec" />

https://youtu.be/VUOIoynRvPA
