<div align="center">

# 🔍 Portofolio QA: Pengujian Website Blibli

</div>

---

## 📌 Informasi Proyek

| | |
|---|---|
| **Project** | Website Testing ([Blibli.com](https://www.blibli.com)) |
| **Type** | Manual Testing |
| **Tools Used** | Google Sheets (Test Case & Bug Report) |
| **Role** | QA Tester |
| **Objective** | Menguji fitur utama pada website Blibli untuk memastikan fungsionalitas dan user experience berjalan sesuai harapan |

---

## ✏️ Test Scope

**Fitur yang diuji:**

### a. Authentication Testing
- [Register](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing)
- [Login](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing)

### b. Product & Cart Functionality Testing
- [Search & Filter Product](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing) (kata kunci valid/non-valid, filter harga, brand, kategori, promo)
- [Cart Management](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing) (menambah, mengubah, dan menghapus produk dari bag)

---

## 📁 Test Case Documentation

### Authentication Testing

📋 [Lihat Google Sheets - Register & Login](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing)

### Product & Cart Functionality Testing

📋 [Lihat Google Sheets - Search dan Cart](https://docs.google.com/spreadsheets/d/1mz6TcdwzEp4YVAO60MLuKj-uwn109OtiBq3d6_gRcyc/edit?usp=sharing)

---

## � Bug Reports

**Daftar Bug yang Ditemukan:**

### 1. Email sudah terdaftar tidak menampilkan pesan error

- **Severity:** `Medium` 🟠
- **Deskripsi:** Saat pengguna memasukkan email yang sudah pernah digunakan, sistem langsung mengarahkan ke halaman login tanpa memberikan pesan bahwa email tersebut sudah terdaftar.
- **Dampak:** Membingungkan pengguna yang tidak tahu bahwa emailnya sudah terdaftar.

### 2. Pesan error tidak sesuai untuk format email tidak valid

- **Severity:** `Minor` 🟡
- **Deskripsi:** Saat pengguna memasukkan email tidak valid (contoh: `coba#gmail.com`), sistem menampilkan pesan *"Mohon masukkan nomor HP yang valid"* alih-alih *"Mohon masukkan alamat email yang valid"*.
- **Dampak:** Tidak mengganggu fungsi utama, tapi menurunkan kejelasan pesan error bagi pengguna.

---

## � Summary

Ditemukan **dua bug** pada fitur registrasi dengan tingkat keparahan berbeda:

- **Medium**, karena meskipun sistem masih berfungsi, alur login tanpa pesan yang jelas bisa membuat pengguna bingung.

- **Minor**, karena fungsi utama berjalan baik, tetapi pesan error tidak sesuai konteks sehingga mengganggu kejelasan UX.

> **Secara keseluruhan**, pengujian menunjukkan bahwa proses registrasi dan login berfungsi dengan baik secara teknis, namun masih memerlukan perbaikan pada validasi pesan error dan kejelasan feedback kepada pengguna.
