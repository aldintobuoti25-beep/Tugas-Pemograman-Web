# Konsep Website UMKM - Kopi Lokal Nusantara

Repositori ini berisi rancangan dan kode sumber sederhana untuk landing page website UMKM yang bergerak di bidang penjualan biji kopi lokal.

---

## 📐 1. Arsitektur Web (Struktur & Flow)

Berikut adalah struktur alur navigasi dari website UMKM ini:

```text
               +-----------------------+
               |      Landing Page     |
               +-----------+-----------+
                           |
       +-------------------+-------------------+
       |                   |                   |
+------v-------+    +------v-------+    +------v-------+
| Katalog      |    | Tentang Kami |    | Informasi    |
| Produk       |    | (Story UMKM) |    | Kontak       |
+------+-------+    +--------------+    +------+-------+
       |                                       |
       +-------------------+-------------------+
                           |
                 +---------v---------+
                 | Tombol Pesan via  |
                 | WhatsApp          |
                 +-------------------+
```

---

## 👤 2. User Story

Aktivitas dan alur interaksi pengguna saat menjelajahi website:

1. **Membuka Halaman Utama (Landing Page):**
   * Pengguna masuk ke website dan langsung disambut oleh visual *Hero Banner* beserta tombol *Call to Action* (CTA) **"Lihat Katalog Menu"**.
2. **Mengeksplorasi Katalog Produk:**
   * Pengguna menggeser ke bawah (*scroll*) untuk melihat daftar produk kopi, lengkap dengan foto, deskripsi profil rasa (*flavor notes*), dan harga.
3. **Mengenal Brand / Usaha:**
   * Pengguna membaca seksi **"Tentang Kami"** untuk mengetahui asal-usul biji kopi dan nilai yang diusung oleh UMKM.
4. **Melakukan Pemesanan:**
   * Pengguna mengklik tombol **"Pesan via WA"** pada produk yang diinginkan.
   * Pengguna otomatis dialihkan ke aplikasi/aplikasi web WhatsApp dengan pesan awal yang sudah terisi secara otomatis sesuai nama produk.

---

## 💻 3. Cara Menggunakan File Ini

1. **Unduh/Clone Repositori:**
   ```bash
   git clone https://github.com/username-anda/nama-repo.git
   ```
2. **Jalankan Website:**
   * Buka file `index.html` menggunakan browser favorit Anda (Chrome, Firefox, Edge, dll.).
3. **Publikasi ke GitHub Pages:**
   * Masuk ke menu **Settings** pada repositori GitHub Anda.
   * Pilih menu **Pages** di panel kiri.
   * Pada bagian **Branch**, pilih `main` dan simpan (*Save*).
   * Website UMKM Anda dapat diakses langsung secara online.