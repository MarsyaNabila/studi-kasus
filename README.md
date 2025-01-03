# studi-kasus
Nama: Marsya Nabila Putri

Kelas: TI.24.A.4

NIM: 312410338

Matakuliah: Bahasa Pemrograman

# Validasi Input Pendaftaran Online
Program ini dibuat untuk memvalidasi data input pada proses pendaftaran online. Validasi dilakukan pada tiga jenis data: nama lengkap, nomor telepon, dan email. Program ini memberikan pesan kesalahan yang spesifik jika ada input yang tidak valid dan menyatakan bahwa data pendaftaran valid jika semua input benar.

# Cara kerja Program
1. Validasi Nama

![Screenshot 2025-01-03 071254](https://github.com/user-attachments/assets/308db696-06c6-47a0-a0ef-9bd2fc2f38a0)

Penjelasan:

- Fungsi isalpha() memastikan bahwa name hanya terdiri dari huruf.
- Jika nama berisi angka, spasi, atau karakter khusus, validasi akan gagal, dan pesan error ditambahkan ke daftar errors.

2. Validasi Nomor Telepon

![Screenshot 2025-01-03 071247](https://github.com/user-attachments/assets/ab65e6d4-5764-455a-8ad9-b6e64e289fa0)

Penjelasan:

- Fungsi isdigit() memastikan bahwa phone hanya terdiri dari angka.
- Jika phone berisi huruf, spasi, atau karakter lain, validasi akan gagal.

3. Validasi Email

![Screenshot 2025-01-03 071130](https://github.com/user-attachments/assets/f9997098-ccf2-4b7a-a7b2-63da0e0ed6cf)

Penjelasan:

- Ekspresi reguler ^\S+@\S+\.\S+$ memastikan bahwa:
  - Ada karakter sebelum @ (\S+ berarti non-spasi).
  - Ada karakter sebelum dan sesudah ..
  - Tidak ada spasi di seluruh string email.
- Jika format email tidak sesuai, validasi akan gagal.

4. Hasil Validasi

   ![Screenshot 2025-01-03 070844](https://github.com/user-attachments/assets/3796f850-25b0-4dc8-930c-a5fd4ba1e2ab)

Penjelasan:

- Jika ada elemen dalam daftar errors, setiap pesan kesalahan akan ditampilkan.
- Jika tidak ada kesalahan, program akan menampilkan "Data pendaftaran valid."

# Persyaratan

- Python 3.x
- Library re (sudah termasuk dalam Python standar)

# Cara Menjalankan Program
1. Clone repositori ini atau salin file program ke komputer Anda.
2. Buka terminal atau command prompt.
3. Jalankan program menggunakan perintah: bash python nama_file.py
4. Masukkan data sesuai dengan permintaan program:
    - Nama lengkap
    - Nomor telepon
    - Email
5. Program akan menampilkan hasil validasi:
    - Pesan "Data pendaftaran valid" jika semua input benar.
    - Pesan kesalahan untuk setiap data yang tidak valid.

# Input dan Output
# Input
![code](https://github.com/user-attachments/assets/904a42dc-1dd3-4642-8da9-fc4cd30c2a2f)

# Output Valid
![Screenshot 2025-01-03 065925](https://github.com/user-attachments/assets/76cdc677-7863-4691-9634-f660cecffdfe)

Masukan nama lengkap: marsya Masukkan nomor telepon: 0895 Masukkan email: marsyanabila293@gmail.com Data pendaftaran valid.

# Input Tidak Valid
![Screenshot 2025-01-03 070337](https://github.com/user-attachments/assets/a1ce553e-8826-4721-bdcf-eba06a87185a)

Masukkan nama lengkap: marsya Masukkan nomor telepon: 0895 Masukkan email: marsyanabila293.com Nama lengkap harus hanya berisi huruf. Nomor telepon harus hanya berisi angka. Email harus mengandung karakter @ dan . serta sesuai format yang benar.

# Fitur dan Kemampuan: 
- Kesesuaian dengan berbagai pengguna
- Dapat Dimodifikasi
- Keamanan dasar input
- Laporan kesalahan yang spesifik
  

















