# studi-kasus
Nama: Marsya Nabila Putri

Kelas: TI.24.A.4

NIM: 312410338

Matakuliah: Bahasa Pemrograman

# Validasi Input Pendaftaran Online
Program ini dibuat untuk memvalidasi data input pada proses pendaftaran online. Validasi dilakukan pada tiga jenis data: nama lengkap, nomor telepon, dan email. Program ini memberikan pesan kesalahan yang spesifik jika ada input yang tidak valid dan menyatakan bahwa data pendaftaran valid jika semua input benar.

# Cara kerja Program
1. Validasi Nama

Penjelasan:

- Fungsi isalpha() memastikan bahwa name hanya terdiri dari huruf.
- Jika nama berisi angka, spasi, atau karakter khusus, validasi akan gagal, dan pesan error ditambahkan ke daftar errors.

2. Validasi Nomor Telepon

Penjelasan:

- Fungsi isdigit() memastikan bahwa phone hanya terdiri dari angka.
- Jika phone berisi huruf, spasi, atau karakter lain, validasi akan gagal.

3. Validasi Email

Penjelasan:

- Ekspresi reguler ^\S+@\S+\.\S+$ memastikan bahwa:
  - Ada karakter sebelum @ (\S+ berarti non-spasi).
  - Ada karakter sebelum dan sesudah ..
  - Tidak ada spasi di seluruh string email.
- Jika format email tidak sesuai, validasi akan gagal.

4. Hasil Validasi

Penjelasan:

- Jika ada elemen dalam daftar errors, setiap pesan kesalahan akan ditampilkan.
- Jika tidak ada kesalahan, program akan menampilkan "Data pendaftaran valid."











