# Deskripsi Program
Program ini adalah skrip AutoLISP yang dirancang untuk digunakan dalam ZWCAD, yang berfungsi untuk membuat garis tepi (outline) secara otomatis berdasarkan objek yang dipilih oleh pengguna. Skrip ini melakukan langkah-langkah berikut: pertama, pengguna memilih objek yang ingin dianalisis. Program kemudian akan menghitung bounding box dari setiap objek yang dipilih, mengelompokkan bounding box yang saling bersentuhan, dan akhirnya menggambar garis tepi yang mengelilingi setiap kelompok bounding box. Program ini sangat berguna untuk mempercepat proses pembuatan outline dalam desain teknik.

# Tutorial Cara Menjalankan Program di ZWCAD
### Persiapan Lingkungan:
- Pastikan Anda memiliki ZWCAD terinstal di komputer.
- Siapkan gambar yang berisi objek-objek yang ingin dibuat garis tepinya.

### Menyimpan Skrip:
- Salin kode program di atas ([Outline](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-Electrical/blob/main/Pembuatan%20Garis%20Tepi%20Otomatis%20Berdasarkan%20Objek%20yang%20Dipilih%20di%20ZWCAD/Outline.lsp)).
- Buka editor teks (seperti Notepad) dan tempelkan kode tersebut.
- Simpan file dengan ekstensi .lsp, misalnya CreateOutline.lsp.

### Memuat Skrip di ZWCAD:
- Buka ZWCAD.
- Ketik APPLOAD di command line dan tekan Enter.
- Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.
- Setelah berhasil dimuat, tutup jendela Load Application.

### Menjalankan Program:
- Ketik OUTLINE di command line dan tekan Enter.
- Selanjutnya akan diminta untuk memilih objek yang ingin dianalisis. Pilih objek-objek yang diinginkan.
- Setelah memilih objek, program akan menghitung bounding box, mengelompokkan objek yang saling bersentuhan, dan menggambar garis tepi untuk setiap kelompok.

### Verifikasi Hasil:
- Periksa area di sekitar objek yang telah dipilih untuk memastikan garis tepi telah digambar dengan benar.
