# 🍯 HoneyBakes!

> *Baked at dawn, sweetened with honey*

Website toko roti **HoneyBakes!** yang dibuat untuk memenuhi tugas **Ujian Tengah Semester (UTS) mata kuliah Pemrograman Web — Kelas C**. Tampilannya dirancang seperti buku menu yang dibuka dua halaman: halaman kiri dan kanan berisi kategori menu, lalu di bagian akhir ada halaman pemesanan dan ulasan.

---

| Keterangan    | Data                     |
| ------------- | ------------------------ |
| Nama          | `Nabila Indaswari` |
| NIM           | `D1041241021` |
| Kelas         | C                        |
| Mata Kuliah   | Pemrograman Web          |
| Dosen Pengampu| `Fauzan Asrin, S.Kom, M.Kom` |

---

## 📖 Daftar Halaman

| File                    | Isi                                                        |
| ----------------------- | ---------------------------------------------------------- |
| `index.html`            | Halaman sampul + daftar menu (navigasi ke tiap kategori)   |
| `BreadsnLoaves.html`    | Breads & Loaves · Croissants & Pastries                    |
| `CakesnSlices.html`     | Cakes & Slices · Cupcakes & Muffins                        |
| `CookiesnBiscuits.html` | Cookies & Biscuits · Doughnuts                             |
| `TartsnPies.html`       | Tarts & Pies · Promos                                      |
| `OrdernReviews.html`    | Form pemesanan · Form ulasan & saran                       |
| `styles.css`            | Seluruh styling website                                    |
| `styleguide.txt`        | Catatan palet warna dan ikon yang dipakai                  |

---

## ✨ Fitur

- **Layout ala buku menu** — setiap halaman terbagi dua kolom (kiri–kanan) seperti buku yang dibuka, lengkap dengan tombol panah untuk berpindah halaman.
- **Navigasi menu** — daftar kategori di halaman utama langsung menuju halaman kategori terkait, plus tombol **Order Now**.
- **Form pemesanan** (`OrdernReviews.html`)
  - Data pemesan dengan validasi (nomor WhatsApp harus diawali `08`, 10–13 digit).
  - Pilihan menu per kategori memakai `<details>`/`<summary>` agar ringkas.
  - **Subtotal dihitung otomatis** dengan JavaScript setiap kali jumlah item diubah.
  - Pilihan *Pickup* atau *Delivery* — kolom alamat hanya muncul (dan wajib diisi) saat memilih *Delivery*.
  - Tanggal pengambilan tidak bisa diisi dengan tanggal yang sudah lewat.
  - Tambahan (gift box, kartu ucapan, lilin), metode pembayaran, dan catatan.
- **Form ulasan & saran**
  - Rating bintang 1–5 berbasis radio button + CSS.
  - Pilihan menu favorit, aspek yang disukai (checkbox), dan slider tingkat rekomendasi.
  - Opsi kirim ulasan secara anonim.

---

## 🎨 Desain

**Palet warna**

| Nama          | Kode      |
| ------------- | --------- |
| Green         | `#d1ddb9` |
| Green Dark 1  | `#91a464` |
| Green Dark 2  | `#3e4323` |
| Pink          | `#f6e2e3` |
| Pink Dark 1   | `#ecb4bd` |
| Pink Dark 2   | `#c38690` |
| Brown (line)  | `#7a706f` |

**Font** (Google Fonts): *Flavors*, *Mystery Quest*, *Spicy Rice*, *Emilys Candy*, *Love Ya Like A Sister*.

**Ikon** dari [Icons8](https://icons8.com), gambar produk dari Pinterest.

---

## 🛠️ Teknologi

- **HTML5** — struktur halaman dan form (validasi bawaan: `required`, `pattern`, `min`/`max`, dll.)
- **CSS3** — styling, layout, dan komponen rating bintang
- **JavaScript (vanilla)** — hitung subtotal, tampilkan/sembunyikan kolom alamat, dan pesan konfirmasi form

Tidak memakai framework atau library tambahan.

---

## 🚀 Cara Menjalankan

1. Clone atau download folder project ini.
2. Buka `index.html` langsung di browser (Chrome, Firefox, Edge, dsb.).
3. Pastikan terhubung ke internet agar font dan gambar dari sumber eksternal bisa dimuat.

> Form pemesanan dan ulasan hanya berjalan di sisi browser (tidak ada backend), jadi data tidak benar-benar dikirim ke mana pun.

---

<p align="center">Dibuat dengan 🍞 dan 🍯 untuk UTS Pemrograman Web — Kelas C</p>
