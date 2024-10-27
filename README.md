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

```python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````
Fungsi dari integer dalam pemrograman adalah untuk merepresentasikan nilai bilangan bulat, baik positif maupun negatif, serta nol. Integer biasanya digunakan dalam operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.

fungsi dari * untuk mengkalikan angka,dan fungsi dari ` .2` adalah 0 koma 2

dan nilai tugas yang di masukan 90 ,maka akan dikalikan program di atas  .2 yaitu( 0.2) maka keluar cetakan 18

```python
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````
keterangan ini hanya sebuah variable yang nantinya akan di cetakan,dan hasil ahkir akan memproses 

```python
if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"
````
ini adalah struktur kondisi yang menggunakan if, elif , dan`else`

```python
if akhir > 80:
huruf = "A"
````
jika hasil dari nilai tersebut lebih besar dari 80 maka output yang keluar (A)

```python
else:
huruf = "E"
````
jika tidak sesuai semuanya pada program di atas output akan keluar(E)


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
struktur ini menggunakan kondisi if, elif, dan else

```python
gaji = int(input("Masukkan gaji:"))
````
inputan ini akan memasukan angka gaji,karena memiliki fungsi int

```python
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]
````
inputan ini menggunakan fungsi string yang di masukan berupa huruf,dan (false,true) ini adalah fungsi pemilihan Ya atau Tidak,agar tidak meggunakan if di lanjutan program tersebut

```python
if gaji > 2500000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
````
jika angka gaji angka gaji lrbih dari 3 juta maka output yang keluar"gaji sudah diatas UMR" dan jika tidak,output yang keluar"Tidak perlu ikut asuransi"

```python
if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
````
Jika memiliki rumah maka output yang keluar adalah"Wajib bayar pajak", Jika tidak mempunyai rumah maka output yang keluar ialah "Tidak wajib bayar pajak"

```python
else:
    print ("Gaji belum UMR")
````

else yang berada di paling bawah ini terhubung dengan if Gaji > 2500000: apabila gaji tidak melebihi dari 3 juta output yang keluar"gaji belum UMR"

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

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
operator OR dalam python merubah beberapa kondisi dan mengembalikan true jika salah satu benar.

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
````
Program ini menginputkan sesuatu integer yang menggunakan variable
a,b,c.

```python
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````
jika (A) ditambah (B) haslnya (C) atau bahasa pemograman itu OR ,dan apabila (B) ditambah (C) hasilnya (A),dan (C) ditambah (A) maka hasilnya (B).
maka output yang keluar adalah "benar"

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

## LATIHAN 3: KASUS 1 DAN KASUS 2
### PEMESANAN TIKET BIOSKOP

Kasus 1: Program Pemesanan Tiket Bioskop
Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.

Petunjuk:

    ● Gunakan if else dan operator ternary.
    
```python
harga_reguler = 50000
harga_vip = 100000

tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))

 Menghitung total harga
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    exit()

 Menghitung diskon jika pengguna memiliki kartu member


if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
        print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
elif status_member == "tidak":
            total_harga
            print(f"total harga yang harua dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
 ````
Program ini akan menentukan harga pesanan tiket bioskop, Yang reguler/Vip, dan jika Vip harga 100.000, dan jika reguler 80.0000, dan jika memiliki kartu member pelanggan tersebut akan mendapatkan diskon 20%

```python
harga_reguler = 50000
harga_vip = 100000
````
variable ini menentukan harga tiket bioskop

```python
tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))
````
memasukan inputan sesuai Output Program (Reguler/Vip) di variable (Tipe_Tiket), dan Memasukan inputan yang output tersebut Bertanya memiliki kartu member atau tidak.

```python
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    exit()
````
Jika tipe tiket reguler total harga proses ke Harga reguler, dan jika tiket vip Total harga proses keharga vip

dan jika Selain memasukan inputan reguler/vip Output yang keluar "Tipe tiket tidak valid" dan berproses ke fungsi exit() yang artinya program dihentikan.

```python
if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
        print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
elif status_member == "tidak":
            total_harga
            print(f"total harga yang harua dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
````
desision ini menentukan mempunyai kartu member atau tidak, Jika Inputan status member menjawab "ya", maka total harga akan di kalikan dengan operator * 0,8 yang disebut diskon 20%

dan jika inputan status member "tidak", maka total harga normal

jika menginputkan selain (ya/tidak) output yang keluar "Harga tidak dapat dihitung"

Dan ini hasil program tersebut












