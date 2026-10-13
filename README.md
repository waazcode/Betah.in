# Betah.in — Pencarian dan Perbandingan Kos Mahasiswa

**Betah.in** adalah aplikasi web yang membantu mahasiswa mencari dan membandingkan kos di sekitar kampus, khususnya di wilayah Banda Aceh. Pengguna dapat mencari kos berdasarkan harga, jarak, tipe, dan fasilitas, lalu memilih kos yang paling sesuai dengan kebutuhan.

Proyek ini dibuat untuk memenuhi tugas UTS Praktikum Pemrograman Berorientasi Objek Lanjut (POPL) A menggunakan React, Vite, dan Docker.

---

## 👥 Anggota Kelompok 5
* **Fawwaz Ziyadi Ilmi** — (2408107010021)
* **Muhammad Razi Siregar** — (2408107010101)
* **Muhammad Sulthan Shadiq** — (2408107010104)

---

## 🚀 Fitur Utama

* **Pencarian Kos:** Mencari kos berdasarkan nama, alamat, atau kampus.
* **Filter dan Sortir:** Menyaring kos berdasarkan harga, jarak, tipe, dan fasilitas.
* **Detail Kos:** Melihat informasi harga, lokasi, fasilitas, dan foto kos.
* **Bandingin Kos:** Membandingkan 2–3 kos untuk mengetahui perbedaan harga, jarak, dan fasilitas.
* **Favorit:** Menyimpan kos pilihan agar mudah ditemukan kembali.
* **WhatsApp:** Menghubungi pemilik kos secara langsung melalui WhatsApp.

---

## 🛠️ Teknologi yang Digunakan

* **Front-end:** React 19, Vite, React Router
* **State Management:** Context API dan Custom Hooks
* **Storage:** LocalStorage
* **Styling:** Vanilla CSS
* **Containerization:** Docker dan Nginx
* **Version Control:** Git dan GitHub

---

## ⚙️ Cara Kerja Aplikasi

1. Data kos disimpan dalam file `src/data/kos.json` dan dibaca langsung oleh aplikasi.
2. Ketika pengguna mencari atau mengatur filter, React menampilkan data yang sesuai tanpa perlu memuat ulang halaman.
3. Daftar favorit disimpan di `LocalStorage` browser, sedangkan fitur perbandingan mengolah data kos yang dipilih pengguna.
4. Untuk menghubungi pemilik, pengguna diarahkan ke WhatsApp melalui tautan yang sudah disiapkan.

> **Catatan:** Pada versi ini, aplikasi berfokus pada *front-end* dan belum menggunakan *backend* atau *database server*.
