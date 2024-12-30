# Deskripsi Program
Program ini adalah skrip AutoLISP yang dirancang untuk digunakan dalam ZWCAD, yang memungkinkan pengguna untuk menambahkan teks berdasarkan atribut dari blok yang ada di dalam gambar. Skrip ini memungkinkan pengguna untuk memilih objek berdasarkan layer tertentu atau memilih objek secara manual. Setelah memilih objek, pengguna diminta untuk memasukkan jarak vertikal untuk tiga atribut: SID, NAM, dan .RC. Program ini kemudian akan menempatkan teks di posisi yang ditentukan berdasarkan atribut yang diambil dari blok, dengan penyesuaian horizontal yang dapat diatur. Program ini sangat berguna untuk mempercepat proses dokumentasi dan anotasi dalam desain teknik.

# Tutorial Cara Menjalankan Program di ZWCAD
### 1. Persiapan Lingkungan:
- Pastikan memiliki ZWCAD terinstal di komputer.
- Pastikan memiliki blok dengan atribut yang sesuai (SID, NAM, .RC) di dalam gambar.

### 2. Menyimpan Skrip:
- Salin kode program di atas ([ADG](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-Electrical/blob/main/Pembuatan%20Teks%20Atribut%20Blok%20di%20ZWCAD%20Berdasarkan%20Jarak%20Vertikal/ADG.lsp)).
- Buka editor teks (seperti Notepad) dan tempelkan kode tersebut.
- Simpan file dengan ekstensi .lsp, misalnya AddTextAttributes.lsp.

### 3. Memuat Skrip di ZWCAD:
- Buka ZWCAD.
- Ketik APPLOAD di command line dan tekan Enter.
- Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.
- Setelah berhasil dimuat, tutup jendela Load Application.

### 4. Menjalankan Program:
- Ketik ADG di command line dan tekan Enter.
- Selanjutnya akan diminta untuk memilih mode: LAYER atau SELECT.
- Jika memilih LAYER:
- Program akan mencari semua objek di layer "PENETRATION".
- Jika memilih SELECT:
- Anda akan diminta untuk memilih objek secara manual di layar.
- Setelah memilih mode, masukkan jarak vertikal untuk SID, NAM, dan .RC sesuai permintaan.
- Program akan menempatkan teks berdasarkan atribut yang diambil dari blok yang dipilih.

### 5. Verifikasi Hasil:
- Periksa area di sekitar blok yang telah dipilih untuk memastikan teks telah ditambahkan dengan benar sesuai dengan jarak yang dimasukkan.
