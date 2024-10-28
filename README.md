### Nama : Sovy Aprianti
### Nim : 312410344
### Kelas : TI.24.A4
### Matkul : Bahasa Pemrograman

# Struktur Kondisi

Penggunaan struktur kondisi menggunakan statement `if`, Konsep pemrograman yang memungkinkan program untuk mengambil keputusan berdasarkan kondisi atau pernyataan tertentu. Struktur seleksi kondisi yang umum digunakan dalam Python

if : Digunakan untuk mengevaluasi suatu kondisi. Jika kondisi tersebut benar (True)

else : Digunakan untuk menentukan apa yang terjadi jika kondisi `if` adalah salah (False)

elif : digunakan untuk mengevaluasi beberapa kondisi. Jika kondisi `if` pertama salah, Python akan mengevaluasi kondisi `elif`. Anda bisa memiliki beberapa `elif`

# Soal Latihan

![Screenshot From 2024-10-24 20-34-23](https://github.com/user-attachments/assets/a5da9cfa-2132-4689-b60c-b3daf3ab3092)

# Program Menentukan Nilai Akhir

```python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")

akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
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
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````

Untuk menentukan nilai akhir pada Python, Anda bisa menggunakan pernyataan `return` untuk menandai akhir fungsi atau Menggunakan fungsi `print()` dan menentukan nilai yang akan dikembalikan. Pernyataan `return` dapat mengembalikan berbagai jenis data, seperti `integer`, `float`, `string`, `list`, `dictionary`, dan fungsi lainnya.

```python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
````
Fungsi `input()` adalah fungsi untuk menerima masukan dari pengguna dalam bentuk string, 

```python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````
Fungsi `int(tugas)`, `int(uts)`, dan `int(uas)` digunakan untuk mengonversi nilai input (yang masih berupa string) menjadi bilangan bulat (integer).

```python
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````
Jika nilai `akhir` lebih besar dari 60, maka `keterangan` berisi "LULUS", jika tidak, maka "TIDAK LULUS"

```Python
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

Ini adalah Struktur Kondisi Yang Menggunakan `If`, `Elif`, dan `Else`

```Python
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````

Fungsi `Print()` ini akan mencetak Variable-Variable program tersebut

