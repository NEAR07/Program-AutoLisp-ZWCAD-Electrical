# Deskripsi Program
Program ini adalah skrip AutoLISP yang dirancang untuk digunakan dalam ZWCAD, yang memungkinkan pengguna untuk menampilkan atribut dari blok yang ada di dalam gambar. Program ini memungkinkan pengguna untuk memilih objek berdasarkan dua metode: memilih objek secara manual atau memilih semua objek pada layer tertentu (dalam hal ini, layer "FDS"). Setelah memilih objek, pengguna diminta untuk memasukkan jarak vertikal untuk tiga atribut: ROOM_NAME, ROOM_CODE, dan SWBS. Program ini kemudian akan menempatkan teks di posisi yang ditentukan berdasarkan atribut yang diambil dari blok, dengan penyesuaian horizontal yang dapat diatur. Program ini sangat berguna untuk mempercepat proses dokumentasi dan anotasi dalam desain teknik.

# Tutorial Cara Menjalankan Program di ZWCAD
### 1. Persiapan Lingkungan:
- Pastikan memiliki ZWCAD terinstal di komputer.
- Pastikan memiliki blok dengan atribut yang sesuai (CIRCUIT, ROOM_NAME, ROOM_CODE, SWBS) di dalam gambar.

### 2. Menyimpan Skrip:
- Salin kode program di atas ([DBT](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-Electrical/blob/main/Pencetakan%20Atribut%20Blok%20Cadmatic%20di%20ZWCAD%20Berdasarkan%20Pilihan/DBT.lsp)).
- Buka editor teks (seperti Notepad) dan tempelkan kode tersebut.
- Simpan file dengan ekstensi .lsp, misalnya DisplayBlockAttributes.lsp.

### 3. Memuat Skrip di ZWCAD:
- Buka ZWCAD.
- Ketik APPLOAD di command line dan tekan Enter.
- Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.
- Setelah berhasil dimuat, tutup jendela Load Application.

### 4. Menjalankan Program:
- Ketik DBT di command line dan tekan Enter.
- Selanjutnya akan diminta untuk memilih metode: Select atau Layer.
- Jika memilih Select:
- Pilih objek blok yang ingin Anda tampilkan atributnya.
- Jika memilih Layer:
- Program akan mencari semua objek pada layer "FDS".
- Setelah memilih metode, masukkan jarak vertikal untuk ROOM_NAME, ROOM_CODE, dan SWBS sesuai permintaan.
- Program akan menempatkan teks berdasarkan atribut yang diambil dari blok yang dipilih.

### 5. Verifikasi Hasil:
- Periksa area di sekitar objek yang telah  di pilih untuk memastikan teks telah ditambahkan dengan benar sesuai dengan jarak yang sudah dimasukkan.
