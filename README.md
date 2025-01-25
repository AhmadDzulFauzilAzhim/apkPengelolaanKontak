# Aplikasi Pengelolaan Kontak
 
Aplikasi Pengelolaan Kontak adalah aplikasi berbasis GUI yang memungkinkan pengguna untuk mengelola informasi kontak. Pengguna dapat menambahkan, mengedit, menghapus, dan mencari kontak, serta mengekspor dan mengimpor data kontak dalam format CSV. Aplikasi ini menggunakan database untuk menyimpan data kontak dan memberikan antarmuka yang intuitif untuk interaksi pengguna.

---

## Komponen GUI
Aplikasi ini terdiri dari beberapa komponen GUI yang memudahkan pengguna dalam mengelola kontak:

### Input Fields:
- **JLabel:**
  - **Nama:** Label untuk memasukkan nama kontak.
  - **No. HP:** Label untuk memasukkan nomor telepon kontak.
  - **Alamat:** Label untuk memasukkan alamat kontak.
  - **Gender:** Label untuk memilih jenis kelamin (Laki-Laki/Perempuan).
  - **Kategori:** Label untuk memilih kategori kontak (Keluarga, Teman, Kerja).
  - **CARI:** Label untuk mencari kontak.
- **JTextField:**
  - `nameInput`: Untuk memasukkan nama kontak.
  - `handphoneInput`: Untuk memasukkan nomor telepon kontak.
  - `alamatInput`: Untuk memasukkan alamat kontak.
  - `cariInput`: Untuk memasukkan nama atau nomor telepon yang ingin dicari.

---

### ComboBox:
- **Dropdown:**
  - `genderPilih`: Dropdown untuk memilih jenis kelamin (Laki-Laki/Perempuan).
  - `kategoriPilih`: Dropdown untuk memilih kategori kontak (Keluarga, Teman, Kerja).

---

### Tombol Aksi:
- **JButton:**
  - **TAMBAH:** Untuk menambahkan kontak baru.
  - **EDIT:** Untuk mengedit kontak yang dipilih.
  - **SIMPAN:** Untuk menyimpan perubahan yang dilakukan pada kontak.
  - **HAPUS:** Untuk menghapus kontak yang dipilih.
  - **EKSPOR:** Untuk mengekspor data kontak ke file CSV.
  - **IMPOR:** Untuk mengimpor data kontak dari file CSV.
  - **CARI:** Untuk mencari kontak berdasarkan nama atau nomor telepon.
  - **KELUAR:** Untuk menutup aplikasi.

---

### Tabel Kontak:
- **JTable:**
  - `tblKontak`: Menampilkan daftar kontak yang telah disimpan dalam database dengan kolom untuk Nama, No. HP, Alamat, Gender, dan Kategori.

---

### Daftar Kontak:
- **JList:**
  - `kontakList`: Menampilkan nama-nama kontak yang dapat dipilih untuk melakukan aksi edit atau hapus.

---

## Cara Menjalankan Aplikasi

### Prasyarat:
1. Pastikan Anda memiliki **Java Development Kit (JDK)** terinstal di sistem Anda.
2. Pastikan Anda memiliki database (seperti MySQL) yang sudah dikonfigurasi dengan tabel kontak.

### Koneksi Database:
- Sesuaikan kredensial koneksi database di dalam metode `connect()` pada kelas `PengelolaanKontakHelper`.

### Kompilasi dan Jalankan:
1. Buka terminal atau command prompt.
2. Navigasi ke direktori tempat file Java disimpan.
3. Kompilasi aplikasi dengan perintah:
   ```bash
   javac AplikasiPengelolaanKontak.java

---

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo

