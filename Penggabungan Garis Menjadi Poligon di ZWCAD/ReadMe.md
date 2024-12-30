# Deskripsi Program
Program ini adalah skrip AutoLISP yang dirancang untuk digunakan dalam ZWCAD, yang berfungsi untuk menggabungkan garis-garis yang terpilih menjadi satu poligon tertutup. Skrip ini melakukan langkah-langkah berikut: pertama, pengguna memilih objek yang ingin digabungkan. Program kemudian akan mengekstrak garis-garis dari objek yang dipilih, menghapus duplikat titik, dan akhirnya menggambar poligon tertutup berdasarkan titik-titik yang telah dikumpulkan. Program ini sangat berguna untuk menyederhanakan proses menggambar dan mengelola objek dalam desain teknik.

# Tutorial Cara Menjalankan Program di ZWCAD
### 1. Persiapan Lingkungan:
- Pastikan memiliki ZWCAD terinstal di komputer.
- Siapkan gambar yang berisi garis-garis yang ingin digabungkan menjadi poligon.

### 2. Menyimpan Skrip:
- Salin kode program di atas ([BBAN](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-Electrical/blob/main/Penggabungan%20Garis%20Menjadi%20Poligon%20di%20ZWCAD/BBNA%20-%20kotak%20miring%20dan%20lengkung.lsp)).
- Buka editor teks (seperti Notepad) dan tempelkan kode tersebut.
- Simpan file dengan ekstensi .lsp, misalnya CombineLinesToPolygon.lsp.

### 3. Memuat Skrip di ZWCAD:
- Buka ZWCAD.
- Ketik APPLOAD di command line dan tekan Enter.
- Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.
- Setelah berhasil dimuat, tutup jendela Load Application.

### 4. Menjalankan Program:
- Ketik BBAN di command line dan tekan Enter.
- Selanjutnya akan diminta untuk memilih objek yang ingin digabungkan. Pilih objek yang terdiri dari garis-garis.
- Setelah memilih objek, program akan mengekstrak garis-garis tersebut, menghapus titik duplikat, dan menggambar poligon tertutup berdasarkan titik-titik yang telah dikumpulkan.

### 5. Verifikasi Hasil:
- Periksa area di sekitar objek yang telah di pilih untuk memastikan poligon telah digambar dengan benar.
