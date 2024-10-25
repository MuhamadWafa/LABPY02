# BIODATA
# MUHAMAD WAFA MUFIDA ZULFI
# 312410334
# TI.24.A4
# BAHASA PEMOGRAMAN

## LATIHAN 1
### MEMBUAT PROGRAM MENENTUKAN NILAI AKHIR
### DESKRIPSI

Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.
- 20% untuk nilai tugas
- 40% untuk nilai UTS
- 40% untuk nilau UAS
- 
### PENJELASAN PROGRAM

 1.Input: Meminta nama siswa dan nilai UTS, UAS, serta tugas.
 
 2. Perhitungan: Menghitung nilai akhir dengan bobot yang sesuai.
    
 3. Keterangan: Menentukan apakah siswa lulus atau tidak berdasarkan nilai akhir.
    
 4. Penentuan Huruf: Mengonversi nilai akhir menjadi huruf sesuai dengan kriteria yang diberikan.
    
 5. Output: Menampilkan hasil perhitungan.

### STRUKTUR PROGRAM

Input:

• Nama siswa

• Nilai UTS (float)

• Nilai UAS (float)

• Nilai Tugas (float)

Output:

• Nama siswa

• Nilai UTS

• Nilai UAS

• Nilai Tugas

• Nilai Akhir

• Nilai Huruf

• Keterangan ("LULUS" atau "TIDAK LULUS")

## BERIKUT SCREENSHOT VISUALCODE

<img width="960" alt="Screenshot 2024-10-25 142332" src="https://github.com/user-attachments/assets/8f6abfb8-ee26-4af4-a322-a7f60e2f69ef">

## LATIHAN 2
### MEMBUAT PROGRAM MENAMPILKAN GAJI KARYAWAN
### DESKRIPSI

Program ini menerima input gaji, status keluarga (sudah berkeluarga atau belum), dan status kepemilikan rumah dari pengguna, kemudian melakukan beberapa pengecekan sebagai berikut:

1. Apakah gaji di atas UMR (Upah Minimum Regional).

2. Jika gaji di atas UMR, program akan mengecek apakah pengguna sudah berkeluarga untuk menentukan kewajibam mengikuti asuransi dan menabung.

3. Program juga mengecek apakah pengguna memiliki rumah untuk menentukan kewajiban membayar pajak rumah.

### PENJELASAN PROGRAM
1. Input Data Karyawan:

Program meminta input dari pengguna untuk nama karyawan, gaji pokok, dan total potongan gaji.
Menghitung Gaji Bersih:

2. Menghitung Gaji Bersih:

   Gaji bersih dihitung dengan mengurangi gaji pokok dengan total potongan:
   
gaji_bersih

gaji_pokok
−
potongan
```
gaji_bersih=gaji_pokok−potongan
```
4. Output:

   Program mencetak rincian gaji karyawan, termasuk nama, gaji pokok, potongan, dan gaji bersih.

### STRUKTUR PROGRAM
```
• Input:

• Gaji (int)

• Status berkeluarga (Y/T)

• Status kepemilikan rumah (Y/T)

• Output:

• Apakah gaji sudah di atas UMR atau belum

• Kewajiban mengikuti asuransi jika sudah berkeluarga

• Kewajiban membayar pajak rumah jika punya rumah
```

### GAJI DI BAWAH UMR

![WhatsApp Image 2024-10-25 at 15 18 35_fde8077b](https://github.com/user-attachments/assets/1a68e75b-8743-461e-831b-ca0bc138a761)

## BERIKUT SCREENSHOT VISUALCODE

<img width="960" alt="Screenshot 2024-10-25 142936" src="https://github.com/user-attachments/assets/904a4385-f572-4048-8622-d35b49832384">

## LATIHAN 3
### PENGGUNAAN KONDISI OR
### DESKRIPSI 
Kondisi OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih ekspresi kondisi. Dalam bahasa pemrograman Python, operator ini memungkinkan kita untuk memeriksa beberapa kondisi sekaligus. Jika salah satu atau lebih dari kondisi tersebut bernilai True, maka keseluruhan pernyataan akan dianggap True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.
Penggunaan kondisi OR sangat berguna dalam berbagai situasi di mana beberapa kondisi perlu dievaluasi. Operator ini memudahkan pengambilan keputusan dalam logika program, sehingga membuat kode menjadi lebih ringkas dan efisien. Dengan memahami cara kerja OR, programmer dapat menciptakan skrip yang lebih kompleks dan dinamis.

### PENJELASAN OR
1. Definisi
Operator OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih kondisi. Dalam Python, operator ini ditulis sebagai or. Jika salah satu dari kondisi tersebut bernilai True, maka keseluruhan ekspresi juga akan bernilai True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.
2. Sintaksis
Penggunaan dasar operator OR dalam Python adalah sebagai berikut:

```PYTHON
if kondisi1 or kondisi2:
    # lakukan sesuatu
```
3. Contoh Penggunaan
   
a. Pemeriksaan Sederhana Misalnya, kita ingin mengecek apakah sebuah angka berada di luar rentang tertentu:

```PYHTON
angka = 7
if angka < 5 or angka > 10:
    print("Angka tidak dalam rentang 5 hingga 10")
else:
    print("Angka dalam rentang 5 hingga 10")
```

b. Kelayakan dalam Konteks Bisnis Dalam bisnis, kita mungkin perlu memverifikasi kelayakan berdasarkan beberapa syarat:

```PYTHON
gaji = 2500000
memiliki_rumah = True

if gaji > 5000000 or memiliki_rumah:
    print("Kelayakan pinjaman terverifikasi")
else:
    print("Kelayakan pinjaman tidak terpenuhi")
```
Jika gaji lebih dari 5.000.000 atau pemohon memiliki rumah, mereka dianggap layak untuk pinjaman.

c. Logika dalam Pendidikan Dalam konteks pendidikan, kita dapat menggunakan OR untuk mengevaluasi nilai siswa:

```PYHTON
if a + b == c or b + c == a or c + a == b:
    print("BENAR")
else:
    print("SALAH")
```

Program ini memeriksa apakah jumlah dua bilangan sama dengan bilangan ketiga. Jika salah satu kondisi terpenuhi, outputnya adalah "BENAR".

4. Keuntungan Menggunakan OR
   
Menyederhanakan Kode: Operator OR memungkinkan kita untuk menggabungkan beberapa kondisi dalam satu pernyataan, yang membuat kode lebih bersih dan mudah dibaca.

Fleksibilitas: Dengan menggunakan OR, kita bisa menetapkan kriteria yang lebih fleksibel untuk logika keputusan.

### KESIMPULAN
Operator OR adalah alat yang sangat berguna dalam pemrograman untuk mengevaluasi beberapa kondisi. Memahami cara kerjanya memungkinkan programmer untuk membuat logika yang lebih kompleks dan dinamis dalam aplikasi mereka. Jika ada yang ingin Anda tanyakan lebih lanjut, silakan beri tahu!

### STRUKTUR PROGRAM
1. Input Data:

Menggunakan input() untuk meminta pengguna memasukkan nama, gaji, dan status kepemilikan rumah.
Gaji diambil sebagai float untuk memungkinkan nilai desimal.
Status kepemilikan rumah diubah menjadi boolean dengan membandingkan input dengan "Y".

2. Proses Logika Menggunakan OR:

Menggunakan pernyataan if untuk mengevaluasi apakah gaji lebih dari 5.000.000 atau jika pengguna memiliki rumah.
Jika salah satu kondisi bernilai True, maka variabel kelayakan diatur menjadi "layak untuk mendapatkan pinjaman." Jika tidak, diatur menjadi "tidak layak untuk mendapatkan pinjaman."

3. Output Hasil:

Menggunakan print() untuk menampilkan hasil kepada pengguna, termasuk nama, gaji, dan kelayakan pinjaman.

## BERIKUT HASIL SCREENSHOOT VISUALCODE

<img width="960" alt="Screenshot 2024-10-25 143250" src="https://github.com/user-attachments/assets/d2faeea6-7cb9-46a7-b65d-2dfd9ff278c9">















