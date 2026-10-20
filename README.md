# SIM-Barang

Sistem Pengelolaan Inventaris Barang Jurusan, dikerjakan sebagai tugas Praktikum Pemrograman Web.

- **Nama**: [Nama Lengkap]
- **NIM**: [NIM]
- **Program Studi**: D3 Manajemen Informatika, Politeknik Negeri Sriwijaya
- **Dosen Pengampu**: Agus Setiawan, M.Kom.

## Gambaran Proyek

SIM-Barang adalah aplikasi web untuk mencatat, mengelola, dan memantau sarana dan prasarana (aset/barang) laboratorium dan jurusan. Proyek dikembangkan bertahap dari Pertemuan 1 sampai 7, dan setiap pertemuan menambahkan satu lapisan teknologi baru.

Fitur yang direncanakan:
- Tabel inventaris barang (kode, nama, kategori, jumlah, kondisi)
- Formulir input barang dengan validasi
- Login dan pembatasan akses halaman
- Penyimpanan data ke basis data MySQL

## Konsep HTTP Request dan Response

HTTP (HyperText Transfer Protocol) adalah protokol komunikasi antara **client** (browser) dan **server** (web server).

### Alur Kerja
1. Pengguna mengetik URL atau mengklik tautan di browser.
2. Browser mengirim **HTTP Request** ke server.
3. Server memproses permintaan (misalnya menjalankan skrip PHP atau membaca basis data).
4. Server mengirim **HTTP Response** berisi status dan konten (HTML, CSS, JS, atau data).
5. Browser menampilkan hasilnya kepada pengguna.

### HTTP Request
Berisi:
- **Method**: jenis permintaan
- **URL/path**: sumber daya yang diminta
- **Header**: informasi tambahan (misalnya jenis browser)
- **Body**: data yang dikirim (umumnya pada POST)

Method yang umum:
| Method | Fungsi | Contoh dalam SIM-Barang |
|--------|--------|--------------------------|
| GET | Meminta/mengambil data | Membuka halaman daftar barang |
| POST | Mengirim data ke server | Mengirim formulir tambah barang |

### HTTP Response
Berisi:
- **Status code**: hasil pemrosesan
-