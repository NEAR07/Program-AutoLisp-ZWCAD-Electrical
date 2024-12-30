# Deskripsi
Program ini adalah skrip AutoLISP yang dirancang untuk digunakan dalam ZWCAD, yang berfungsi untuk menambahkan garis tepi melengkung di sekitar objek teks dan mtext yang dipilih oleh pengguna. Skrip ini memungkinkan pengguna untuk menentukan faktor offset dan radius fillet untuk sudut garis tepi. Setelah pengguna memilih teks, program akan menghitung posisi dan ukuran teks, kemudian menggambar garis tepi berbentuk kotak dengan sudut melengkung di sekeliling teks tersebut. Program ini sangat berguna untuk meningkatkan tampilan teks dalam desain teknik.

# Tutorial Cara Menjalankan Program di ZWCAD

### 1. Persiapan Lingkungan:
- Pastikan memiliki software ZWCAD terinstal di komputer.
- Siapkan gambar yang berisi objek teks atau mtext yang ingin ditambahkan garis tepinya.

### 2. Menyimpan Skrip:
- Salin kode program di atas ([TextOutline](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-Electrical/blob/main/Pembuatan%20Garis%20Tepi%20Melengkung%20untuk%20Teks%20di%20ZWCAD/Square%20Round%20Corner.lsp)).
- Buka editor teks (seperti Notepad) dan tempelkan kode tersebut.
- Simpan file dengan ekstensi .lsp, misalnya TextOutline.lsp.

### 3. Memuat Skrip di ZWCAD:
- Buka ZWCAD.
- Ketik APPLOAD di command line dan tekan Enter.
- Di jendela yang muncul, cari file .lsp yang telah Anda simpan dan klik Load.
- Setelah berhasil dimuat, tutup jendela Load Application.

### 4. Menjalankan Program:
- Ketik TEXTOUTLINE di command line dan tekan Enter.
- Selanjutnya akan diminta untuk memilih objek teks atau mtext. Pilih objek yang diinginkan.
- Setelah memilih teks, masukkan faktor offset untuk garis tepi (misalnya 0.8 atau 1.5) dan radius fillet untuk sudut (misalnya 0.5 atau 1.0) sesuai permintaan.
- Program akan menggambar garis tepi melengkung di sekitar teks yang dipilih.

### 5. Verifikasi Hasil:
- Periksa area di sekitar teks yang dipilih untuk memastikan garis tepi telah digambar dengan benar dan sudutnya melengkung sesuai dengan pengaturan yang sudah dimasukkan.
