# Algeo01-21110

## TUGAS BESAR 2 IF2123 ALJABAR LINIER DAN GEOMETRI SISTEM PERSAMAAN LINIER DETERMINAN, DAN APLIKASINYA

### SEMESTER 1 TAHUN 2022/2023

### Kelompok 21 DewaLoKi

 Disusun Oleh :

- 13521069 Louis Caesa Kesuma
- 13521082 Farizki Kurniawan
- 13521173 Dewana Gustavus Haraka Otang

### Table of Contents

1. [Deskripsi Program](#deskripsi-program)
2. [Cara Menjalankan Program](#cara-menjalankan-program)
3. [Tekonologi yang Digunakan](#tekonologi-yang-digunakan)
4. [Tampilan Menu](#tampilan-menu)
5. [Cara Menggunakan](#cara-menggunakan)
6. [Contoh Penggunaan](#contoh-penggunaan)

### Deskripsi Program
Program ini adalah program pengenalan wajah dengan menggunakan metode eigenface. Program menggunakan kumpulan citra wajah yang sudah disimpan pada database lalu berdasarkan kumpulan citra wajah tersebut, program dapat mempelajari bentuk wajah lalu mencocokkannya dengan citra wajah di database yang telah dipelajarinya. 

### Cara Menjalankan Program

```sh
git clone https://github.com/DewanaGustavus/Algeo02-21069.git

cd Algeo02-21069

cd src

python main.py
```

### Tekonologi yang Digunakan

- Python
- OpenCV
- Tkinter
- PIL

### Tampilan Menu

- Menu pilihan tipe recognition
![Main Menu](https://cdn.discordapp.com/attachments/702842263704961064/1044612428471742514/image.png)
- Menu file
![Files](https://cdn.discordapp.com/attachments/702842263704961064/1044614271432138782/image.png)
- Menu kamera
![Camera](https://cdn.discordapp.com/attachments/702842263704961064/1044614412809535608/image.png)

### Cara Menggunakan

1. jalankan program sesuai dengan [intruksi di atas](#cara-menjalankan-program).
2. pilih tipe recognition menggunakan files/menggunakan kamera sesuai keinginan.
3. Klik select dataset dan pilih folder yang berisi dataset gambar.
4. Klik training untuk men-train program dengan dataset yang diberikan.
5. Untuk recognition menggunakan files piilh gambar yang ingin di recognize pada bagian select image lalu klik recognize.
6. Untuk recognition menggunakan camera posisikan kamera lalu klik recognize apabila dirasa kamera sudah pas.
7. Program akan melakukan face recognition dan akan menampilkan gambar pada dataset yang mirip dengan input.

### Contoh Penggunaan

![files](https://cdn.discordapp.com/attachments/702842263704961064/1044617548064370698/image.png)
![kamera](https://cdn.discordapp.com/attachments/702842263704961064/1044619643173736509/image.png)